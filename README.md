
# Pharmacy Interaction Management System

## Overview
This project implements a **Pharmacy Interaction Management System** to facilitate better decision-making in prescribing medications. It is designed to analyze and display information about various medications, their effects, and potential interactions with diseases. The system aims to assist physicians in making optimal drug prescriptions by providing insights into drug-to-drug and drug-to-disease interactions.

## Project Description
Managing drug interactions is crucial for preventing adverse effects. This system addresses this need by:
- Managing datasets containing drug and disease information.
- Identifying and displaying harmful and beneficial interactions.
- Providing a user-friendly interface for querying and evaluating drug effects.

### Data Structure
The project operates on four key datasets:
1. **Drug Information Dataset**: Contains names of drugs and their associated details.
2. **Drug Pricing Dataset**: Includes drug names and corresponding prices.
3. **Interaction Effects Dataset**: Lists interactions between drugs and their respective effects (positive, negative, or neutral).
4. **Drug Sensitivity Dataset**: Highlights drug effects (positive or negative) on diseases, specifying sensitivities.

### Features
The system provides the following functionalities:
1. CRUD operations on:
   - Drug-to-drug interactions.
   - Drug-to-disease interactions.
2. Cascade delete functionality to remove dependent records upon deletion.
3. Advanced search options to find:
   - Drugs interacting positively or negatively with a specific disease.
   - Drugs beneficial or harmful in general or for specific diseases.
4. Randomized addition of sample data for testing purposes.
5. Evaluation of effects based on random inputs with automated adjustment of interaction effects.
6. Simulation of price changes due to inflation for drugs and their aggregated impacts on prescription costs.

### Implementation
Key components of the implementation include:
- **Optimized Data Structures**: Ensuring low memory usage while enabling fast queries.
- **Validation**: Input data is verified to prevent errors or inconsistencies.
- **Console-based User Interface**: Providing an interactive experience for entering and retrieving information.
- **Error Handling**: Detecting incorrect inputs and providing warnings or error messages.

### Example Input Structure
Below is an example of the data structure:
- Drug Information: `<drug_name>: <drug_price>`
- Disease Name: `<disease_name>`
- Drug Interactions: `<drug_name>: (<drug_name1>, <effect1>); (<drug_name2>, <effect2>)`
- Disease Sensitivities: `<disease_name>: (<drug_name1>, +); (<drug_name2>, -); (<drug_name3>, +)`

### Evaluation Metrics
The system will be evaluated based on:
- Efficiency of data storage and retrieval.
- Design of data structures and their appropriateness.
- Execution time of various queries.
- Memory usage efficiency.
- User interface design.

### Additional Features
- **Graphical User Interface**: A GUI enhancement can improve user interaction and will be rewarded with additional points.
- **Operation Logging**: An option to display all operations performed during the session for review and debugging.

---

## Installation
To set up the project:
1. Clone this repository:  
   ```bash
   git clone <repository-url>
   ```
2. Install dependencies.
3. Run the program through the command line or the GUI interface.

## Usage
1. Load datasets from specified files.
2. Perform CRUD operations or analyze interactions using the provided functions.
3. Evaluate drug effects or adjust prices based on user input.

---

### License
This project is licensed under [MIT License](LICENSE).

---
