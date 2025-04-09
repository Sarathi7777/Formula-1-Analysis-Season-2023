# Formula 1 Data Analysis Project

![Formula 1 Logo](formula1projectlogo.jfif)

A comprehensive data analysis and visualization project for Formula 1 racing data, built with Python and Streamlit.

## 🏎️ Features

- Race Analysis and Statistics
- Driver Performance Analysis
- Constructor (Team) Analysis
- Historical Data Visualization
- Track Information
- Predictive Analytics
- Interactive Dashboards

## 📋 Prerequisites

- Python 3.8 or higher
- pip (Python package installer)

## 🚀 Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/formula1-analysis.git
cd formula1-analysis
```

2. Create a virtual environment (recommended):
```bash
python -m venv env
```

3. Activate the virtual environment:
- Windows:
```bash
.\env\Scripts\activate
```
- macOS/Linux:
```bash
source env/bin/activate
```

4. Install required packages:
```bash
pip install -r requirements.txt
```

## 💻 Usage

Run the Streamlit application:
```bash
streamlit run main.py
```

The application will open in your default web browser at `http://localhost:8501`

## 📊 Project Structure

- `main.py` - Main application entry point
- `analysis.py` - Core analysis functions
- `prediction.py` - Predictive analytics
- `visualization.py` - Data visualization components
- `constructor_analysis.py` - Team analysis
- `drivers_analysis.py` - Driver statistics
- `TrackInfo.py` - Track information
- `Historical.py` - Historical data analysis
- `yearanalysis.py` - Year-wise analysis
- `requirements.txt` - Project dependencies

## 📈 Data Sources

The project uses various CSV files containing Formula 1 data:
- Race results
- Driver standings
- Constructor standings
- Lap times
- Pit stops
- Qualifying results

## 🛠️ Dependencies

- streamlit==1.33.0
- pandas==1.4.2
- numpy==1.26.4
- matplotlib==3.5.1
- plotly==5.21.0
- scikit-learn==1.4.1.post1
- Pillow
- click==8.1.3

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🙏 Acknowledgments

- Formula 1 for the data
- Streamlit for the web framework
- All contributors and maintainers

## 📧 Contact

For any queries or suggestions, please open an issue in the repository.
