# Machine-Learning-Project-WWI21DSB

docs contains documentation of the project

app contains code-content including first sample notebooks and further developed code

----------Setup details----------
1. install https://visualstudio.microsoft.com/de/downloads/?q=build+tools VS C++ build tools, rest isn't needed and can be unchecked during installation process
2. To dodge issue with your current tensorflow version on your machine it's highly recommended to create a python virtual environment on your machine
    -> first    run                 python -m venv "name"
    -> second   activate your venv  .\"name"\Scripts\activate
    -> third    update pip          python -m pip install --upgrade pip

3. To start the setup install all needed dependencies by running                                                        pip install -r requirements.txt
4. Allect a new ipykernel to install more needed dependencies by running                                                python -m ipykernel install --user --name="name" 
5. Run through the requirements.ipynb, if the VERIFICATION_SCRIPT print an "OK"-message the setup was successfull
6. run avometer.py through your console                                                                                 python avometer.py
7. enjoy classifying your avocados :D

