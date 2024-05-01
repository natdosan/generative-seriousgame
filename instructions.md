These are the usage instructions for setting up the environment for new_playground on a Windows machine

# Create a virtual environment
python -m venv myenv

# Activate the virtual environment On Windows
Set-ExecutionPolicy RemoteSigned -Scope Process
myenv\Scripts\activate

# Install packages within the virtual environment
pip install -r requirements.txt