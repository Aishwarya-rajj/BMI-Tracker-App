
# BMI Tracker App

## Project Overview
The BMI Tracker is a simple Python-based application designed to calculate the Body Mass Index (BMI) for users. The app categorizes the BMI result into one of four categories (Underweight, Normal weight, Overweight, Obesity) and visualizes the result using a bar chart. Built using **Tkinter** for the graphical user interface (GUI) and **Matplotlib** for data visualization, this project offers a user-friendly interface for calculating BMI.

## Objective
- Build a BMI calculator app to allow users to input their weight and height.
- Classify the BMI result into one of four categories: Underweight, Normal weight, Overweight, Obesity.
- Provide a graphical representation of the BMI and its category using a bar chart.
- Implement basic error handling to ensure that the input is valid.

## Technologies and Libraries
- **Programming Language**: Python
- **Libraries**:
  - Tkinter – GUI framework for building the application interface
  - Matplotlib – Visualization for displaying BMI and its categories
  - Messagebox (from Tkinter) – To show error messages in case of invalid input

## Implementation
### Key Steps:
1. **GUI Setup**:
   - A graphical interface is created using Tkinter where users can input their height and weight.
   - Two input fields are provided to enter height (in centimeters) and weight (in kilograms).

2. **BMI Calculation**:
   - The app calculates the BMI using the formula: `BMI = weight / (height in meters)^2`.
   - The BMI result is then categorized into one of four categories: Underweight, Normal weight, Overweight, Obesity.

3. **Error Handling**:
   - The app includes error handling to ensure that users input valid numerical values for both height and weight. If invalid inputs are provided, an error message is displayed.

4. **Visualization (Bar Chart)**:
   - After calculating the BMI, the app generates a bar chart visualizing the BMI value.
   - The chart displays thresholds for Underweight, Normal weight, Overweight, and Obesity using horizontal lines to indicate the respective ranges.

5. **Displaying Results**:
   - A new window is opened to display the BMI result and the corresponding category along with the bar chart.

## Results
- **BMI Calculation** – The app correctly calculates the BMI based on user input.
- **Categorization** – The BMI result is accurately classified into one of the categories: Underweight, Normal weight, Overweight, Obesity.
- **Visualization** – A bar chart is displayed to visualize the BMI and its classification.

## Project Structure
```
|-- bmi_tracker
    |-- bmi_tracker.py
    |-- README.md
    |-- requirements.txt
```

## How to Run the Project
1. Clone the repository:
   ```
   git clone https://github.com/username/bmi_tracker.git
   ```
2. Install dependencies:
   ```
   pip install -r requirements.txt
   ```
3. Run the Python script:
   ```
   python bmi_tracker.py
   ```

## Future Enhancements
- Add the option to save the BMI history for users.
- Allow users to input their age and gender for more personalized BMI calculations.
- Implement a more advanced visualization dashboard with trends and progress over time.
- Deploy the app as a web application using Flask or FastAPI.

## Conclusion
This BMI Tracker app provides a simple and efficient way for users to calculate and visualize their BMI. With a clean user interface and real-time graphical representation, the app offers an intuitive tool for individuals to monitor their health.
