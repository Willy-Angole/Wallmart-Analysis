# load the app in the backend

uvicorn main:app --reload 

# run the frontend

yarn dev

# solve errors of conflicting versions of next js

nvm install 18.17.0

nvm use 18.17.0

then run the application again