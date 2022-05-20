# rajini++ : Superstar-Programming-Language


![banner_thin](https://user-images.githubusercontent.com/6749212/168450764-5ae486d8-8299-4425-b51d-cf3b9538efb2.png)


![PyPI - Python Version](https://img.shields.io/pypi/pyversions/rajinipp?logo=PyPI&logoColor=%23eaeaea&style=flat-square)

rajini++ (rajiniPP) is a programming language is a tribute to the one and only superstar and based on the iconic dialogues of Rajinikanth. Came across to this fun project by aadhithya, is not meant to be used for serious software development.

## Superstar Rajinikanth
- [Who is Rajinikanth](https://www.youtube.com/watch?v=YDUQZwMHMoo)?
- [Rajinikanth on Wikipedia](https://en.wikipedia.org/wiki/Rajinikanth).

## Installation
- rajinipp requires **python >= 3.8**. 

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

`Hello, World!" `

## Acknowledgements

- This project is inspired by the [ArnoldC](https://github.com/lhartikk/ArnoldC) project.


## Embedding rajini++ code in python scripts

rajinipp interpreter is written completely in python, it is possible to run rajini++ code inside python scripts
```
from rajinipp.runner import RppRunner

def main():
    # * initialize the rajinipp runner
    rpp = RppRunner()
    print("Hello, World from python!")
    rpp.eval('DOT "Hello world from rajini++!";')

    # * It is also possible to access the outputs of the rpp code
    print("Executing 5+5 in rajini++")

    out = rpp.eval("5+5;")

    print(f"5 + 5 = {out}")


if __name__ == "__main__":
    main()   
```

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
