# colorguide package

A package to display a guide of the colors used by UI and Syntax themes

![Sceenshot](https://cloud.githubusercontent.com/assets/17919240/17274519/e8c376fa-5699-11e6-9f21-aab794e32a23.png?raw=true)

![Sceenshot](https://cloud.githubusercontent.com/assets/17919240/17274538/e64c6db8-569a-11e6-817a-0246ff104287.png?raw=true)

## Notes

Firstly, please forgive me if I do anything wrong - this package is full of firsts - I've not written HTML / CSS / Less / Coffee before and, of course, not written a package for Atom before.

Colorguide will display the "final" values of the **custom** colors and color variables used by a theme - UI and Syntax.  

Unfortunately, in order to do this, I must add files into the theme and modify one file.  This is nesessary in order to obtain the actual values assigned to each variable.


## Configuration

Colorguide comes with configuration files for several of the popular themes:
UI: Atom Material, Isotope, Nucleus Dark, and Seti
Syntax: Atom Material, Atom Monokai, Fizzy, Gl-dark, Monokai, and Seti

Colorguide will display the colors values of Atom's required / Official UI and Syntax Variables even if the colorguide configuration files are not added to a theme.

I did not make configuration files for the out-of-the-box themes because:
1) they do not exist in the packages folder
2) they have only a few custom colors and color variables

### Configure A theme

This is an example of how to configure the seti-ui theme:
