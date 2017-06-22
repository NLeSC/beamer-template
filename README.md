# beamer-template
Latex Beamer Template for the eScience Center

## Using the beamer template
Just download and copy the template then you can change it in whatever way you want.

### Building
I like to use latexmk to make the pdf out of this template. Under ubuntu I use xelatex to build it (this works better than pdflatex for some reason).
My full build command looks something like:

```bash
latexmk -synctex=1 -xelatex -interaction=nonstopmode -file-line-error -pdf main
```

## Contributing
Do you have good ideas or contributions feel free to send a pull request.

Please add optional features to the src directory so people can \input the file if they
want to use it

### style or theme
Does anyone know how to turn this into a beamer theme or style or both?
