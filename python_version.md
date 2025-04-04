# check installed python versions
pyenv versions

# choose python version
pyenv local 3.10.15

# create virtual environment inside project dir
python -m venv venv

# activate the virtual environment
source venv/bin/activate

# additional
pip install --upgrade pip
pip install -r requirements.txt
