# Mnist Data Neural Network Visualization 
This project tries to assert how a trained deep learning neural network model predicts the correct output label.For this project i have used mnist dataset also known as hand writtern numbers dataset to try to understand what happens between output and input layers more specifaclly how activation of each neuron takes place.Its a simple neural network with 32 neurons in two the hidden layers.Hope you enjoy it. 
<br />
You can see it live in https://jinu-mnist-net.herokuapp.com/ .

## Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites
Make sure that you have python pre-installed on your PC.
Things you need to install the software and how to install them:

streamlit
tensorflow 
jsonschema
numpy
json5
flask
matplotlib
```
pip install streamlit
pip install tensorflow
pip install jsonschema
pip install numpy
pip install json
pip insatll flask
pip install matplotlib

```
### Installing
A step by step series of examples that tell you how to get a development env running:
1) Clone this Github repository on your local env or PC.
2) Open terminal and cd to the folder where mlServer.py is located.
3) Run python mlServer.py and leave it running.
2) Open the folder where app.py file is located.
3) Open new terminal and cd to the folder where app.py is located.
4) Run command streamlit run app.py.
5) Development server will automatically open in your web browser

## Deployment
If you wish to deploy this project on heroku follow these steps:
1)First you have to  deploy mlserver which is in ml-server folder you will need Procfile,requirements.txt file and runtime.txt file which is availabe in the folder.<br />
2)Now for the secind step to deploy actual streamlit app open app.py file change the URI field in line 7 of the app.py file to the web domain of the app that you created in the above step.<br />
For deploying this app you will need a Procfile,requirements.txt file, and a stup.sh file all are available in this repository.Best Wishes😃😃😃.

## Demo

![](demo.gif)

## Built With

* [Streamlit](https://www.streamlit.io/) - The web framework used.
* [Heroku](https://www.heroku.com/) - Cloud Plateform for Deployment.

## Authors

* **[Jinendra Malekar](https://github.com/JINU98)**

## Acknowledgments

[Coursera](https://www.coursera.org/) - For keeping me busy.
