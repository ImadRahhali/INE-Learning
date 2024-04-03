# INE-Learning Platform
![LOGO](inelogo.png)
Welcome to the official repository of INE-Learning, a cutting-edge E-Learning platform designed exclusively for the students of INPT. INE-Learning is an interactive environment where students can share and gain knowledge, empowering each other through education. Our platform stands out by offering a user-friendly interface, a wide range of courses, and seamless interaction between students.

![Landing Page](inelearningdesign.png)
Start your learning journey here : https://ine-learning-client.vercel.app/
## Features

- **Custom Course Creation:** Students can create, share, and manage their courses, contributing to a vast library of resources.
- **Interactive Learning:** Engage with courses through comments, ratings, and feedback.
- **Personalized User Experience:** Tailored course recommendations and notifications to keep you updated.
- **Secure Authentication:** Robust security measures to protect user data and ensure a safe learning environment.

## Technologies

This project leverages modern web development technologies and practices:

- **Frontend:** ReactJS for a dynamic and responsive user interface.
- **Backend:** Spring Boot, offering a powerful suite of features for building web applications.
- **Database:** MongoDB, a NoSQL database, for flexible data storage.
- **Authentication:** JSON Web Token (JWT) for secure authentication.
- **Storage:** Firebase for storing videos and thumbnails, ensuring high availability and scalability.
- **Testing:** Comprehensive testing strategies, including unit and integration tests, to ensure reliability and performance.
- **DevOps:** Docker and Kubernetes for automated development processes, deployment, and management, ensuring fast and reliable delivery of functionality to end users.


## Getting Started

To get the platform up and running on your local machine, follow these steps:

1. **Clone the repository**

```bash
git clone https://github.com/TahirRida/INE-Learning
```

2. **Install dependencies**

For the backend (Spring Boot):
```bash
cd Backend
./mvnw install
```

For the frontend (ReactJS):
```bash
cd Frontend/inelearning
npm install
```

3. **Configure Environment Variables**

Ensure you have the necessary environment variables set up for both the frontend and backend, including database credentials and Firebase API keys.

4. **Run the Application**

Backend:
```bash
./mvnw spring-boot:run
```

Frontend:
```bash
npm start
```

Visit `http://localhost:3000` to view the application.

## Testing

Our application includes extensive testing to ensure functionality and reliability:

- **Backend Testing:** Utilizes JUnit and Mockito for unit and integration tests.
- **Frontend Testing:** Employs React Testing Library to simulate user interaction.
- **Security Testing:** Conducted to identify and mitigate potential vulnerabilities.

## DevOps
### Docker and Kubernetes Integration

In this DevOps section, we automate development, deployment, and management for fast and reliable delivery of functionality to end users in the INE-Learning platform.

- **Docker for Development and Deployment:** We use Docker to containerize our backend and frontend, ensuring a consistent development environment, simplified dependency management, and seamless scaling.
- **Kubernetes for Orchestration**: We use Kubernetes to automate deployment, scaling, and operations for high availability and reliability of our Docker containers.

Together, Docker and Kubernetes form a powerful combination that empowers us to deliver a stable and scalable E-Learning platform, meeting the needs of our users effectively.


## Contributing

We welcome contributions from the INPT community! If you have suggestions for improvements or new features, feel free to fork the repository, make changes, and submit a pull request.

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Acknowledgements

- ReactJS Community
- Spring Boot Team
- MongoDB
- Firebase
- Docker
- Kubernetes
- And every contributor who has helped make INE-Learning a reality!

