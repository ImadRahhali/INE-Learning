# Stage 1: Build the React app
FROM node:16.14.0-alpine AS build
WORKDIR /app
COPY package.json ./
COPY yarn.lock ./
RUN npm install
COPY . .
RUN npm run build

# Stage 2: Serve the React app
FROM nginx:alpine
COPY --from=build /app/build /usr/share/nginx/html
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]
