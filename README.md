- first we install fastapi : 
    
    python3 -m venv venv
    source ./venv/bin/activate 
    touch Dockerfile
    touch pyproject.toml
    pip install "fastapi[all]" "motor[srv]" beanie aiostream
    pip freeze > requirements.txt

    touch src/server.py
    touch src/dal.py (data access layer)

    Create a mongodb database cluster in mongodb site
    ADD MONGODB_URI to .env
    Create a compose.yaml for nginx that reverse proxy for frontend & backend service.

npx create-react-app my-app 



   
   