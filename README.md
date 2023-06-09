# infra_actions
Учебный проект для изучения работы GitHub Actions (Яндекс Практикум)

### Как запустить проект:

Клонируем репозиторий и переходим в него:
```bash
git clone https://github.com/SergeiTregubov/infra_actions.git
```
Создаем и активируем виртуальное окружение:
```bash
python -m venv venv
source venv/Scripts/activate
python -m pip install --upgrade pip
```
Ставим зависимости из requirements.txt:
```bash
pip install -r requirements.txt
```
Переходим в папку cd infra_project/:
```bash
cd infra_project/
```
Запускаем север:
```bash
python manage.py runserver
```
Создаем суперпользователя:
```bash
python manage.py createsuperuser
```
Делаем миграции:
```bash
python manage.py makemigrations
python manage.py migrate
```
