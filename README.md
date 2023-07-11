# Machine-Learning-Project-WWI21DSB

Goal of this project is to develop a machine learning application which can be used to classify avocados during a live video-feed. <br>

It should be a prototype that with further development can be used to e.g. assist retailers in sorting out overripe avocados or assist avocado-farms in their picking procedure.<br>

Members of this group are Leonard Jung and Steffen Weiffenbach.

# Repository overview

app contains the Avometer application with setup configuration

docs contains documentation of the project

training contains the notebook for training of the model which was perfomed on Google Collab

# Setup details

Please bare in mind that setup is only tested for Windows based machines. <br>

1. To dodge issues with your current tensorflow version on your machine it's highly recommended to create a python virtual environment on your machine<br>
   -> 1.1 `python -m venv "name"`<br>
   -> 1.2 `.\"name"\Scripts\activate`<br>
   -> 1.3 `python -m pip install --upgrade pip`<br>

2. To start the setup install all needed dependencies by running <br>  
   `pip install -r requirements.txt`<br>

3. Allect a new ipykernel to install more needed dependencies by running <br>  
   `python -m ipykernel install --user --name="name"` <br>

4. Run through the requirements.ipynb, if the model_builder_test prints an "OK"-message the setup was successfull<br>

5. Run avometer.py <b>through your console</b>. A start through VS-Code e.g. won't work sufficiently. The app can be closed by pressing 'q' on your keyboard<br>  
   `python avometer_simplenet.py`<br>
   `python avometer_complexnet.py`<br>

6. Enjoy classifying your avocados :D
