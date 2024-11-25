
# Pharmacy Interaction Management System

## Overview
This project is a result of my individual effort to design and implement a **Pharmacy Interaction Management System**. The system facilitates better decision-making in prescribing medications by analyzing and displaying information about various drugs, their effects, and interactions with diseases. It is designed to assist physicians in optimizing drug prescriptions through comprehensive insights into drug-to-drug and drug-to-disease interactions.

## Project Description
Managing drug interactions effectively is a critical aspect of modern healthcare. I addressed this challenge by:
- Developing a robust system to manage datasets containing drug and disease information.
- Building features to identify and display both harmful and beneficial interactions.
- Crafting a user-friendly interface to support effective querying and evaluation of drug effects.

### Data Structure
The project leverages four key datasets:
1. **Drug Information Dataset**: Stores drug names and related details.
2. **Drug Pricing Dataset**: Includes drug names with their respective prices.
3. **Interaction Effects Dataset**: Captures drug-to-drug interactions with effects classified as positive, negative, or neutral.
4. **Drug Sensitivity Dataset**: Highlights drug effects (positive or negative) on diseases while specifying sensitivities.

### Features
I designed and implemented the following functionalities:
1. CRUD operations for:
   - Drug-to-drug interactions.
   - Drug-to-disease interactions.
2. Cascade delete to ensure consistency in dependent records.
3. Advanced search capabilities to identify:
   - Drugs with positive or negative interactions with a specific disease.
   - Drugs that are generally beneficial or harmful for specific diseases.
4. Randomized data generation for testing purposes.
5. Automated adjustments for interaction effects based on random inputs.
6. Simulation of drug price changes due to inflation, with aggregated cost impacts.

### Implementation Highlights
The system incorporates:
- **Optimized Data Structures**: Ensuring minimal memory usage while enabling rapid query execution.
- **Input Validation**: Preventing errors by verifying data integrity during input and storage.
- **Interactive Console Interface**: Providing seamless access to all features.
- **Error and Warning Notifications**: Detecting and displaying user input issues effectively.

### Example Input Structure
Below is an example of the supported input structure:
- Drug Information: `<drug_name>: <drug_price>`
- Disease Name: `<disease_name>`
- Drug Interactions: `<drug_name>: (<drug_name1>, <effect1>); (<drug_name2>, <effect2>)`
- Disease Sensitivities: `<disease_name>: (<drug_name1>, +); (<drug_name2>, -); (<drug_name3>, +)`

### Evaluation Metrics
The project's success is measured against:
- Efficient in-memory storage and retrieval.
- Well-designed and appropriate data structures.
- Fast query execution times.
- Memory usage optimization.
- Usability and design quality of the interface.

### Additional Features
- **Graphical User Interface (Optional)**: An optional enhancement for improved user interaction.
- **Operation Logging**: Ability to display all operations performed during a session for review and debugging.

---

## Installation
To set up the project:
1. Clone this repository:  
   ```bash
   git clone <repository-url>
   ```
2. Install necessary dependencies.
3. Run the program via the command line or GUI.

## Usage
1. Load datasets from pre-configured files.
2. Execute CRUD operations or analyze interactions using the interactive interface.
3. Evaluate drug effects or adjust prices based on user-defined inputs.

---

### License
This project is licensed under [MIT License](LICENSE).

---
