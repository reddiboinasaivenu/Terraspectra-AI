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


## 📅 Day 4 – Backend API Setup and Frontend Integration Preparation

### 🎯 Objective
To establish the backend API infrastructure using FastAPI, prepare request and response schemas, develop a mock prediction endpoint, and create the React dashboard interface. The objective is to prepare the system for future integration with the actual hyperspectral disease prediction model.

### ✅ Tasks Completed / Planned Development

**1. FastAPI Backend Setup**
- Set up the FastAPI application.
- Configure and run the backend server locally.
- Create a `/health` endpoint to verify server availability.
- Test the health-check functionality.

**2. API Data Format and Schemas**
- Prepare `schemas.py` using Pydantic request and response models.
- Draft example API request and response formats.
- Keep the schemas provisional until the model input and output specifications are confirmed by Sanjana.
- Ensure agreement on field names and data types before integration.

**3. Mock Prediction Endpoint**
- Create a temporary `/predict` API endpoint.
- Return sample prediction responses using clearly labelled mock values.
- Use mock data only for frontend development and testing.
- Ensure mock predictions are not presented as actual model predictions.

**4. React Dashboard Development**
- Set up the React frontend.
- Design the main dashboard layout.
- Develop reusable UI components.
- Display sample prediction responses using mock data.
- Prepare the dashboard for future backend and model integration.

**5. Hyperspectral Image Tiling Test**
- Develop an independent test to divide a sample array into smaller tiles.
- Test the reconstruction process by combining the generated tiles.
- Verify that the reconstructed output matches the original sample array.
- Document the input, tiling process, and reconstructed output.

**6. Future Model Integration**
- Prepare the API and dashboard for integration with the actual hyperspectral disease prediction model.
- Plan to replace mock responses with real model predictions once the model is ready.
- Coordinate with Sanjana to confirm the model input shape, band order, preprocessing requirements, class labels, and output format.

### 🛠️ Technologies and Tools
- **Python** – Backend development.
- **FastAPI** – REST API development.
- **Pydantic** – Request and response validation.
- **React.js** – Frontend dashboard development.
- **NumPy** – Hyperspectral array and tiling operations.
- **Mock Data** – Temporary API and dashboard testing.

### 📦 Expected Deliverables
- FastAPI backend server with a working `/health` endpoint.
- Pydantic request and response schemas with documented examples.
- Mock `/predict` endpoint with clearly labelled sample values.
- React dashboard displaying sample API responses.
- Independent hyperspectral image tiling and reconstruction test.
- README documentation explaining backend and frontend installation and execution.

### ⚠️ Dataset and Project Scope Considerations
- The currently inspected sample contains controlled wheat-leaf hyperspectral imagery with VNIR/SWIR measurements.
- Satellite scenes, field boundaries, GPS coordinates, and GeoTIFF georeferencing have not yet been confirmed.
- GIS features should initially use sample arrays or clearly labelled mock coordinates.
- Real farm maps, acreage calculations, and georeferenced risk maps must not be claimed as functional until supported by the dataset.
- Mock heatmaps are only UI demonstrations and do not establish disease detection or model accuracy.
- The three-week early-warning claim requires suitable time-based data and validation before it can be presented as proven.

### 🔄 Integration Workflow
The planned integration flow is:

`Input → API → Model → Prediction Response → React Dashboard`

- Coordinate with Sanjana to finalize model input and output specifications.
- Share the proposed API request and response examples before finalizing the endpoint.
- Agree on field names and data types.
- Replace mock data with actual model outputs after model integration.
- Test the complete end-to-end workflow.

### 📌 Current Status
Backend API preparation, frontend dashboard development, mock prediction testing, and tiling validation are the planned development activities for this stage. Final model integration depends on confirmation of the actual model specifications.

### 🚀 Next Steps
- Finalize API schemas with the model specifications.
- Connect the actual hyperspectral prediction model.
- Replace mock prediction responses with real model outputs.
- Integrate the backend API with the React dashboard.
- Perform end-to-end testing and validate prediction results.


## Day 5 — GIS Integration Planning and Dashboard Development

### Objective
To prepare the TerraSpectra-AI application for future GIS integration by developing an API and dashboard that can support hyperspectral sample data, mock coordinates, and visualization components without assuming that geospatial data is already available.

### Work Completed

