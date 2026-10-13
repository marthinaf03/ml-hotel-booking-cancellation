# ml-hotel-booking-cancellation
*Predict hotel booking cancellations, understand which customers are most at risk and what hotels could do to reduce them*

Booking cancellations are one of the main sources of revenue loss for hotels: a room cancelled at the last minute is often impossible to resell, and hotels try to protect themselves with restrictive policies (non-refundable rates, deposits) or with overbooking, which in turn can damage customer satisfaction if it goes wrong.

This project analyses about 119,000 real bookings from two hotels in Portugal (a City Hotel and a Resort Hotel) to predict whether a booking will be cancelled and to understand which factors and customer segments are most associated with cancellations. The analysis follows the **CRISP-DM** methodology.

Final assignment – *Machine Learning and Data Mining (Module I)*, University of Bologna, A.Y. 2026/27.
Author: **Martina Fava**

## Main tasks
- Understand the business problem and the cost of a cancellation for the hotel
- Explore and clean the data, removing anomalies and variables that would cause data leakage
- Build and compare classification models to predict cancellations, using metrics suited to an imbalanced target
- Interpret the models to find the main drivers of cancellation
- Turn the results into practical suggestions on deposit policies and overbooking

## 📁 Repository structure
```text
ml-hotel-booking-cancellation/
├── hotel_booking_cancellation.ipynb   # Colab notebook with the full analysis
├── data/                              # dataset and source information
├── assets/                            # plots and figures
├── report/                            # paper (IEEE format) and presentation (PDF)
├── requirements.txt                   # Python libraries used
├── LICENSE
└── README.md
```

## 🗎 Project structure
All the analysis is contained in a single notebook, organised according to the CRISP-DM phases.

```text
hotel_booking_cancellation.ipynb
├── 1. Business Understanding
│   ├── Problem definition
│   └── Cost of errors and choice of metrics
├── 2. Data Understanding
│   ├── Data import and attribute description
│   ├── Target distribution
│   └── Exploratory analysis
├── 3. Data Preparation
│   ├── Duplicates and anomalous rows
│   ├── Missing values
│   ├── Leakage removal
│   ├── Feature engineering
│   └── Encoding and train/test split
├── 4. Modeling
│   └── Training and tuning of classification models
├── 5. Evaluation
│   ├── Model comparison
│   └── Model interpretation
└── 6. Deployment
    └── Business recommendations
```

## How to run
Open the notebook in Google Colab and run all cells (*Runtime → Run all*). The dataset is loaded directly from this repository, so no manual upload is needed.

## 📊 Results
*To be added at the end of the project.*

| Model | Precision | Recall | F1-score | PR-AUC |
|-------|-----------|--------|----------|--------|
|       |           |        |          |        |

## Future work
*To be added at the end of the project.*

## Data source
Antonio, N., Almeida, A., Nunes, L. (2019). *Hotel booking demand datasets*. Data in Brief, 22, 41–49.
Kaggle version: https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand

## License
This project is licensed under the MIT License.
