# COVID-19 Simulation with Streamlit

![COVID-19 Simulation](https://img.shields.io/badge/Simulation-Success-brightgreen)

An interactive Python-based simulation for modeling the impact of COVID-19 across multiple regions. This project leverages **Streamlit** for a user-friendly interface and provides data visualizations and insights.

## 🌟 Features

- **Interactive Simulation**: Allows users to select regions, define timelines, and customize sample scales.
- **Dynamic Visualizations**: Graphs and visual representations of the simulation output.
- **Streamlit Integration**: An intuitive web interface for easy interaction.
- **Customizable Parameters**: Start/end dates, sample ratios, and regional selections.

## 📂 Directory Structure

```plaintext
├── a2-countries.csv              # Regional population data
├── a2-covid-simulated-timeseries.csv  # Simulation output
├── a2-covid-summary-timeseries.csv    # Summary statistics
├── assignment2.py               # Core simulation logic
├── helper.py                    # Plotting and utility functions
├── sim_parameters.py           # Simulation parameters
└── streamlit_ui.py            # Web interface
```

## 🔧 Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/covid19-simulation.git
   cd covid19-simulation
   ```

2. Install the required Python packages:
   ```bash
   pip install streamlit pandas matplotlib
   ```

## ▶️ Usage

1. Start the Streamlit application:

   ```bash
   streamlit run streamlit_ui.py
   ```

2. Configure the simulation parameters in the web app:

   - **Sample Ratio**: Adjust the scale for simulation.
   - **Start and End Dates**: Define the timeline.
   - **Regions**: Select regions to simulate.

3. Click the **Run Simulation** button to generate results and visualizations.

## 📊 Output

- **Simulation Data**: Time-series CSVs with detailed COVID-19 statistics.
- **Summary Statistics**: High-level insights into simulated results.
- **Graphs**: Dynamic visualizations showing trends across regions.

## 🛠 Core Components

- **assignment2.py**: Implements the COVID-19 spread simulation using a Markov Chain model.
- **streamlit_ui.py**: Handles the Streamlit web interface for user interaction.
- **helper.py**: Utility functions for data visualization and result processing.

## 📈 Example Visualization

![Example Visualization](example-visualization.png)

## 🤝 Contribution

Contributions are welcome! Please follow the standard fork-and-pull model:

1. Fork the repository.
2. Create a new branch.
3. Commit and push your changes.
4. Submit a pull request.

## 📝 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## 📞 Contact

For any questions or feedback, please contact:

- **Author**: Your Name
- **Email**: your.email@example.com
- **GitHub**: [Your GitHub Profile](https://github.com/your-username)

Enjoy exploring the simulation! 🎉
