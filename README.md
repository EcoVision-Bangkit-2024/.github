# Eco Vision: Implies a clear, data-powered vision for waste management 🌱

<div align="center">
<img src="https://github.com/EcoVision-Bangkit-2024/.github/blob/60256e916eb2839a53b84ed41b22df1735b9ce39/Eco%20Vision.png" width="50%" height="50%" >
</div>

Welcome to the **Eco Vision** project repository! Developed by **Team 3**, this project combines Machine Learning, Cloud Computing, and Mobile Development to address waste management challenges. Eco Vision is a digital solution designed to help businesses and communities make data-driven, sustainable waste management decisions.

## Project Overview
Eco Vision focuses on waste management data collection, analysis, and visualization. The goal is to provide a streamlined platform for tracking, categorizing, and analyzing waste in real time. Our solution is tailored for environments like hotels and hospitality sectors, starting with a pilot implementation at Banyan Tree Hotel in Bali.

Eco Vision empowers organizations with actionable insights to optimize waste reduction, reuse, and recycling, thus contributing to a more sustainable future.

## Project Features
- **Real-Time Data Collection**: Gather waste data from various departments and locations within a facility.
- **Waste Categorization Model**: Leverage Machine Learning to classify waste types, facilitating better sorting and recycling.
- **Data Visualization Dashboard**: A user-friendly web-based dashboard that presents insights and trends for informed decision-making.
- **Mobile Application**: An Android app to collect and view waste data on the go, enabling real-time updates and notifications.

## Technology Stack

### 1. Machine Learning
- **TensorFlow**: Used for developing and training a custom waste categorization model.
- **Docker**: Containerized the model for deployment on Google Cloud Run, ensuring scalable and efficient processing.
  
### 2. Cloud Computing
- **Google Cloud Platform (GCP)**: Utilized for secure data storage, model deployment, and backend services.
- **Cloud Storage**: Stores categorized waste data for analytics.
- **Cloud Run**: Runs the containerized ML model in a serverless environment.
- **Cloud SQL**: Manages structured waste data with easy querying capabilities.
- **Cloud IAM**: Manages roles and permissions for secure access control.

### 3. Mobile Development
- **Android (Kotlin)**: The mobile app is developed natively for Android, providing real-time data collection and notifications for on-site waste monitoring.

## Project Structure
- **/data**: Contains data preprocessing and cleaning scripts.
- **/ml_model**: Machine Learning model training, testing, and Docker configuration.
- **/backend**: Backend services built with Node.js and Express.js, including API endpoints for data retrieval and updates.
- **/mobile_app**: Source code for the Android app developed with Kotlin.
- **/dashboard**: Frontend code for the web dashboard built with React.js, displaying data insights and analytics.

## Getting Started
### Prerequisites
- **Node.js** and **npm** for backend development
- **Docker** for containerizing the ML model
- **Android Studio** for mobile app development
- **Google Cloud Account** with necessary permissions to set up GCP resources

### Installation
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/ecovision.git
   cd ecovision
