# Machine-Learning-Project-WWI21DSB

app contains the Avometer application with setup configuration

docs contains documentation of the project

training contains the notebook for training of the model

# ----------Setup details----------

1. To dodge issues with your current tensorflow version on your machine it's highly recommended to create a python virtual environment on your machine<br>
   -> 1.1 `python -m venv "name"`<br>
   -> 1.2 `.\"name"\Scripts\activate`<br>
   -> 1.3 `python -m pip install --upgrade pip`<br><br>

2. To start the setup install all needed dependencies by running <br>  
   `pip install -r requirements.txt`<br>
3. Allect a new ipykernel to install more needed dependencies by running <br>  
   `python -m ipykernel install --user --name="name"` <br>
4. Run through the requirements.ipynb, if the model_builder_test print an "OK"-message the setup was successfull<br>
5. run avometer.py through your console<br>  
   `python avometer.py`<br>
6. enjoy classifying your avocados :D
