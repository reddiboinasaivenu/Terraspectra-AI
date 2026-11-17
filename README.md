<<<<<<< HEAD
# 🌱 TerraSpectra-AI

### Explainable Spectral Intelligence for Wheat Disease Detection

**Turning Hyperspectral Data into Explainable Agricultural Intelligence**

---

## 📌 Project Overview

TerraSpectra-AI is an AI-powered precision agriculture platform designed to detect fungal diseases and physiological stress in wheat crops using hyperspectral imaging and machine learning.

Unlike conventional RGB imaging techniques, which mainly capture visible colour changes, TerraSpectra-AI analyzes spectral information across Visible and Near-Infrared (VNIR) and Short-Wave Infrared (SWIR) wavelengths to identify subtle changes in crop reflectance.

The platform aims to support early disease detection, crop health monitoring, and explainable AI-based agricultural decision-making.

## 📅 Day 1 — Backend Development and FastAPI Setup

**Role:** Backend Developer

**Focus Area:** Backend Architecture and API Development

### 1. Objectives

The primary objective of Day 1 was to establish the backend foundation of TerraSpectra-AI using FastAPI. The work focused on preparing the application structure, defining API schemas, developing basic endpoints, and creating a foundation for future machine-learning model integration.

### 2. Tasks Planned

- **FastAPI Project Setup**
  - Initialize the backend project using Python and FastAPI.
  - Configure the application entry point.
  - Set up the required dependencies.
  - Configure Uvicorn for running the backend server.

- **API Structure and Schemas**
  - Design a modular backend architecture.
  - Organize API routes and application modules.
  - Create Pydantic schemas for request and response validation.
  - Define structured data formats for API communication.

- **Basic API Endpoints**
  - Develop initial REST API endpoints.
  - Configure HTTP request and response handling.
  - Prepare health-check and application-status endpoints.
  - Establish consistent JSON responses.

- **Future Model Prediction Endpoint**
  - Design an endpoint for future wheat disease predictions.
  - Prepare input schemas for spectral data.
  - Define the expected prediction response structure.
  - Plan integration between the backend API and trained machine-learning models.

### 3. Proposed Backend Architecture

```text
TerraSpectra-AI/
│
├── backend/
│   ├── app/
│   │   ├── main.py
│   │   ├── api/
│   │   │   └── routes.py
│   │   ├── schemas/
│   │   │   └── prediction.py
│   │   ├── services/
│   │   │   └── prediction_service.py
│   │   └── core/
│   │       └── config.py
│   │
│   └── requirements.txt
│
├── data/
├── models/
├── frontend/
└── README.md
```

### 4. Technology Stack

| Technology | Purpose |
|---|---|
| Python | Backend programming |
| FastAPI | REST API development |
| Pydantic | Data validation |
| Uvicorn | Backend server |
| JSON | Data exchange |
| Machine Learning | Future wheat disease prediction |

### 5. Proposed API Endpoints

| Method | Endpoint | Description |
|---|---|---|
| GET | `/` | Backend welcome message |
| GET | `/health` | Check API health |
| POST | `/predict` | Future wheat disease prediction |
| GET | `/docs` | Interactive API documentation |

*Note: These endpoints represent the planned API design. Update them based on actual implementation.*

### 6. Expected Prediction Workflow

1. Receive hyperspectral input data through the API.
2. Validate incoming data using Pydantic schemas.
3. Pass the validated spectral information to the prediction service.
4. Process the input using the trained machine-learning model.
5. Return the predicted crop condition and relevant results as JSON.

### 7. Learning Outcomes

- Understood FastAPI application architecture.
- Learned REST API development concepts.
- Understood request and response validation.
- Learned modular backend project organization.
- Explored the integration of machine-learning models with backend services.

### 8. Next Steps

- Complete the initial API implementation.
- Test endpoints using Swagger UI and Postman.
- Develop spectral data validation.
- Integrate the trained wheat disease detection model.
- Implement prediction responses and error handling.

### 9. Conclusion

Day 1 established the backend development foundation for TerraSpectra-AI. The initial architecture, API structure, schema design, and future model integration approach provide a foundation for building a scalable and explainable wheat disease detection platform.

