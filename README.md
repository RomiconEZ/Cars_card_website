Frontend:
Установить зависимости: npm install
Запустить frontend: npm start

Backend:

 python -m venv venv

venv/Scripts/activate

pip install -r requirements.txt
uvicorn backend.main:app --reload

