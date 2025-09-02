# LK Hospital Management System

This is a web-based hospital management system built with Flask. It allows patients to register, book appointments, and view their medical history. Admins can manage patients, doctors, appointments, and patient admissions.

## Features

*   **Patient Management:** Patients can register, login, and manage their appointments.
*   **Doctor Management:** Admins can add, edit, and delete doctors.
*   **Appointment Booking:** Patients can book appointments with doctors based on their availability.
*   **Admin Dashboard:** A comprehensive dashboard for admins to manage the entire system.
*   **Patient Admission:** Admins can admit and discharge patients.

## Getting Started

### Prerequisites

*   Python 3.x
*   PostgreSQL

### Installation

1.  **Clone the repository:**

    ```bash
    git clone <repository-url>
    cd <repository-folder>
    ```

2.  **Create a virtual environment and activate it:**

    ```bash
    python -m venv venv
    source venv/bin/activate
    ```

3.  **Install the dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

4.  **Set up the database:**

    *   Create a PostgreSQL database.
    *   Create a `.env` file in the root directory by copying `.env.example`.
    *   Update the `DATABASE_URL` in the `.env` file with your PostgreSQL connection string.

## Usage

To run the application in development mode, use the following command:

```bash
python app.py
```

The application will be available at `http://localhost:5001`.

## Deployment

This application is ready to be deployed to Vercel.

1.  **Push your code to a Git repository (e.g., GitHub).**

2.  **Import your project on Vercel.**

3.  **Configure the environment variables on Vercel:**

    *   `SECRET_KEY`: A secret key for the Flask application.
    *   `DATABASE_URL`: The connection string for your PostgreSQL database.

4.  **Deploy!**

Vercel will automatically detect the `vercel.json` file and deploy the application.