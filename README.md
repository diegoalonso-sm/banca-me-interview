---
# Interview Assessment Banca.me

## Description

This repository contains the code and resources for the technical assessment used for applying to an intership in [banca.me](https://www.banca.me/). The purpose of this project is to demonstrate skills in data analysis, software development, and problem-solving through a practical exercise.

## Repository Contents

- **/src**: Contains the source code for the exercises and problems.
- **/data**: Directory containing the datasets used for the assessments.
- **/docs**: Detailed documentation for each exercise, including requirements, instructions, and solutions.
- **/tests**: Automated tests to validate the implemented solutions.
- **/notebooks**: Jupyter Notebooks with exploratory analysis and interactive solutions.

## Requirements

- **Python 3.12+**
- **Docker** (optional, for a reproducible development environment)
- **Python Libraries:**
  - pandas
  - numpy
  - matplotlib
  - scikit-learn

## Installation

1. Clone the repository:

   ```sh
   git clone https://github.com/diegoalonso-sm/interview-assessment.git
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

3. Within the container, you can run the notebooks.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---