---

## 🚀 Project Vision

To transform hyperspectral agricultural data into actionable intelligence by combining AI-based disease detection, spectral analysis, and explainable predictions to support smarter farming decisions.
=======
# Terraspectra-AI
Early Detection of Fungal Blight in Wheat Using Hyperspectral Imaging &amp; Hybrid Deep Learning
>>>>>>> ff05d31591d6b1ea67f706f380ac6228b8735008


## 📅 Day 1 — Backend Development & FastAPI Project Setup

**Role:** Backend Developer  
**Technology Stack:** Python, FastAPI, Pydantic, Uvicorn

### 1. Project Overview

The primary objective of Day 1 was to establish the backend foundation using FastAPI. The work focused on creating a structured backend application, defining API schemas, developing basic REST API endpoints, and preparing the architecture for future machine-learning model predictions.

### 2. Tasks Completed

- **FastAPI Project Setup**
  - Initialized the FastAPI backend project using Python.
  - Configured the application entry point.
  - Set up the development environment and required dependencies.
  - Configured Uvicorn as the ASGI server.

- **API Structure and Schemas**
  - Designed a modular backend folder structure.
  - Organized API routes, request handling, and response models.
  - Created Pydantic schemas for request validation.
  - Established a structured approach for managing API data.

- **Basic API Development**
  - Prepared basic REST API endpoints.
  - Implemented HTTP request handling.
  - Added structured JSON responses.
  - Prepared endpoints for backend health checks and application status.

- **Future Model Prediction Endpoint**
  - Designed the initial API structure for machine-learning predictions.
  - Planned request and response schemas for model inputs and outputs.
  - Prepared the integration approach for connecting a trained model with the FastAPI backend.
  - Established a foundation for future prediction services.

### 3. Suggested Project Structure

```text
backend/
│
├── app/
│   ├── main.py
│   ├── api/
│   │   └── routes.py
│   ├── schemas/
│   │   └── prediction.py
│   ├── services/
│   │   └── prediction_service.py
│   └── core/
│       └── config.py
│
├── requirements.txt
└── README.md
```

### 4. Technologies Used

| Technology | Purpose |
|---|---|
| Python | Backend programming |
| FastAPI | REST API development |
| Pydantic | Request and response validation |
| Uvicorn | Running the backend server |
| JSON | API data exchange |

### 5. Expected API Endpoints

| HTTP Method | Endpoint | Purpose |
|---|---|---|
| GET | `/` | Welcome message |
| GET | `/health` | Check backend status |
| POST | `/predict` | Future model prediction integration |

*Note: These are proposed endpoint designs. Update this section according to the endpoints actually implemented.*

### 6. Challenges and Learning Outcomes

- Understood the fundamentals of FastAPI application development.
- Learned how to organize backend modules and API routes.
- Understood request validation using Pydantic.
- Gained knowledge of REST API architecture.
- Learned how backend services can communicate with machine-learning models.

### 7. Current Status

The initial backend development plan and application structure were established. The API foundation was prepared for further development, including model integration and prediction functionality.

### 8. Next Steps

- Complete and test the API endpoints.
- Implement detailed request and response validation.
- Develop the prediction service.
- Integrate the trained machine-learning model.
- Test API functionality using Swagger UI and Postman.

### 9. Conclusion

Day 1 focused on establishing the backend development foundation using FastAPI. The project architecture, API organization, schema design, and future prediction integration approach were planned to support scalable backend development in the upcoming stages.

## 📅 Day 3 — Frontend Development

**Project:** TerraSpectra AI – Precision Agriculture & Crop Disease Detection  
**Module:** Frontend Development  
**Focus:** React Dashboard Development

### 1. Objective

The main objective of Day 3 was to begin frontend development by setting up the React application and designing a user-friendly dashboard for displaying crop disease prediction results, spectral analysis graphs, and machine learning model outputs.

### 2. Tasks Performed

**1. React Project Setup**
- Set up the frontend development environment using React.
- Organized the project structure for better code management.
- Prepared the application for reusable component development.
- Established the foundation for integrating frontend components with backend services.

