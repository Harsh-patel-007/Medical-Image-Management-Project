# Medical Image Management System

A Python-based system designed to extract critical metadata from medical DICOM images and store it in a structured SQLite database. This allows for efficient querying and management of a large collection of medical imaging data.

---

##  Key Features

* **DICOM Parsing:** Automatically reads and extracts metadata (like Patient ID, Study Date, Modality, etc.) from `.dcm` files.
* **Database Storage:** Stores the extracted metadata in a lightweight and portable SQLite database (`medical_images.db`).
* **Data Querying:** Includes a Jupyter Notebook (`python sql project.ipynb`) to demonstrate how to connect to the database and run SQL queries.
* **Scalability:** Provides a basic framework for managing a large number of medical images programmatically.

---

##  Technologies Used

* **Language:** Python 3
* **Database:** SQLite 3
* **Core Libraries:**
    * `pydicom` - For reading and parsing DICOM files.
    * `sqlite3` - For interacting with the SQLite database.
    * `pandas` - For data handling and display (optional, but recommended).
    * `Jupyter Notebook` - For interactive development and demonstration.

---

##  Getting Started

Follow these instructions to set up the project on your local machine.

### Prerequisites

* Python 3.8 or higher
* Git 


