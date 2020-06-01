# ML-React-App
It's a template on which we can build a React app and call endpoints to make predictions.

### Edits by Manoj
1. Go to folder: example/iris-data-classifier/ML-React-App-Template/
2. Start the Flask Server
```
cd service
python3 -m venv pyvenv1
source pyenv1/bin/activate
pip3 install -r requirements.txt
FLASK_APP=app.py flask run
```

3. Start the React Front End
```
cd ui
npm install
npm install -g serve
npm run build
serve -s build -l 3000
```


### Usage
The complete guide to use this repository: https://towardsdatascience.com/create-a-complete-machine-learning-web-application-using-react-and-flask-859340bddb33
