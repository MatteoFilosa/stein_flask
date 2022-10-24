Steps to run the Flask server:

1) Install the requirements running "pip install -r requirements.txt" (If you don't have pip installed, install it)
1) Create a virtual environment by running the command "python -m venv <name_of_the_virtual_environment>" in the terminal
2) Activate the virtual environment by running <name_of_the_virtual_environment>\Scripts\activate 
3) If an error appears in the console telling that the execution of Scripts is not allowed, open a Windows
Powershell terminal in admin mode and enter the command "Set-ExecutionPolicy unrestricted". This will allow the policy of scripts execution in your machine to be unrestricted, so be careful
4) In the terminal, execute the command "set FLASK_APP=server_flask.py" or " $env:FLASK_APP = "server_flask" "
5) In the terminal, execute the command "flask run"

The server should now be running in localhost. Press the key combination "CTRL+C" to interrupt it.