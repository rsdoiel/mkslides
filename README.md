
# md2slides

Convert a Markdown file into a sequence of HTML5 slides.

+ Use Markdown to write your presentation in one file
+ Separate slides by "--" and a new line (e.g. \n versus \r\n)
+ Apply the simple default template or use your own
+ Control Layout and display with HTML5 and CSS

## Releases and cross compilation

The script [mk-release.sh](./mk-release.sh) cross compiles *md2slides* for Windows, Max OS X, Linux (amd64) and Raspberry Pi (Raspbian/ARM7).
It places all the resulting executable programs in the *dist* folders.

## windows issues

*md2slides* has very limited Windows testing done.  *md2slides.exe* 
presumes the Unix style new line only and not the old DOS/Windows CR/LF type endings.


