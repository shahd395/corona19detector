# corona19detector
1.
in cmd : 

& git clone https://github.com/shahd395/corona19detector.git

& cd ml-flask-demo

& python3 -m venv env
& .\env\Scripts\activate.bat
& pip3 install -r requirements.txt
& python3 app.py

,,,,,,
2. 
Test locally: 

GET
http://localhost:5000


POST
http://localhost:5000/predict  (pass in a JSON body with your post request)

,,,,,,
3. 
Deploying to Heroku

& heoku login
& heroku create
& git push heroku main
& heroku open

