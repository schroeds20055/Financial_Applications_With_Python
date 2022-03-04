# Loan Qualifier

The Loan Qualifier App provides users an easy way to obtain a list of lenders and loans they qualify for based on specific credentials. This can help streamline the process for users and provides them an option to save the qualifying loans into a csv file.

---

## Technologies

* Programming Language: Python 3.9.10
* [fire](https://github.com/google/python-fire) - For the command line interface, help page, and entry-point.
* [questionary](https://github.com/tmbo/questionary) - For interactive user prompts and dialogs

---

## Installation Guide

Before running the application first install the following dependencies.

```python3
  pip install fire
  pip install questionary
```
![install fire](loan_qualifier_app/data/images/install_fire.png?raw=true "install file")
![install questionary](loan_qualifier_app/data/images/install_questionary.png?raw=true  "install questionary")

## Usage

* To run the loan qualifier app, simply clone the repository and run **app.py** to get get a list of qualifying loans:

```python3
python app.py
```

* Upon launching the loan qualifier app you will be greeted with the following prompts/questions:
    
![initial loan qualifier prompts](loan_qualifier_app/data/images/user_credentials_results.png?raw=true  "user credentials")

* After inputting in credentials, the qualifier information and number of qualifying loans will display. you will then be greeted with the following question:

![saving list of qualified loans](loan_qualifier_app/data/images/saved_qualifying_loans.png?raw=true ?raw=true "list of qualified loans")

---

## Contributors

Project created by:

Cody Schroeder
email: fakeemail@email.com
Twitter: @faketwitter

---

## License

MIT License

Copyright (c) [2022] [Cody Schroeder]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
