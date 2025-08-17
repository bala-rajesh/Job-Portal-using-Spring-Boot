# Job Portal Application 💼

This project is a full-stack job portal application designed to connect employers with potential employees. It allows employers to create and post job listings, while job seekers can browse and search for relevant opportunities. The application features a user-friendly interface, robust search functionality, and a streamlined job posting process.

## 🚀 Key Features

- **Job Posting**: Employers can easily create and post job listings with detailed descriptions, required experience, and necessary technologies.
- **Job Search**: Job seekers can search for jobs based on keywords, skills, and location.
- **User-Friendly Interface**: The application provides an intuitive and easy-to-navigate interface for both employers and job seekers.
- **Responsive Design**: The frontend is designed to be responsive and accessible on various devices.
- **API Documentation**: Swagger UI is integrated into the backend for easy API exploration and testing.

## 🛠️ Tech Stack

- **Frontend**:
    - React
    - React Router DOM
    - Axios
    - Tailwind CSS
    - Vite
- **Backend**:
    - Spring Boot
    - Spring Data MongoDB
    - Java
- **Database**:
    - MongoDB
- **Build Tools**:
    - Maven
    - npm

## 📦 Getting Started

Follow these steps to set up the project locally.

### Prerequisites

- Node.js (v16 or higher)
- Java Development Kit (JDK 11 or higher)
- Maven
- MongoDB

### Installation

1.  **Clone the repository:**

    ```bash
    git clone https://github.com/bala-rajesh/Job-Portal-using-Spring-Boot
    cd <project_directory>
    ```

2.  **Backend Setup:**

    - Navigate to the `backend` directory:

      ```bash
      cd backend
      ```

    - Build the project using Maven:

      ```bash
      mvn clean install
      ```

    - Run the Spring Boot application:

      ```bash
      mvn spring-boot:run
      ```

    - Ensure MongoDB is running. You may need to configure the connection string in `backend/src/main/resources/application.properties` if it's not the default.

3.  **Frontend Setup:**

    - Navigate to the `frontend` directory:

      ```bash
      cd ../frontend
      ```

    - Install the dependencies:

      ```bash
      npm install
      ```

### Running Locally

1.  **Backend:**

    - Ensure the Spring Boot application is running (see Backend Setup).  It typically runs on `http://localhost:8080`.

2.  **Frontend:**

    - Start the development server:

      ```bash
      npm run dev
      ```

    - The frontend application will be accessible at `http://localhost:5173` (or another port if configured differently).

## 💻 Project Structure

```
📂 Job Portal Application
├── 📁 backend
│   ├── 📁 src
│   │   ├── 📁 main
│   │   │   ├── 📁 java
│   │   │   │   ├── 📁 com
│   │   │   │   │   ├── 📁 mahmudalam
│   │   │   │   │   │   ├── 📁 jobportal
│   │   │   │   │   │   │   ├── 📁 spring_boot_job_portal_app
│   │   │   │   │   │   │   │   ├── 📄 SpringBootJobPortalAppApplication.java
│   │   │   │   │   │   │   │   ├── 📁 interfaces
│   │   │   │   │   │   │   │   │   ├── 📄 JobPostRepository.java
│   │   │   │   │   │   │   │   │   ├── 📄 SearchRepository.java
│   │   │   │   │   │   │   │   ├── 📁 model
│   │   │   │   │   │   │   │   │   ├── 📄 JobPostModel.java
│   │   │   │   │   │   │   │   ├── 📁 controller
│   │   │   │   │   │   │   │   │   ├── 📄 JobPostController.java
│   │   │   ├── 📁 resources
│   │   │   │   ├── 📄 application.properties
│   ├── 📄 pom.xml
├── 📁 frontend
│   ├── 📁 src
│   │   ├── 📁 components
│   │   │   ├── 📄 Layout.jsx
│   │   ├── 📁 pages
│   │   │   ├── 📄 CreatePost.jsx
│   │   │   ├── 📄 Feed.jsx
│   │   │   ├── 📄 Home.jsx
│   │   │   ├── 📄 NotFound.jsx
│   │   ├── 📁 api
│   │   │   ├── 📄 api.js
│   │   ├── 📄 App.jsx
│   │   ├── 📄 main.jsx
│   │   ├── 📄 index.css
│   ├── 📁 public
│   │   ├── 📄 vite.svg
│   ├── 📄 vite.config.js
│   ├── 📄 package.json
│   ├── 📄 package-lock.json
├── 📄 README.md
```



## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1.  Fork the repository.
2.  Create a new branch for your feature or bug fix.
3.  Make your changes and commit them with descriptive messages.
4.  Push your changes to your fork.
5.  Submit a pull request.

## 📝 License

This project is licensed under the [MIT License](LICENSE).

## 📬 Contact

If you have any questions or suggestions, feel free to contact me at [kunapareddybalarajesh@gmail.com](mailto:kunapareddybalarajesh@gmail.com).

## 💖 Thanks Message

Thank you for checking out this project! I hope it's helpful and that you find it interesting. Your feedback and contributions are highly appreciated.



