<p align="center"><img src="https://capsule-render.vercel.app/api?type=waving&color=0:111827,100:4338ca&height=180&section=header&text=Confusion%20Matrix%20Lab&fontSize=36&fontColor=ffffff" width="100%" alt="Confusion Matrix Lab banner"></p>
<p align="center"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=19&pause=1000&color=818CF8&center=true&vCenter=true&width=620&lines=Evaluate+classification+predictions;See+precision%2C+recall+and+F1+per+class" alt="Animated tagline"></p>
<p align="center"><img src="assets/mark.svg" width="100" alt="Confusion matrix icon"></p>
<p align="center"><img src="https://img.shields.io/github/license/CyberLoop-dev/confusion-matrix-lab?style=flat-square" alt="License"><img src="https://img.shields.io/github/languages/top/CyberLoop-dev/confusion-matrix-lab?style=flat-square" alt="Language"><img src="https://img.shields.io/github/stars/CyberLoop-dev/confusion-matrix-lab?style=flat-square" alt="Stars"><img src="https://img.shields.io/github/last-commit/CyberLoop-dev/confusion-matrix-lab?style=flat-square" alt="Last commit"></p>

## 🧭 Overview
Confusion Matrix Lab evaluates a classifier's predicted labels against known actual labels. Paste or open a CSV with `actual` and `predicted` columns to see a confusion matrix and per-class metrics. It evaluates supplied predictions; it does not train a model.

## ✨ Features
- 🧮 Build a confusion matrix for any set of class labels.
- 🎯 Calculate accuracy, precision, recall, F1, and macro-F1.
- 📊 Compare class counts and prediction mistakes visually.
- 📂 Load a local CSV or edit the included sample data.
- 🔒 CSV parsing and calculations run in the browser.

## 🎬 Demo
No hosted demo is published. Select **Load sample** after starting the local server.

## 🚀 Quick Start
Requires Node.js 18 or newer.
```bash
npm start
```
Open [http://localhost:4177](http://localhost:4177).

CSV format:
```csv
actual,predicted
cat,cat
dog,cat
dog,dog
```

## 🧰 Tech Stack
- Node.js built-in HTTP server
- Browser JavaScript and HTML tables
- No runtime dependencies

## 🗂️ Folder Structure
```text
confusion-matrix-lab/
├── assets/mark.svg
├── public/{app.js,index.html,style.css}
├── .gitignore
├── LICENSE
├── package.json
├── README.md
└── server.js
```

## 🗺️ Roadmap
- [ ] Add weighted averages.
- [ ] Add normalized matrix modes.
- [ ] Add downloadable metrics JSON.

## 🤝 Contributing
Contributions are welcome. Keep metric definitions explicit and include examples with imbalanced classes.

## 📄 License
Released under the [MIT License](LICENSE).

<p align="center"><img src="https://capsule-render.vercel.app/api?type=waving&color=0:4338ca,100:111827&height=100&section=footer" width="100%" alt="Footer wave"></p>