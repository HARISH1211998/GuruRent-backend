## ⚙️ **Backend (FastAPI + Supabase + Render)**

```markdown
# GuruRent Backend

This is the **backend service** for GuruRent, built with FastAPI + PostgreSQL.  
It provides REST APIs for users, items, bookings, and payments.

---

## 🚀 Tech Stack
- FastAPI (Python web framework)
- PostgreSQL (Database – Supabase free tier)
- SQLAlchemy + Alembic (ORM + migrations)
- JWT Authentication
- Hosted on **Render**

---

## 📂 Project Structure

---

## 🔧 Setup Instructions
```bash
# Clone repo
git clone https://github.com/<your-username>/gururent-backend.git
cd gururent-backend

# Create virtual env
python3 -m venv venv
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt

# Run locally
uvicorn app.main:app --reload


