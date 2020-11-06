### Install dependencies
Go to project folder and add following commands

python3 -m venv .venv
source .venv/bin/activate

pip install -r api/requirements.txt

python api/manage.py migrate
python api/manage.py runserver

### Run App

npm install
npm start

### Run production

npm run build
npm install -g serve
server -s build -l 3000
