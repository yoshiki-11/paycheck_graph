# PaycheckGraph

<!-- ##### Analyse your paycheck -->

[![Generic badge](https://img.shields.io/badge/python-v3.7.4-336E9F.svg)](https://shields.io/)
[![Generic badge](https://img.shields.io/badge/MongoDB-v4.2.3-14AA52.svg)](https://shields.io/)

<!-- Put Sample Image Here -->
## Getting Started

**Update(February 5, 2020)**: Paycheck at where I work is published by a PDF file. Just reading them, might be enough for checking erros, but do you not want to see *trends* over time?

This package creates statical graphs of your paycheck! Download it and try putting your pdf file in the suggested folder where instructed below.

*Notice: This package only works at a company where I work (at this moment.)*

### Prerequisites
* Paycheck downloaded (in pdf format). 


### Installing
Install MongoDB to your local environment.
<br>See
[The Official MongoDB Software Homebrew Tap](https://github.com/mongodb/homebrew-brew).

Git clone this repository.
```bash
$ git clone https://github.com/yoshiki-11/paycheck_analytics.git
```

Pip install *requirements.txt*.
```bash
$ pip install requirements.txt
```

## Running the test
### Analyse your data
Set your pdf files at `data/pdf`.

Run <br>
```bash
$ python main.py
```


## Built With
* [pdfminor.six](https://github.com/pdfminer/pdfminer.six) - Used to extract text from pdf files.
* [MongoDB](https://github.com/mongodb/mongo) - Database used.

