# pyndemic web backend
## fastapi app
* Activate/create venv 
* Install requirements - `pip install -r requirements.txt`
* Start web server - `uvicorn src.main:app --reload`  
`--reload` argument for hot reload server
* After need get session token in `/auth` endpoint  
documentation in `/docs` endpoint

## frontend app
Frontend server is Vue.js app
* App directory is `frontend`
* Available by url `/static/game_view.html`
* API deployed at `127.0.0.1:5000/actions/api/v1`
* Web version https://divergent-app.ru/pyndemic

