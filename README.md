# Prediction of Failure Using LSTM

This project uses an LSTM (Long Short-Term Memory) neural network to predict hard drive failures based on historical data.

## Project Structure
│── data/
│   ├── raw/            # Unprocessed data
│── notebooks/          # Jupyter notebooks
│── requirements.txt    # Dependencies
│── README.md           # Documentation
│── .gitignore          # Ignore unnecessary files
│── .gitattributes      # For GitHub LFS (large files)

## Installation
Clone the repository and install dependencies:
```bash
git clone https://github.com/dannielabutu/Prediction-of-Failure-Using-LSTM.git
cd Prediction-of-Failure-Using-LSTM
pip install -r requirements.txt

## GitHub Large File Storage (LFS)

Since this project includes large data files, you need to set up Git LFS:

git lfs install
git lfs track "data/raw/*"
git lfs track "data/processed/*"
git add .gitattributes
git commit -m "Enable Git LFS"

# Notebooks

	•	Creating_data.ipynb: Merges and consolidates raw data into a single CSV file.
	•	Data_Cleaning_preprocessing.ipynb: Cleans and processes the dataset for modeling.
	•	LSTM_model.ipynb: Implements and trains an LSTM-based failure prediction model.

# Usage

Run the Jupyter notebooks step by step or convert them to scripts in the src/ directory.

Contributing

Feel free to submit pull requests or report issues.

# License

MIT License
