# SafeLock

SafeLock is a security system that detects strangers based on user key hold time patterns. It uses **One-Class SVM** and **Isolation Forest** for anomaly detection. The backend is implemented in **Python**, while the frontend is powered by **Flask**.

## 🚀 Features
- Collects user key hold time data.
- Detects anomalies in user behavior using **One-Class SVM** and **Isolation Forest**.
- Provides a web interface using **Flask**.
- Generates visualizations using **Matplotlib** and **Seaborn**.
- Displays results in a user-friendly format.

## 🛠️ Installation

1. **Clone the repository**
   ```sh
   git clone https://github.com/lsroshini/SafeLock.git
   cd SafeLock
   ```

2. **Create a virtual environment** (Optional but recommended)
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**
   ```sh
   pip install -r requirements.txt
   ```

4. **Run the application**
   ```sh
   python app.py
   ```

5. Open a browser and go to `http://127.0.0.1:5000/` to use SafeLock.

## 📂 Project Structure
```
SafeLock/
│── templates/                # HTML templates
│── app.py                    # Flask application
│── requirements.txt          # Required dependencies
│── README.md                 # Documentation
|── rogue_agent_key_hold.csv  # Dataset
```

## 📜 Dependencies
- Flask
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn