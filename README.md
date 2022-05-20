# rajini++ : Superstar-Programming-Language


![banner_thin](https://user-images.githubusercontent.com/6749212/168450764-5ae486d8-8299-4425-b51d-cf3b9538efb2.png)



[![GitHub Workflow Status](https://img.shields.io/github/workflow/status/aadhithya/rajiniPP/Test%20and%20Release?logo=Github%20Actions&logoColor=%23fff&style=flat-square)](https://github.com/aadhithya/rajiniPP/actions/workflows/release.yml)
[![GitHub issues](https://img.shields.io/github/issues/aadhithya/rajiniPP?style=flat-square)](https://github.com/aadhithya/rajiniPP/issues)
[![GitHub release (latest SemVer)](https://img.shields.io/github/v/release/aadhithya/rajiniPP?logo=semantic%20release&style=flat-square)](https://pypi.org/project/rajinipp/)
![GitHub Release Date](https://img.shields.io/github/release-date/aadhithya/rajiniPP?logo=semantic%20release&style=flat-square)
![PyPI - Python Version](https://img.shields.io/pypi/pyversions/rajinipp?logo=PyPI&logoColor=%23eaeaea&style=flat-square)
![PyPI - License](https://img.shields.io/pypi/l/rajinipp?style=flat-square)
![GitHub commits since latest release (by SemVer)](https://img.shields.io/github/commits-since/aadhithya/rajiniPP/latest/master?style=flat-square)



rajini++ (rajiniPP) is a programming language is a tribute to the one and only superstar and based on the iconic dialogues of Rajinikanth. Came across to this fun project by aadhithya, is not meant to be used for serious software development.

## Superstar Rajinikanth
- [Who is Rajinikanth](https://www.youtube.com/watch?v=YDUQZwMHMoo)?
- [Rajinikanth on Wikipedia](https://en.wikipedia.org/wiki/Rajinikanth).

## Installation
- rajinipp requires **python >= 3.8**. Install python from [here](https://www.python.org/downloads/).
- Install the rajini++ interpreter using the following command:
  `pip install rajinipp` in your terminal

- test installation: `rajinipp version`

## Getting started

rajini++ is not a feature rich language and is not intended for serious use. It is rather a hobby project and a tribute to the one and only superstar.

### Run programs
`hello_world.rpp`:  
```
LAKSHMI START
DOT "Hello, World!";
MAGIZHCHI
```
- save it has a .py file and execute using
- Run the `hello_world.rpp` program:

  `rajinipp run examples/hello_world.rpp` or
  `python -m rajinipp run examples/hello_world.rpp`
  

will result in the following output:

![hello world output](./imgs/hello-out.png)



## Resources
- **Learn the rajini++ language**:
  -  **The rajini++ language documentation** can be found at the [rajiniPP Wiki](https://github.com/aadhithya/rajiniPP/wiki/).
  -  Example programs can be found here: [Example Programs](https://github.com/aadhithya/rajiniPP/tree/master/examples).
- **The rajini++ Language Spec**: The rajini++ commands and its equivalent in python3 can be found at the [rajiniPP Language Spec](https://github.com/aadhithya/rajiniPP/wiki/rajiniPP:-Language-Specification) wiki.
- **The rajinipp Interpreter Documentation**: The documentation for the rajinipp interpreter can be found [here](https://github.com/aadhithya/rajiniPP/wiki/rajinipp:-The-interpreter).


## Acknowledgements
- A lot of learnings from [DIVSPL](https://github.com/di/divspl) and its accompanying [pycon talk](https://www.youtube.com/watch?v=ApgUrtCrmV8).
- A lot of learnings from [this pycon talk](https://www.youtube.com/watch?v=LCslqgM48D4&t=1388s) by [Alex Gaynor](alex).
- Workflows setup based on [poetry_pypi_template](https://github.com/a-parida12/poetry_pypi_template).
- This project is inspired by the [ArnoldC](https://github.com/lhartikk/ArnoldC) project.


```
!! Declare function
EN VAZHI THANI VAZHI myfunc_one

    !! FOR LOOP
    NAA 1 THADAVA SONNA range THADAVA SONNA MADHRI{
        AANDAVAN SOLLRAN ix ARUNACHALAM SEIYARAN 100;
        DOT "Hello from myfunc_one!";
        DOT "returning variable value =" ix ;
    }KATHAM KATHAM;

    !! Return ix
    IDHU EPDI IRUKKU ix;

MARAKKADHINGA

!! Main Program
LAKSHMI START
DOT "Hi from main!";

AANDAVAN SOLLRAN range ARUNACHALAM SEIYARAN 3;

!! Assign function return value to y
y CHUMMA ADHURUDHULA myfunc_one;

DOT "Value returned from myfunc_one:" y;

MAGIZHCHI
```
