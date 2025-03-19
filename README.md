## Diet Recommendation System

This project is a Diet Recommendation System designed to help users assess the healthiness of foods based on their nutritional content and specific health conditions. The system uses a GUI built with Tkinter to provide recommendations for various health conditions, including diabetes (Type I and II), high blood pressure, low blood pressure, cholesterol levels, and general healthy eating.
## Features

- Health Condition-Specific Recommendations:

    - Diabetes Type I and II

    - High Blood Pressure

    - Low Blood Pressure

    - Cholesterol Management

    - General Healthy Food Assessment

- Food Analysis:

    - Evaluates the nutritional content of food items based on input data.

    - Determines whether a food is healthy or unhealthy for specific conditions.

- Suggested Foods:

    - Provides alternative food suggestions based on nutritional criteria.


## Tech Stack


**Python**: Core programming language.

**Tkinter**: For building the graphical user interface.

**Pandas**: To process data (CSV files).

**CSV Module**: To read and analyze food data.

**Seaborn & Matplotlib**: For potential data visualization enhancements.


## Installation

1. Clone the repository:

``` 
git clone https://github.com/yourusername/diet-recommendation-system.git

```
2. Install the required Python libraries:

```
pip install pandas numpy matplotlib seaborn

```
3. Ensure you have Tkinter installed (comes pre-installed with most Python distributions).
## Usage/Examples

1. Run the script:

```
python diet_recommendation_system.py

```
2. Enter the name of a food item in the input field.

3. Select one of the health conditions via buttons:

- Diabetes Type I

- Diabetes Type II

- High BP

- Low BP

- Cholesterol

- Healthy Food Check

4. View the analysis in the output fields:

- Nutritional quantities of the food.
- Healthiness assessment.
- Suggested alternative foods.
## File Structure

- `diet_recommendation_system.py`: Main script containing the GUI and logic.

- input.csv: CSV file containing nutritional data for various food items.
## Example Input

The `input.csv` file should contain columns such as:

- Food name

- Nutritional values (e.g., fats, carbohydrates, sugars, sodium, etc.)
## Example Output

When analyzing "Apple" for Diabetes Type I:

```
Apple is healthy for you. Foods high in healthy fats, protein, and fiber can help regulate blood sugar levels.
Suggested Foods:
Banana
Orange
Pear

```
## Future Enhancements

- Add support for additional health conditions.

- Incorporate machine learning models for personalized recommendations.

- Enable dynamic updates to the food database via user input.
## Authors

- [@Tusharroy01](https://www.github.com/Tusharroy01)


## License

MIT License

Copyright (c) 2025 Afroze07

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
