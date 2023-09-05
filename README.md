# File Format Converter

## Objective

The objective of this project is to develop solutions to efficiently convert CSV files obtained from a MySQL database into JSON files. JSON is a more suitable format for downstream applications, making it essential to convert these CSV files into JSON files.

## Data Model Details

![Data Model](data_model.png](https://github.com/KokYenZein/File-Format-Converter/blob/main/images/data%20model%20details.png)

The data model represents the structure of the CSV files obtained from the MySQL database. The goal is to convert this structured data into JSON format.

## Design

![Design](design.png)

The design of the File Format Converter project outlines the architecture and flow of data during the conversion process. It defines how the CSV data will be processed and transformed into JSON format.

## Setup Instructions

### Prerequisites

Before setting up and running the project, ensure you have the following prerequisites in place:

- Python installed on your system.
- [Virtual environment](https://docs.python.org/3/tutorial/venv.html) for managing dependencies.
- Project dependencies listed in the `requirements.txt` file.

### Project Setup

1. Create a virtual environment (venv) to isolate project dependencies.

2. Activate the virtual environment.

3. Install project dependencies from the `requirements.txt` file.

4. Deploy the application with the core logic by following the design guidelines provided.

5. Set any required environment variables, such as database connection details or file paths. Use a `.env` file to store these variables securely.

6. Run the project by executing the main script or application entry point.

7. Implement appropriate exception handling to ensure the reliability and robustness of the conversion process. Handle exceptions gracefully and provide meaningful error messages when necessary.

## Usage

Once the project is set up and running, you can use it to convert CSV files from the MySQL database into JSON files. Ensure that you provide the necessary input parameters or configurations as required by the application.

