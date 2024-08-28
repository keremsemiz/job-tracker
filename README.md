# Job Applications API

This is a FastAPI-based API for tracking job applications, including creating applications, listing them, and updating their status.

## Features

- **Create Job Application**: Add a new job application with company name, job title, application date, and status.
- **List Job Applications**: Retrieve a list of all job applications.
- **Update Job Application**: Update the details of an existing job application.

## Installation

### Using Poetry

1. Clone the repository:
    ```bash
    git clone https://github.com/keremsemiz/job-tracker.git
    cd job-applications-api
    ```

2. Install dependencies:
    ```bash
    poetry install
    ```

3. Run the application:
    ```bash
    poetry run uvicorn job_applications_api.main:app --reload
    ```

### Using Pip

1. Clone the repository:
    ```bash
    git clone https://github.com/keremsemiz/job-tracker.git
    cd job-applications-api
    ```

2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Run the application:
    ```bash
    uvicorn job_applications_api.main:app --reload
    ```

## Usage

After starting the application, you can interact with the API at `http://127.0.0.1:8000`.

### Endpoints

- **POST /applications/**: Create a new job application.
- **GET /applications/**: List all job applications.
- **PUT /applications/{application_id}/**: Update an existing job application.

You can also explore the API documentation by visiting `http://127.0.0.1:8000/docs` in your browser.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
