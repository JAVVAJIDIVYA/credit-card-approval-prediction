# Solution Requirements

**Team ID**: SWTID-2026-6771  
**Project Name**: Credit card Approval Prediction

---

## 1. Functional Requirements

| S.No | Requirement Category | Requirement Description                                                                 | Priority |
|------|---------------------|-----------------------------------------------------------------------------------------|----------|
| 1    | User Input          | Allow users to enter applicant details through a web form.                              | High     |
| 2    | Input Validation    | Validate all mandatory fields and data formats before submission.                        | High     |
| 3    | Data Processing     | Convert user input into the format required by the ML model.                            | High     |
| 4    | Prediction          | Predict whether the credit card application is Approved or Rejected using the Random Forest model. | High |
| 5    | Result Display      | Display the prediction result to the user in a user-friendly format.                    | High     |
| 6    | Model Loading       | Load the trained machine learning model during application startup.                      | High     |
| 7    | Error Handling      | Display appropriate error messages for invalid inputs or system errors.                 | Medium   |
| 8    | User Interface      | Provide an easy-to-use and responsive web interface.                                     | Medium   |

---

## 2. Non-Functional Requirements

| S.No | NFR Category            | Requirement Description                                                                 | Target Metric / Acceptance Criteria                          |
|------|-------------------------|-----------------------------------------------------------------------------------------|----------------------------------------------------------------|
| 1    | Performance & Speed     | The system should generate credit card approval predictions quickly after the user submits the application. | Prediction result displayed within 2–3 seconds.               |
| 2    | Scalability             | The system should support multiple users accessing the application simultaneously without significant performance degradation. | Supports 100+ concurrent users with stable performance.       |
| 3    | Security & Data Privacy | The system should protect applicant information and validate all user inputs to prevent unauthorized access or invalid data. | HTTPS deployment, server-side input validation, and secure storage of the ML model. |
| 4    | Reliability & Availability | The application should provide consistent predictions and remain available during normal operation. | 99% uptime with consistent prediction results for identical inputs. |
| 5    | Usability & Accessibility | The application should have a simple, responsive, and easy-to-use interface for all users. | User can complete an application in under 5 minutes; compatible with desktop and mobile browsers. |
| 6    | Maintainability & Portability | The system should allow easy model updates and deployment on different platforms without major code changes. | Model can be replaced by updating the .pkl file; deployable on Render, Railway, or any Flask-supported cloud platform. |
