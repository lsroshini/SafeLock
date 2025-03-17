# SafeLock

SafeLock is a security system that detects strangers based on user key hold time patterns. It uses **One-Class SVM** and **Isolation Forest** for anomaly detection. The backend is implemented in **Python**, while the frontend is powered by **Flask**.


- Collects user key hold time data.
- Detects anomalies in user behavior using **One-Class SVM** and **Isolation Forest**.
- Provides a web interface using **Flask**.
- Generates visualizations using **Matplotlib** and **Seaborn**.

## Dependencies
- Flask
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
