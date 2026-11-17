# Cars Dealership - Full-stack Development Capstone Project

**Project Name:** Cars Dealership Application  
**Author:** Jaideep726  
**Description:** A modern, full-stack, responsive web application for a national car retailer in the United States. The platform enables users to browse nationwide dealership branches across various states, view and post customer reviews for cars, and leverage microservice-driven sentiment analysis.

## Key Features & Architecture
- **Frontend:** React with Bootstrap 5 for dynamic single-page responsiveness.
- **Backend Core:** Django REST Framework handling authentication, user sessions, and proxying.
- **Microservices:**
  - **Dealer & Reviews Database:** Express.js + MongoDB backend storing dealership records and car reviews.
  - **Sentiment Analysis:** Python/Flask microservice analyzing customer review text polarity with NLTK.
- **Containerization & Deployment:** Dockerized multi-tier setup deployed on IBM Cloud Code Engine and Kubernetes.
