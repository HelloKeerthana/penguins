
## User Inputs
- **Island**: Select from Biscoe, Dream, or Torgersen.
- **Sex**: Choose between male or female.
- **Bill Length (mm)**: Set using the slider (32.1 to 59.6).
- **Bill Depth (mm)**: Set using the slider (13.1 to 21.5).
- **Flipper Length (mm)**: Set using the slider (172.0 to 231.0).
- **Body Mass (g)**: Set using the slider (2700.0 to 6300.0).

## Dataset
The app uses data from the [Palmer Penguins dataset](https://github.com/allisonhorst/palmerpenguins).

## Model
The Random Forest Classifier (`penguins_rfc.pkl`) was pre-trained on the penguins dataset.

## Files
- `app.py`: Main application file.
- `penguins_cleaned.csv`: Preprocessed dataset for model input.
- `penguins_rfc.pkl`: Trained Random Forest model.
- `requirements.txt`: List of required packages.

## Example Usage
When the app is running, either:
1. Provide input parameters through the sidebar, or
2. Upload a CSV file with penguin features for predictions.

## Acknowledgments
Special thanks to [Allison Horst](https://github.com/allisonhorst) for the Palmer Penguins dataset.
