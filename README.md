🚀 Scowtt Revenue Engine: The "Whale" Hunter
A Production-Grade Lead Prioritization System by Praveen

💡 The Core Idea
Most ML models stop at predicting "Will they buy?" But for Scowtt Inc., a "Yes" from a $5 customer is very different from a "Yes" from a $500 customer.

I built an Expected Value Engine that combines Propensity (how likely they are to buy) with Monetary Value (how much they spend). This allows the sales team to stop chasing "noise" and start focusing on the leads that actually move the needle.

📈 The High-Impact Results
Revenue Concentration: The top 10% of leads identified by this model capture 47.1% of all potential revenue.

Efficiency Multiplier: We achieved a 4.7x Lift, making marketing efforts nearly 5 times more effective than random outreach.

Calibration: With a Brier Score of 0.0056, the probabilities generated aren't just guesses—they are mathematically reliable numbers the business can trust.

🛠️ Engineering Standards
Even though this is a single-notebook submission, I’ve maintained strict production standards:

Leakage Prevention: Features are engineered using a "Point-in-Time" snapshot (June 1, 2018), ensuring the model never "sees the future" during training.

Latency-First: The scoring engine runs at 21 microseconds per user, making it fast enough for real-time applications.

Explainability: I used SHAP values to "open the black box," proving that Recency and Purchase Velocity are the strongest indicators of a high-value lead.

📂 How to Navigate this Project
Plaintext

.
├── data/               # Raw Olist CSVs (Store your data here!)

├── notebooks/          # The Brain & The Story (Praveen_Scowtt_Project.ipynb)

├── outputs/            # The Work Product (Final Lead List & Charts)

├── .gitignore          # Keeps the repo clean

└── requirements.txt    # For easy environment setup

🏃 Getting Started

Place the Olist datasets in the /data folder.

Install dependencies: pip install -r requirements.txt.

Open notebooks/Praveen_Scowtt_Project.ipynb and Run All.
