# Links to Project Resources

Here are the links to various components of the **Loan Default Prediction Project**:

## Experiment Tracking
- [MLFlow/DagsHub Experiments](https://dagshub.com/Shruti-1205/my-first-repo/experiments)
  - Access detailed experiment logs, metrics, and model versions tracked during the development phase.

## Dockerized Model
- [Docker Hub Container](https://hub.docker.com/repository/docker/shruti1205/loan_default_api/tags)
  - Pull the Docker container hosting the deployed machine learning model using the following command:
    ```bash
    docker pull shruti1205/loan_default_api:v1
    ```

## Deployed Model Digital Ocean
- [Deployed Model](http://138.197.107.85/docs)
  - Use the FastAPI-based backend to make predictions.

## Streamlit App
- [Interactive Streamlit App](https://loan-default-predict.streamlit.app/)
  - Interact with the model through a user-friendly web application.

---

## How to Use These Resources

1. **MLFlow/DagsHub**:
   - Explore the experiments to see how the models were trained and evaluated.
   - View metrics such as F1-score, precision, and recall for different models.

2. **Docker Hub**:
   - Pull the containerized model to deploy locally or on any cloud service.
   - Example usage:
     ```bash
     docker run -d -p 8000:8000 shruti1205/loan_default_api:v1
     ```

3. **Deployed API**:
   - Use the API to send prediction requests programmatically or through Swagger UI.
   - Example `curl` request:
     ```bash
     curl -X POST "http://138.197.107.85/predict" -H "Content-Type: application/json" -d '{"Age": 30, "Income": 50000, "LoanAmount": 20000, "CreditScore": 720, "MonthsEmployed": 24, "NumCreditLines": 4, "InterestRate": 5.5, "LoanTerm": 36, "DTIRatio": 0.35, "Education": "Bachelor\'s", "EmploymentType": "Full-time", "MaritalStatus": "Single", "HasMortgage": "No", "HasDependents": "No", "LoanPurpose": "Auto", "HasCoSigner": "No"}'
     ```

4. **Streamlit App**:
   - Test the interactive app to see real-time loan default predictions.
   - Provide inputs dynamically via sliders and dropdowns.