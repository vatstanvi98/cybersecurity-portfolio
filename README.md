
# 🚨 SIEM Log Analysis – Brute Force Detection

## 🧠 Objective
Analyze login logs to detect brute-force attacks using custom detection logic.

## 🧰 Tools Used
- Python (Pandas, Matplotlib)
- Simulated login logs (CSV)
- Custom brute-force detection logic

## ⚙️ Detection Logic
If a source IP attempts 5+ failed logins within 5 minutes → mark as brute force.

## 🔍 Results
Suspicious IPs are written to `output/flagged_ips.csv`.

## 📁 Folder Structure
```
siem-log-analysis/
├── data/
│   └── auth_logs.csv
├── notebooks/
│   └── brute_force_detection.ipynb
├── output/
│   └── flagged_ips.csv
├── dashboard/
└── README.md
```

## 🧠 Lessons Learned
- Worked with time-based detection windows
- Simulated SIEM-style log data
- Built an effective brute-force detection logic
