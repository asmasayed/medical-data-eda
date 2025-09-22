# Medical Data Visualizer - FreeCodeCamp Project

## Overview
This is a FreeCodeCamp Data Analysis with Python project focused on medical data visualization. The project uses Python with pandas, seaborn, and matplotlib to create categorical plots and heatmaps from medical examination data.

## Project Status
- **Current State**: Template project ready for development
- **Environment**: Fully configured and functional
- **Dependencies**: All required packages installed and compatible

## Recent Changes
- **2025-09-22**: Project imported and set up for Replit environment
  - Installed Python 3.11 with compatible dependencies
  - Fixed numpy/pandas compatibility issues (numpy downgraded to 1.24.3)
  - Configured workflow to run main.py script
  - Verified environment setup is working correctly

## Project Architecture

### Files Structure
- `main.py` - Entry point that runs the visualization functions and tests
- `medical_data_visualizer.py` - Main implementation file (template to be completed)
- `medical_examination.csv` - Medical data dataset
- `test_module.py` - Unit tests for the visualization functions
- `requirements.txt` - Python dependencies
- `examples/` - Reference images showing expected output

### Dependencies
- **pandas==1.5.3** - Data manipulation and analysis
- **seaborn==0.13.2** - Statistical data visualization
- **matplotlib** - Plotting library
- **numpy==1.24.3** - Numerical computing (downgraded for compatibility)

### Workflow Configuration
- **Name**: Medical Data Visualizer
- **Command**: `python main.py`
- **Output**: Console-based execution
- **Current Status**: Template code (expected to fail until implementation is complete)

## Development Notes

### Current Implementation Status
The project contains template code that needs to be completed:
- `medical_data_visualizer.py` has placeholder functions `draw_cat_plot()` and `draw_heat_map()`
- Variables are set to `None` and need proper implementation
- The current error is expected behavior for a template project

### Expected Functionality
When completed, the project should:
1. Load and clean medical examination data
2. Create categorical plots showing value counts for categorical features
3. Generate correlation heatmaps with proper data filtering
4. Pass all unit tests in `test_module.py`
5. Save plots as `catplot.png` and `heatmap.png`

### Data Analysis Goals
- Analyze medical examination data including age, sex, height, weight, blood pressure
- Visualize relationships between lifestyle factors (smoking, alcohol, activity) and cardiovascular disease
- Create statistical visualizations showing patterns in the medical data

## User Preferences
- Project follows FreeCodeCamp structure and requirements
- Uses standard Python data science libraries
- Console-based output for development and testing