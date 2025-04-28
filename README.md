# Airbnb NYC Investment Analysis

This repository contains a data science analysis of Airbnb listings in New York City for investment optimization purposes. The analysis uses machine learning techniques to identify optimal pricing strategies, high-demand neighborhoods, and the most profitable room types.

## Repository Structure

- **Untitled.ipynb**: Original notebook containing the Airbnb NYC analysis with machine learning models
- **Fair_notebook.ipynb**: Enhanced notebook prepared for FAIR data science implementation that integrates with DBRepo and TUWRD repositories
- **README.md**: This file explaining the repository and project

## FAIR Implementation Status

This project is currently being adapted to follow FAIR (Findable, Accessible, Interoperable, Reusable) data science principles. The implementation includes:

1. **Prepared for DBRepo Integration**: The Fair_notebook.ipynb is structured to load data from DBRepo with fallback to local loading due to current connection issues with the DBRepo system.

2. **Persistent Identifiers**: Placeholder PIDs have been included in the notebook, to be replaced with actual identifiers once DBRepo connection is established.

3. **Machine Learning Models**: 
   - K-Means Clustering (n=2) for listing segmentation
   - Random Forest Regression for price prediction
   - Complete with FAIR4ML metadata schema implementation

4. **Metadata and Documentation**: Full documentation of data provenance, model parameters, and evaluation metrics following FAIR principles.

## Technical Challenges

Currently, there are technical connection issues with the DBRepo system that prevent full FAIR implementation. The error "Failed to contact database: Failed to establish connection to database" occurs when attempting to connect. These challenges have been documented in the Data Management Plan, and the notebook has been structured with fallback mechanisms to ensure functionality while maintaining FAIR compliance where possible.

## Usage

To use this notebook:

1. Ensure you have access to the Airbnb NYC dataset (airbnb_data_processed_oversampled.csv)
2. Run the Fair_notebook.ipynb in Jupyter Lab/Notebook
3. The notebook will attempt to connect to DBRepo but will fall back to local data loading if connection fails

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Data Management Plan

A comprehensive Data Management Plan following EC Horizon Europe template has been created for this project and uploaded to Zenodo under the title "DMP: Analyzing Airbnb Listings in New York City for Investment Opportunities".

## Future Work

- Complete integration with DBRepo when connection issues are resolved
- Save trained models to TUWRD with complete metadata
- Implement additional models and analysis techniques
