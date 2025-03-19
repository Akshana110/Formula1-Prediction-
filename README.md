# Predicting the 2025 Australian Grand Prix Winner using FastF1 & Gradient Boosting

## Description
This project predicts the winner of the 2025 Australian Grand Prix using FastF1 API and a Gradient Boosting model. By analyzing past race data and 2025 qualifying times, it estimates race performance and ranks drivers accordingly.

## Installation
Ensure you have Python installed, then install the required dependencies:
```bash
pip install fastf1 pandas numpy scikit-learn
```

## Data Collection
- **FastF1 API** is used to fetch the 2024 Australian GP race data.
- **2025 Qualifying Data** is manually inputted based on assumed lap times.

## Implementation Steps
1. Enable FastF1 cache to store session data.
2. Load the 2024 Australian GP race session and extract lap times.
3. Prepare the 2025 qualifying data with driver names and times.
4. Map driver names to FastF1 codes and merge the 2025 qualifying data with 2024 race lap times.
5. Train a Gradient Boosting Regressor model using qualifying times as features.
6. Predict race performance based on qualifying times.
7. Rank drivers based on predicted race times.
8. Evaluate the model using Mean Absolute Error (MAE).

## Results
- The predicted race times are ranked, providing an estimated winner.
- Model evaluation using MAE ensures accuracy in predictions.

## License
This project is open-source and available under the MIT License.

## Future Improvements
- Use additional features like tire degradation, weather conditions, and pit stop strategies.
- Integrate real-time data streaming from FastF1 API.
- Optimize the ML model with hyperparameter tuning.

## Author
Akshana Prasad
![notebook](https://github.com/user-attachments/assets/2d9dfaeb-e763-4143-b057-d1ba396b167c)
![f1](https://github.com/user-attachments/assets/e6663237-a2e6-421b-abb7-66678a977337)

)

