# Health Insurance Cost Predictor

## 🚀 Overview
This **Machine Learning-powered application** predicts **health insurance costs** based on various factors. It utilizes two different models—one for individuals **below 25 years of age** and another for those **25 and older**—along with a **scaler model** to improve accuracy.

## 🛠 Tech Stack
- **Machine Learning Models**
- **Python** for backend processing
- **Streamlit** for deployment
- **Git & GitHub** for version control

## 📌 Features
✅ Predicts insurance cost based on user inputs
✅ Uses separate models for different age groups
✅ Scaled inputs for improved accuracy
✅ Deployed with Streamlit for easy access

## 🔗 Live Demo & Source Code
- **Live App:** [Health Insurance Cost Predictor](https://ml-premium-prediction-project-nenekjpysqmyppki6nde7v.streamlit.app/)
- **GitHub Repository:** [Source Code](https://github.com/Ayush95697/ML-Premium-Prediction-Project.git)

## 🖥️ UI Preview
![Health Insurance Cost Predictor](image.png)

## 🔍 How It Works
```python
if age < 25:
    prediction = model_young.predict(input_data)
else:
    prediction = model_old.predict(input_data)
```
This logic ensures that the correct model is used for different age groups.

## 📂 Installation & Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/Ayush95697/ML-Premium-Prediction-Project.git
   ```
2. Navigate to the project directory:
   ```bash
   cd ML-Premium-Prediction-Project
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the Streamlit app:
   ```bash
   streamlit run app.py
   ```

## 🎯 Future Improvements
- Adding more features like **region-based cost variations**
- Improving model accuracy with **advanced ML algorithms**
- Deploying on cloud services for **better scalability**

## 💡 Contributions
Feel free to fork this repository, open issues, and submit pull requests! 😊

## 📞 Contact
For any queries, reach out to me at: [Ayush Mishra](mailto:ayushmishra7548@gmail.com)
