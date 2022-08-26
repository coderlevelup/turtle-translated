# turtle-translated

turtle-translated is a collection of translations of python turtle into many spoken languages.

The primary goal of this project is to make it more delightful to learn python by being able to instruct the turtle in the learner's home language.

## Installation

Clone this repo (or download the specific language file).

Either run python in the repo folder (or the folder where the file is), or put the relevant file into python path.

## Usage
Example of using the isiXhosa translation `fudo`
```python console
>>> import fudo
fudo(turtle) 0.0.3 - yePython 3 - 2022

>>> help(fudo)
Help on module fudo:

NAME
    fudo

DESCRIPTION
    Imizobo yoFudo yindlela edumileyo yokwazisa inkqubo kwi
    abantwana. Yayiyinxalenye yolwimi lokuqala lweLogo oluphuhlisiwe
    nguWally Feurzig kunye noSeymour Papert ngo-1966.

    Yiba nomfanekiso wofudo lwerobhothi oluqala ku- (0, 0) kwinqwelo-moya ye-x. Emva kwe ``import ufudo``, lunike
    umyalelo turtle.phambili(15), kwaye iyashukuma (on-screen!) 15 pixels in
    icala elijonge ngakulo, lizoba umgca njengoko lihamba. Yinike i
    umyalelo turtle.ekunene(25), kwaye ijikeleza-endaweni 25 degrees ngokwewotshi.

    Ngokudibanisa le miyalelo kunye nezinye ezifanayo, iimilo ezintsonkothileyo kunye
    imifanekiso inokuzotywa ngokulula.

    ----- fudo.py

>>> thabo = fudo.Fudo()
opens a new window with a turtle in the middle

>>> thabo.phambile(100)
moves the turtle forward 100 pixels

>>> thabo.ekunene(90)
turns the turtle right 90 degrees

>>> thabo.umva(90)
moves the turtle back 100 pixels

>>> thabo.ekhohlo(90)
turns the turtle left 90 degrees

```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

The project is in an exploratory phase, please feel free to add a language file for your language or to improve on the current one, but note that we will almost definitely restructure (or heavily refactor) the files once we find the shape of things.

## License
[Python license](https://docs.python.org/3/license.html)