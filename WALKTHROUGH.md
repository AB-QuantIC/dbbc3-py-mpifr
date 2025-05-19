
# Document
https://dbbc3.readthedocs.io/en/latest/source/installation.html

# Installation (Ubuntu)

sudo apt update
sudo apt install python

sudo apt-get install python-setuptools

pip install mock
pip install numpy

-------------------------------------
-------------------------------------

git clone https://github.com/mpifr-vlbi/dbbc3.git
cd lib
sudo python setup.py install

# Open document

cd docsrc
make html
cd _build/html
python -m SimpleHTTPServer 4000

At browser, go to:
>> http://localhost:4000/