## 🚀 Getting Started

Follow these six steps to get the project up and running on your local machine.

### 1. Clone the Repository
Open your terminal and clone the codebase:
```bash
git clone [https://github.com/LordZeusIsBack/OYO-Clone.git](https://github.com/LordZeusIsBack/OYO-Clone.git)
cd OYO-Clone

# Windows
python -m venv venv
venv\Scripts\activate

# macOS/Linux
python3 -m venv venv
source venv/bin/activate

pip install -r requirements.txt

DEBUG=True
SECRET_KEY=your_secret_key_here
DB_NAME=oyo_db
DB_USER=postgres
DB_PASSWORD=your_password
DB_HOST=localhost
DB_PORT=5432

python manage.py makemigrations
python manage.py migrate





