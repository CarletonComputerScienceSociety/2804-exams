# 2804 Exams

Exams from Carleton University's COMP 2804 Discrete Structures II course, expressed in the [Taoquiz](https://github.com/startrekdude/taoquiz) `.quiz` format.

Material originally created by [Michiel Smid](https://cglab.ca/~michiel/2804.html) and [Pat Morin](https://cglab.ca/~morin/teaching/2804/oldexams.html).

## Building

Frist run the `.quiz` file through `mathdefs.py` (in the Taoquiz repository under the `utils` directory), then through Taoquiz, like so:

```sh
~/2804-exams$ python $TAOQUIZ/utils/mathdefs.py f13-final.quiz | taoquiz - f13-final.html
```

