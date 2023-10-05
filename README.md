# Face_Recognition
Clone this repository
# Run Locally
## then make a new virtual environment using the below command for windows
python -m venv .ven
## install requirements.txt file
pip install -r reqirements.txt
### then run the app.py file locally
python app.py
now you can test with postman
1. Open postman
2. Move to Body Tab
3. Enter Key name as image_a and image_b and parameter as file
4. Select Images you want test it
5. press send request
6. now you the JSON response
##  Run on Docker container
1. Open docker container desktop app 
2. Then run this command
   docker build -t app .
   (This will build docker image)
3. docker run -d -p 8502:8502 app (run docker via command prompt)
4. docker ps (check status of container id)
5. docker logs CONTAINERID (check the docker running status)
