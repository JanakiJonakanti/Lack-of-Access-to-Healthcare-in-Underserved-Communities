Lack of Access to Healthcare in Underserved Communities – Data Analysis & Visualization

Overview

This project simulates healthcare-related data across 20 regions to identify and visualize disparities in healthcare access in underserved communities. Through data analysis and visual storytelling, we uncover correlations between critical factors like population density, healthcare quality, staff distribution, and budget allocation.

Objectives

Simulate realistic healthcare access data for multiple regions.

Analyze key metrics such as people per facility, staff availability, and healthcare quality.

Visualize correlations and trends using Python and data science libraries.

Highlight regions that require urgent attention or better resource allocation.


Features

Correlation Matrix: Understand relationships between population, budget, staffing, and healthcare quality.

Bar Charts & Scatter Plots: Visualize disparities and patterns across regions.

Enhanced Metrics: Calculate and display derived values like:

People per healthcare facility

Staff per 1,000 population

Budget per capita



Tech Stack

Python 3.x

Libraries Used:

numpy

pandas

matplotlib

seaborn

scipy.stats



How to Run

1. Clone the repository or download the .py file:

git clone https://github.com/yourusername/healthcare-access-analysis.git
cd healthcare-access-analysis


2. Install the required libraries:

pip install numpy pandas matplotlib seaborn scipy


3. Run the Python script:

python healthcare_analysis.py


4. View the console output and explore the generated visualizations.



Visualizations Included

People per Facility by Region – Identifies areas with the most overloaded healthcare centers.

Staff per 1000 vs Healthcare Quality – Highlights staffing impact on quality.

Distance to Clinic vs Budget per Capita – Reveals budget distribution efficiency.

Population vs Budget Allocation – Linear regression to track proportional budgeting.


Sample Output (Snippet)

📊 Correlation Matrix:
                             Population  Facilities  ...  Budget Allocation (USD)  Budget per Capita (USD)
Population                     1.000000    0.313107  ...                  0.523471                -0.065703
Facilities                     0.313107    1.000000  ...                  0.120375                 0.068239
...

Future Enhancements

Integrate real-world data (e.g., from WHO or government databases).

Deploy as a dashboard using Streamlit or Dash.

Include geographic visualizations with Folium or Plotly.


License

This project is licensed under the MIT License.
