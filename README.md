﻿# Smart Contact Manager

Welcome to **Smart Contact Manager**! This application offers a comprehensive set of features to enhance your user experience, including streamlined account registration, enhanced contact management, data export capabilities, and more.

## 🌟 Features

### 🔐 Account Registration and Verification
- **Email and Third-Party Providers**: Effortlessly register and verify accounts via email or through third-party providers like Google and GitHub.
- **Streamlined Process**: Enjoy a simplified and user-friendly account registration process.

### 📇 Contact Management
- **Enhanced Contact Management**: Manage your contacts with ease, featuring cloud-stored pictures and a streamlined email drafting process.
- **Cloud Storage**: Utilize AWS S3 and Cloudinary API for secure and efficient storage of contact pictures.

### 📊 Data Export and Customization
- **Export to Excel**: Seamlessly export your data to Excel using the Excel API.
- **Favorites Marking**: Mark your favorite contacts or items for quick and easy access.
- **Profile Customization**: Personalize your user profile with a variety of customization options.
- **Theme Toggling**: Toggle between different themes based on user feedback for an optimal viewing experience.

## 🛠 Technologies Used

- **Backend**: Spring Boot for building a robust and scalable backend application.
- **Cloud Storage**: AWS S3 and Cloudinary API for efficient media file management and storage.
- **API Development**: REST API for smooth and efficient client-server communication.
- **Excel Integration**: Excel API for easy data export to Excel.
- **Frontend**: Tailwind CSS and JavaScript for a responsive and interactive user interface.
- **User Feedback**: Feedback API for collecting and implementing valuable user feedback.

## 🚀 Setup Instructions

### Prerequisites

- Java 11 or higher
- Maven
- Node.js and npm
- AWS Account for S3
- Cloudinary Account

### Backend Setup

1. **Clone the repository:**
   ```sh
   git clone https://github.com/yourusername/smart-contact-manager.git
   cd smart-contact-manager

2. Configure AWS S3 and Cloudinary:

- Set up your AWS credentials for S3.
- Obtain your Cloudinary API key and secret.
- Update the application.properties file:

3. **properties:**
   ```sh
    spring.datasource.url=jdbc:mysql://localhost:3306/yourdatabase
    spring.datasource.username=yourusername
    spring.datasource.password=yourpassword
    cloud.aws.credentials.accessKey=yourAWSAccessKey
    cloud.aws.credentials.secretKey=yourAWSSecretKey
    cloudinary.cloud_name=yourCloudName
    cloudinary.api_key=yourAPIKey
    cloudinary.api_secret=yourAPISecret
    Build and run the backend:
   
4. **Build and run the backend:**
   ```sh
    mvn clean install
    mvn spring-boot:run
   
### Frontend Setup
1. **Navigate to the frontend directory:**
   ```sh
    cd frontend
2. **Install dependencies:**
   ```sh
    npm install
   
3. **Run the frontend:**
   ```sh
    npm start
4 **Access the application:**
Open your web browser and navigate to [http://localhost:3000](http://localhost:8080/login).