**2. Dashboard Layout Design**
- Designed the initial dashboard structure.
- Planned a clean and user-friendly interface.
- Organized dashboard sections for displaying crop analysis information.
- Created a layout suitable for presenting disease detection and prediction results.

**3. Disease Prediction Components**
- Planned reusable React components for displaying disease prediction results.
- Structured result sections to present detected crop diseases.
- Prepared the interface for displaying prediction labels and confidence scores.
- Designed result components to make crop health information easier to understand.

**4. Spectral Graphs and Model Results**
- Added dashboard sections for spectral reflectance visualization.
- Planned graph components for analyzing Visible and Near-Infrared (VNIR) spectral data.
- Prepared sections for displaying Short-Wave Infrared (SWIR) analysis.
- Organized model result sections for presenting AI-based crop health predictions.

### 3. Technologies Used

| Technology | Purpose |
|---|---|
| React.js | Frontend application development |
| JavaScript | Application functionality |
| HTML5 | Dashboard structure |
| CSS3 | Dashboard styling |
| Git & GitHub | Version control |

### 4. Expected Dashboard Modules

- **Dashboard Overview:** Displays overall crop health information.
- **Disease Prediction:** Presents detected crop diseases and prediction results.
- **Spectral Analysis:** Displays spectral reflectance graphs.
- **Model Results:** Presents machine learning prediction outputs.
- **Analysis Interface:** Provides a structured view of crop assessment information.

### 5. Outcome

The Day 3 activities focused on establishing the frontend development foundation for TerraSpectra AI. The React project structure and dashboard design requirements were prepared, with dedicated sections planned for disease prediction, spectral visualization, and machine learning results.

### 6. Next Steps

- Complete the dashboard UI components.
- Implement interactive spectral graphs.
- Integrate backend APIs with the React frontend.
- Connect disease prediction results to the dashboard.
- Improve dashboard responsiveness and user experience.

**Status:** Frontend development foundation and dashboard planning.

### Day 4: SWIR Coordinate Orientation Analysis

#### Objective
The objective of this task is to analyze the SWIR (Short-Wave Infrared) hyperspectral image and verify the correct orientation of leaf pixel coordinates. This helps ensure accurate identification and extraction of leaf regions from hyperspectral images for further spectral analysis and disease prediction.

#### Tasks Performed
- Loaded the SWIR hyperspectral image using the Spectral Python library.
- Read the hyperspectral image from the `.hdr` file.
- Calculated the mean intensity across all spectral bands to generate a 2D grayscale background image.
- Loaded leaf pixel coordinates from the CSV file using Pandas.
- Tested two coordinate orientations:
  - **Orientation 1:** X = Column and Y = Row.
  - **Orientation 2:** X = Row and Y = Column.
- Plotted leaf coordinates over the grayscale SWIR image using Matplotlib.
- Compared both orientations to identify the correct coordinate alignment.
- Saved the coordinate orientation comparison image for further analysis.

#### Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib
- Spectral Python

#### Input Files
- `data/raw/SWIR_sample/01_D.hdr` – SWIR hyperspectral image.
- `data/raw/SWIR_sample/01_D_leaf1.csv` – Leaf pixel coordinate data.

#### Output Files
- `data/processed/SWIR_coordinate_orientation_comparison.png` – Visualization comparing both coordinate orientations.

#### Implementation Details
1. Imported the required Python libraries.
2. Loaded the SWIR hyperspectral image using `open_image()`.
3. Generated a grayscale image by calculating the mean across spectral bands.
4. Read the leaf coordinates from the CSV file.
5. Visualized the coordinates using two different orientation approaches.
6. Compared the visual outputs to check coordinate alignment.
7. Exported the comparison visualization at 300 DPI.

#### Expected Outcome
The coordinate orientation comparison helps determine how the leaf coordinates align with the SWIR image. Correct coordinate alignment is important for accurate leaf-region extraction and reliable hyperspectral data processing.

#### Conclusion
Successfully implemented a SWIR coordinate orientation comparison workflow. Both coordinate arrangements were visualized and saved for evaluation. This analysis supports the next stages of hyperspectral preprocessing, leaf-region extraction, spectral feature analysis, and crop disease prediction.