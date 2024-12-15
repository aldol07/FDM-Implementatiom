# FDM-Implementatiom
Implementation of Fourier Decomposition Method
# Fourier Decomposition Method (FDM) for EEG Analysis

## Overview
This project demonstrates the Fourier Decomposition Method (FDM) for analyzing EEG signals. The method decomposes signals into frequency sub-bands, such as Delta, Theta, Alpha, and Beta, which are useful for understanding brain activity.

## Project Structure
```
FDM-EEG-Analysis/
|-- data/
|   |-- synthetic_eeg_dataset.csv  # EEG dataset
|-- src/
|   |-- fdm.py                     # FDM implementation
|   |-- main.py                    # Main script for processing
|-- outputs/
|   |-- eeg_subbands.csv           # Output sub-band data
|-- README.md                      # Project documentation
```

## How to Use
1. Open the `fdm implementation.ipynb` file and adjust the file paths or parameters if needed.
2. Run the main script in Jupyter Notebook or your Python environment to process the EEG data.
3. Decomposed EEG sub-bands will be saved in the `outputs/` folder as `eeg_subbands.csv`.

## Dataset
- The dataset is stored in the `data/` folder as `synthetic_eeg_dataset.csv`.
- Columns 0-2499: EEG signal values.
- Column 2500: Class labels.

## Output
- The script generates a CSV file containing decomposed sub-band data for further analysis.

## Requirements
- Jupyter Notebook or Python environment
- Libraries: `numpy`, `scipy`, `pandas`, `matplotlib`

## License
This project is licensed under the MIT License.
