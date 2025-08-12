# Student Marks Prediction (Regression Project)

Predicts student marks based on other subjects using a complete ML pipeline with data ingestion, transformation, model training, and deployment via a Flask web app.

---

## Project Structure

```
mlproject1/
├── app.py
├── application.py
├── requirements.txt
├── src/
│ ├── data_ingestion.py
│ ├── data_transformation.py
│ ├── model_trainer.py
│ ├── prediction.py
│ ├── logger.py
│ ├── exception.py
│ └── utils.py
├── templates/
│ └── index.html
└── artifacts/
└── trained_model.pkl
```



## How to Run

1. Install dependencies: `pip install -r requirements.txt`  
2. Train model: `python application.py`  
3. Launch web app: `python app.py`  
4. Open `http://127.0.0.1:5000` in browser




## Skills Demonstrated

- Data pipeline design (ingestion, transformation)  
- Regression modeling and evaluation  
- Flask-based model deployment  
- Logging and error handling
