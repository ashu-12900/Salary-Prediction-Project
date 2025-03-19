# Developer Salary Analysis Dashboard

## Overview
This project is an interactive Streamlit web application that visualizes and analyzes software developer salary data from the Stack Overflow Developer Survey. The dashboard provides insights into how factors such as country, years of professional coding experience, and education level correlate with developer salaries worldwide.

## Features
- **Country Distribution**: Interactive pie chart showing the distribution of survey respondents by country
- **Experience vs. Salary Analysis**: Animated scatter plot visualizing the relationship between years of coding experience and salary, with country-based color coding
- **Education Impact**: Box plots displaying salary distributions across different education levels
- **Clean Data Processing**: Automated data cleaning and preprocessing functions for reliable analysis


## Technologies Used
- **Streamlit**: For creating the interactive web interface
- **Pandas**: For data manipulation and analysis
- **Plotly Express**: For creating interactive and animated data visualizations
- **Matplotlib**: For additional visualization capabilities

## Installation

### Prerequisites
- Python 3.7+
- pip

### Setup
1. Clone this repository:
   ```bash
   git clone [https://github.com/yourusername/developer-salary-analysis.git](https://github.com/ashu-12900/Salary-Prediction-Project)
   cd developer-salary-analysis
   ```

2. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

3. Download the Stack Overflow Developer Survey data:
   - Visit the [Stack Overflow Developer Survey](https://insights.stackoverflow.com/survey) page
   - Download the latest survey results
   - Extract and place the "survey_results_public.csv" file in the project root directory

## Usage
1. Run the Streamlit application:
   ```bash
   streamlit run app.py
   ```

2. Open your web browser and navigate to `http://localhost:8501`

3. Explore the various visualizations to gain insights into developer salary trends

## Data Processing
The application performs several data cleaning operations:
- Filters for full-time employed developers
- Removes outliers in salary data
- Standardizes education level categories
- Converts experience levels to numeric values
- Groups smaller countries into an "Other" category for better visualization


## Future Improvements
- Add machine learning model to predict salaries based on input parameters
- Include more visualization types for deeper analysis
- Add year-over-year comparison for trend analysis
- Implement user authentication for personalized dashboards

## Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments
- Stack Overflow for providing the developer survey data
- The Streamlit team for their excellent documentation and examples
