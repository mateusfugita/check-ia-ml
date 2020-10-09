# Check-IA ML

## Technologies
- Flask
- scikit-learn

## Running locally
1. Install the dependencies
```
$ pip install -r requirements.txt
```
2. Run the application
```
$ python app.py
```
3. The application will be running in **localhost:5000**.

## Running with Docker
1. Run the following commands on terminal
```
$ docker build -t <CONTAINER-NAME>:latest .
$ docker run -p 5000:5000 <CONTAINER-NAME>:latest
```
2. The application will be running in **localhost:5000**.
