# Accounting ERP App (Python + FastAPI + PostgreSQL)

## 📦 Installation Guide (English)

### Requirements
- Python 3.10+
- PostgreSQL database (`TMFSS2025`)
- Git

### Steps
```bash
git clone https://github.com/ITMVBTOPY/Accounting-ERP-App-.git
cd Accounting-ERP-App-
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate
pip install -r requirements.txt
uvicorn app.main:app --reload

