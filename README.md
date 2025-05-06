
Context-Aware Personalized News Recommender using Contextual Multi-Armed Bandits

Project Overview
This project implements a personalized news recommendation system using Contextual Multi-Armed Bandits (CMAB), specifically the LinUCB algorithm. It dynamically recommends news articles to users based on their context (time of day, device type) and feedback (click or no click).

Features
- Simulates a user interaction environment with contextual data
- Uses LinUCB for real-time learning and recommendation
- Evaluates performance through reward tracking and decision history

Files Included
- `interactions.csv`: Dataset of user-article interactions with context and rewards
- `linucb_model.py`: Python class implementation of the LinUCB algorithm
- `main_simulation.py`: Script to simulate recommendations and record outcomes
- `recommendation_history.csv`: Output file with step-by-step recommendation results

How to Run

Step 1: Setup Python Environment
Ensure Python 3.x is installed. Then install required packages:
```bash
pip install pandas numpy
```

Step 2: Generate Dataset
This step is already done; the file `interactions.csv` is included.

Step 3: Run the Recommender
Run the simulation script:
```bash
python main_simulation.py
```

Step 4: Review Output
Check the file `recommendation_history.csv` for the system's performance log.

Evaluation Metrics
- Click-through Rate (CTR)
- Reward Accumulation
- Correct Recommendations

Future Enhancements
- Integrate real-world datasets like Microsoft MIND
- Add a web interface or interactive dashboard
- Test alternative algorithms like Thompson Sampling or Epsilon-Greedy

