# Part II
This is the solution for the part two of the assessment

### Instructions to run the framework

You need the following in your computer to run the framework
* Selenium grid
* Python

If you already have a selenium grid, you only need to go to **UI/config/config.ini** and make sure the seleniumAddress is the correct

### How to install python
See instruction in the readme file of the part_one folder, section "How to install python"

Once python is installed, go to install the requirements by the command
```
pip install -r requirements.txt
```

### How to install Selenium grid
For this framework, we are going to install webdriver-manager as the selenium grid 
There are several ways to install it, you can use brew if you are on Mac 
but I'd recommend to install NodeJS because it will run on Windows or Mac

#### How to install NodeJS
Get the executable from the Node JS page https://nodejs.org/es/download/
and install it, or you can install it from brew

Once you are done, NodeJS and npm will be installed

Run the following command to install the web-driver
```
npm i webdriver-manager -g
```

Now, run the following command to update it
```
webdriver-manager update
```
And start the web manager by the command
```
webdriver-manager start
```

## Running the test
Now, if everything is installed, open the terminal, and go to the folder **part_two**
Run the command
```
python UI/tests/product/TS001ValidateProductCanBeAddedToCart.py
```