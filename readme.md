# read the setup.py file
python setup.py sdist 

# twine is needed, hence
pip install twine
# Once installed
twine upload --skip-existing dist/*

# if twine not recognized, install twine on the python scripts directory
# then run

twine upload --skip-existing dist/*

# enable 2 factor authentication & tokens in PYPI
in account setting of Pypi

# if any change made to the code & setup file, read the setup.py file again
python setup.py sdist 

# then again the below code to upload the package.
twine upload --skip-existing dist/*





