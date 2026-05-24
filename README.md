# Data Assets Explorer

Python-based telemetry data transformation project developed during the Deloitte Australia Technology Virtual Experience Program by Forage.

---

## Project Overview

This project converts two different telemetry JSON formats into one unified data structure for industrial monitoring systems.

The solution standardizes machine telemetry data from multiple sources and ensures compatibility with dashboard applications and monitoring tools.

---

## Features

- Convert multiple telemetry formats into one standard structure
- Parse and transform JSON data
- Convert ISO 8601 timestamps into Unix milliseconds
- Structured location mapping
- Automated unit testing
- Clean and efficient Python implementation

---

## Technologies Used

- Python 3
- JSON
- unittest
- datetime

---

## Project Structure

```bash
project/
│
├── data-1.json
├── data-2.json
├── data-result.json
└── main.py
```

---

## Functionality

### Format 1 Conversion
- Reads flat location strings
- Extracts telemetry data
- Converts data into unified structure

### Format 2 Conversion
- Handles nested device objects
- Converts ISO timestamps to Unix milliseconds
- Maps structured location fields

Both input formats generate the same standardized output format.

---

## Running the Project

### Clone the Repository

```bash
git clone https://github.com/abhijeetbarai/Data-Assets-Explorer.git
```

### Run the Program

```bash
python main.py
```

---

## Test Results

```bash
Ran 3 tests in 0.014s

OK
```

All unit tests pass successfully.

---

## Skills Demonstrated

- Python Programming
- Data Transformation
- JSON Processing
- Problem Solving
- Software Development
- Unit Testing

---

## Certification

Deloitte Australia Technology Virtual Experience Program – Forage

Certificate URL:  
https://www.theforage.com/completion-certificates/9PBTqmSxAf6zZTseP/udmxiyHeqYQLkTPvf_9PBTqmSxAf6zZTseP_691f1670dab7055453c704bb_1779306968290_completion_certificate.pdf

---

## Author

Abhijeet Barai

GitHub:  
https://github.com/abhijeetbarai
