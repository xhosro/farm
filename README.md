- first we install fastapi : 
    
    python3 -m venv venv
    source ./venv/bin/activate 
    touch Dockerfile
    touch pyproject.toml
    pip install "fastapi[all]" "motor[srv]" beanie aiostream
    pip freeze > requirements.txt

    touch src/server.py
    touch src/dal.py (data access layer)

    uvicorn main:app --reload

npx create-react-app my-app 



   
   