**1. Dataset Assessment**
- Reviewed the available controlled wheat-leaf hyperspectral sample.
- Identified that the current sample contains VNIR/SWIR spectral measurements.
- Recognized that satellite imagery, field boundaries, GPS coordinates, and GeoTIFF georeferencing have not yet been confirmed.
- Identified the need to keep hyperspectral data processing separate from future GIS integration.

**2. API Development Planning**
- Prepared the API architecture to support sample arrays and future geospatial inputs.
- Planned structured request and response formats for data exchange between the backend and frontend.
- Prepared the integration approach for disease prediction results and visualization data.
- Kept mock responses separate from actual model predictions.

**3. Dashboard and GIS Visualization Planning**
- Planned dashboard components for displaying hyperspectral analysis results.
- Prepared the approach for visualizing sample coordinates.
- Considered mock heatmaps for demonstrating the future GIS interface.
- Designed the integration approach for future farm-level risk visualization.

**4. Data Integrity and Validation**
- Ensured that mock coordinates are clearly identified as demonstration data.
- Avoided presenting mock heatmaps as actual disease detection results.
- Identified the need for suitable geospatial datasets before implementing real farm mapping and acreage calculations.
- Recognized that disease prediction accuracy requires independent model validation.

### Important Project Limitations
- The current sample is a controlled wheat-leaf hyperspectral image, not a confirmed satellite dataset.
- Real farm boundaries and acreage calculations are not yet supported by verified geospatial data.
- Mock heatmaps are UI demonstrations and do not demonstrate actual disease detection.
- The three-week early-warning objective remains a project goal and has not been scientifically validated.

### Next Steps
- Complete backend API integration.
- Connect the React dashboard with the backend.
- Test API responses using sample arrays and clearly labelled mock coordinates.
- Integrate verified GPS, satellite, or GeoTIFF data when available.
- Develop and validate geospatial disease-risk visualization using appropriate datasets.
- Evaluate early-warning performance using suitable time-based observations.

### Current Status
GIS integration planning and dashboard preparation are in progress. The application is being designed to support future geospatial capabilities while maintaining a clear distinction between demonstration features and validated model outputs.


## 📅 Day 6 — Integration Preparation

### Objective
Prepare the frontend and backend components for machine learning model integration by using temporary sample data, defining API input/output formats, organizing the project code, and maintaining the development work in GitHub.

### Tasks Completed

**1. Temporary Sample Data Integration**
- Used temporary sample data to test the application while the actual machine learning model is under development.
- Prepared sample input values and mock prediction responses for testing.
- Ensured that temporary data is clearly identified as mock data and not actual model predictions.
- Designed the application to support future integration with the trained machine learning model.

**2. API Input and Output Coordination**
- Reviewed the API requirements for communication between the frontend and backend.
- Planned the request and response formats required for machine learning predictions.
- Identified the input parameters required by the prediction API.
- Discussed the expected response structure to ensure compatibility between frontend and backend components.
- Kept the API format flexible until the final model input and output specifications are confirmed.

**3. Code Organization**
- Organized the project files and folders for better maintainability.
- Separated frontend components, backend API logic, sample data, and supporting files.
- Maintained a modular development structure to simplify future modifications.
- Prepared the existing codebase for machine learning model integration.

**4. GitHub Repository Management**
- Reviewed the completed development work.
- Prepared the updated project files for version control.
- Used Git to track project changes and maintain the development history.
- Prepared the completed work for pushing to the GitHub repository.

### Technical Implementation

| Component | Description |
|---|---|
| Sample Data | Temporary mock input and prediction values |
| API Integration | Planned request and response structures |
| Frontend | Prepared for API response integration |
| Backend | Organized API logic for future model connection |
| Code Structure | Modular and maintainable project organization |
| GitHub | Version control and project updates |

### Current Status
- Temporary sample data is available for integration testing.
- API input and output formats are under coordination.
- Project code is organized for future integration.
- The application structure is prepared for connecting the actual machine learning model.

### Next Steps
- Confirm the final API input and output formats with the machine learning team.
- Integrate the trained machine learning model when it becomes available.
- Replace temporary mock responses with actual model predictions.
- Test frontend and backend communication.
- Validate prediction responses and handle API errors.
- Push the remaining completed changes to GitHub.

### Conclusion
Day 6 focused on preparing the project for machine learning integration. Temporary sample data and planned API structures help frontend and backend development continue without waiting for the final model. The organized codebase will make future integration, testing, and maintenance easier.