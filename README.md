# Student Data Processing with YAML

## Overview
This project is a simple Python application that reads student data from a YAML file, displays all students, and allows filtering students based on their GPA.

## Features
- Reads student data from a `students.yaml` file.
- Displays all students in the dataset.
- Filters students with a GPA above a user-defined threshold.

## Technologies Used
- Python
- PyYAML (for reading YAML files)

## Installation
### Prerequisites
Ensure you have Python installed. You can check by running:
```sh
python3 --version
```

### Setup Virtual Environment (Recommended)
```sh
python3 -m venv myenv
source myenv/bin/activate  # Activate the virtual environment
```
![image](https://github.com/user-attachments/assets/9b9061dc-876f-4159-97d8-4b800c2a3245)


### Install Dependencies
```sh
pip install -r requirements.txt
```
If `requirements.txt` is not provided, install PyYAML manually:
```sh
pip install pyyaml
```
<img width="633" alt="image" src="https://github.com/user-attachments/assets/c2edcbe4-a2ec-4974-9c71-3c27458806ab" />


## Usage
### 1️⃣ Add Student Data in `students.yaml`
Example:
```yaml
students:
  - name: Alice
    age: 21
    major: Computer Science
    gpa: 3.8
  - name: Bob
    age: 22
    major: Mathematics
    gpa: 3.5
```
<img width="775" alt="image" src="https://github.com/user-attachments/assets/b2b5c94e-43fb-4db2-b76c-f27933aafce6" />


### 2️⃣ Run the Script
```sh
python app.py
```
<img width="653" alt="image" src="https://github.com/user-attachments/assets/c6b6016f-756e-4ae2-b9b6-27d0373bd128" />


### 3️⃣ Enter Minimum GPA for Filtering
The program will ask for a minimum GPA to filter students. Enter a value like `3.5`.

## File Structure
```
📂 Container_Assi
│── 📜 app.py          # Main Python script
│── 📜 students.yaml   # YAML file with student data
│── 📜 requirements.txt # Dependencies
```

## Troubleshooting
- **YAML Parsing Errors:** Ensure correct indentation in `students.yaml`.
- **Module Not Found:** Run `pip install -r requirements.txt`.

## License
This project is for educational purposes only.

---

Happy Coding! 🚀
