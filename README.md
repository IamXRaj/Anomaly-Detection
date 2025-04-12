# 👤 User Behavior Anomaly Detection with Isolation Forest

This project uses the **Isolation Forest** algorithm to detect anomalous user behavior in login sessions. It simulates normal and abnormal user activity based on features like login duration, tab switches, keystroke speed, and idle time.

---

## 📁 Dataset (Simulated)

- 100 normal user sessions generated using statistical distributions
- 5 injected anomalous user records with extreme values
- Key features:
  - `login_duration` (minutes)
  - `tab_switches` (count)
  - `keystroke_speed` (keys/minute)
  - `idle_time` (minutes)

---

## 🧠 ML Model

- **Isolation Forest** (`sklearn.ensemble`)
  - Contamination rate: 5%
  - Automatically detects outliers based on feature isolation

---

## 📊 Visualizations

- **Seaborn Pairplot** to visualize normal vs anomalous behavior across all features
- Anomaly results saved as `user_behavior_anomaly_report.csv`

---

## 🚀 Output

- Anomaly labels (`Normal`, `Anomaly`) appended to each user record
- Cleanly exported dataset for use in BI dashboards or audits

---

## 🧑‍💻 Developed With

- Python
- pandas, numpy
- scikit-learn
- seaborn, matplotlib

---

## 🗃️ Files

- `main.py`: Source code for simulation, detection, and visualization
- `user_behavior_anomaly_report.csv`: Output file with anomaly labels

---

## 📜 License

Open-source under the MIT License.

---

## 🙋‍♂️ Author

**IamXraj**  
📬 GitHub: [IamXraj](https://github.com/IamXraj)

