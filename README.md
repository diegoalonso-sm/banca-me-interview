---
# Interview Assessment

## Description

This repository contains the code and resources for the technical assessment used in job interviews. The purpose of this project is to demonstrate skills in data analysis, software development, and problem-solving through practical exercises and examples.

## Repository Contents

- **/src**: Contains the source code for the exercises and problems.
- **/data**: Directory containing the datasets used for the assessments.
- **/docs**: Detailed documentation for each exercise, including requirements, instructions, and solutions.
- **/tests**: Automated tests to validate the implemented solutions.
- **/notebooks**: Jupyter Notebooks with exploratory analysis and interactive solutions.

## Requirements

- **Python 3.8+**
- **Docker** (optional, for a reproducible development environment)
- Python Libraries:
  - pandas
  - numpy
  - matplotlib
  - scikit-learn

## Installation

1. Clone the repository:

   ```sh
   git clone https://github.com/your-username/interview-assessment.git
   cd interview-assessment
   ```

2. Create and activate a virtual environment (optional but recommended):

   ```sh
   python3 -m venv venv
   source venv/bin/activate   # On Windows use `venv\Scripts\activate`
   ```

3. Install the dependencies:

   ```sh
   pip install -r requirements.txt
   ```

## Usage

1. Navigate to the directory of the exercise or problem you want to solve.

2. Read the instructions and requirements in the `README.md` file within that directory.

3. Implement your solution in the corresponding file.

4. Run the tests to validate your solution:

   ```sh
   pytest tests/test_<problem_name>.py
   ```

## Running with Docker

1. Build the Docker image:

   ```sh
   docker build -t interview-assessment .
   ```

2. Run the Docker container:

   ```sh
   docker run -it --rm -v $(pwd):/app interview-assessment
   ```

   This will mount the current directory to `/app` in the container and run it interactively.

3. Within the container, you can run your solutions and tests as described above.

## Contributions

Contributions are welcome. If you wish to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/new-feature`).
3. Make your changes and commit them (`git commit -am 'Add new feature'`).
4. Push your changes to a new branch (`git push origin feature/new-feature`).
5. Create a Pull Request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---
