# Dataset Tookit:

## Setting up a development environment

We assume that you have `git` and `virtualenv` and `virtualenvwrapper` installed.

    # Clone the code repository 
    git clone 

    # Create the 'dataset_toolkit_env' virtual environment
    virtualenv dataset_toolkit_env
    
    # Activate 'dataset_toolkit_env' virtual environment
    source/bin/activate dataset_toolkit_env

    # Install required Python packages
    pip install -r requirements.txt

## Running the app
    # Export 
    export FLASK_APP=app/application.py
    export PYTHONPATH=$PYTHONPATH:$PWD

    # Start the Flask development web server
    flask run

Point your web browser to http://localhost:5000/
