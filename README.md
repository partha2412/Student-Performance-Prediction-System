# Student-Performance-Prediction-System

# flow->
  root/
  │
  ├── client/                  # React
  │
  ├── server/                  # Node + Express
  │   ├── routes/
  │   ├── controllers/
  │   ├── services/
  │   ├── uploads/              # CSV uploads
  │   └── index.js
  │
  ├── ml-service/               # Python ML service (separate)
  │   ├── model/
  │   │   └── model.pkl
  │   ├── train.py
  │   ├── predict.py
  │   ├── preprocessing.py
  │   └── app.py                # Flask / FastAPI
  │
  └── README.md

