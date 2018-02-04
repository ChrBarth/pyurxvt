# pyurxvt

### Change fonts and colors in urxvt on the fly

pyurxvt is a simple script that allows you to change fonts and colors in a
running urxvt-session. This is mostly for testing purposes (creating a new
colortheme). No changes made are permanent so if something gets
messed up, you can just close and re-open urxvt and the original colors and
fonts are restored.

## Usage:

'''pyurxvt [-h] [-t TITLE] [-f FONT] [-b BOLDFONT] [-i ITALICFONT]
               [-o BOLDITALICFONT] [-s] [-l LOAD]

Sends Commands to urxvt

optional arguments:
  -h, --help            show this help message and exit
  -t TITLE, --title TITLE
                        sets the title
  -f FONT, --font FONT  sets the font
  -b BOLDFONT, --boldfont BOLDFONT
                        sets the bold font
  -i ITALICFONT, --italicfont ITALICFONT
                        sets the italic font
  -o BOLDITALICFONT, --bolditalicfont BOLDITALICFONT
                        sets the bold-italic font
  -s, --sample          display some sample-text
  -l LOAD, --load LOAD  load colors from file (in .Xresources format)'''
