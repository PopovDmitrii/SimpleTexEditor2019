# TeX Editor 

![](https://pp.userapi.com/c846220/v846220531/1a9555/GafoHl3Vphk.jpg)

## Purpose
TeX Editor is a project designed to generate in a canonical and science-like form of formulas and comments to them. The application was created to simplify the work with TeX code when the user needs to obtain formula in the form of a graphic image quickly. Application functionality includes the following mathematical symbols:
- standard set of mathematical symbols (+, -, *, /, =, < , >)
- \pm - plus-minus sign
- \cdot - an another way to indicate multiplication
- \le, \ge - inequality signs
- \neq - not equal sign
- \sqrt - square root (and \sqrt[p] -- root of p-th any degree)
- \sum - summation sign
- \prod - product sign
- \frac{}{} - fraction (including multi-level fractions)
- ^{} - subscript or exponentiation sign (including multi-level degrees)
- _{} - subscript
Code for symbols is not necessary for the user to memorize. Special hints are built into the applications, as well as buttons with corresponding symbols on them.
 
The application interface consists of two windows: in the left one user enters the formula in text format (or uploads the text-file), and in the right one the formula is generates as an image.

### How to use the application?
1. To run the application, open a "TeX_Editor.html" file. 
2. On the next screen you can open a text file with your code from a local disk or start writing it yourself in a text box.
3. It is possible to select the mode of automatic rendering of the image while writing a formula or rendering by pressing a special button.
4. If the user makes a syntax error during operation, the notification will appear and the program will stop rendering.
5. Upon completion, you can save your formula as an image or as a text file with a code.
6. The application can be run on mobile devices, as well as in the browser.

## Limitations 

- The length of the entered text should not exceed 250 characters (formula + short commentary).
- The size of the uploaded file should not exceed 250 bytes.
- Multi-level fractions and degrees can have no more than three levels.

## Prerequisites 
### Download [NodeJS](https://nodejs.org/en/download/) 
Version not below than v.6.10.3 is required.
After NodeJS installation please check that everything is installed correctly (for example, PATH ), using command:
```
node --version
```
Stdout should be v6.10.3 (or higher). 

### Install all node packages 
``` 
npm install 
``` 
After this command you will see node_module folder. 

## Command interface 

### Run & Debug 
``` 
npm run start 
``` 
### Check project source syntax
``` 
npm run lint: js> syntax_error.txt 
``` 
After running the command in the file syntax_error.txt you should see no warnings and no errors.

### Run project unit-tests 
```
npm run test
```
You should see no errors, if all tests are passed.

### Build project documentation 
``` 
npm run doc
``` 
The result will be in the folder docs.

### Build project bundle to upload app on server
``` 
npm run build 
``` 
The result will be in the 'build' folder


