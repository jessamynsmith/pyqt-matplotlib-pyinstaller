# pyqt-matplotlib-pyinstaller

Example of using pyinstaller to create a Python app that contains pyqt and matplotlib.

Like my work? Tip me! https://www.paypal.me/jessamynsmith


### Development

Fork the project on github and git clone your fork, e.g.:

    git clone https://github.com/<username>/pyqt-matplotlib-pyinstaller.git

Create a virtualenv using Python 3 and install dependencies. I recommend getting python3 using a package manager (homebrew on OSX).

    python3 -m venv pyqt-matplotlib-pyinstaller
    pip install -r requirements.txt

Run the application:

    python app.py
    
Create an executable using pyinstaller:

    pyinstaller app.py
    
Navigate to the dist directory to run the application.
