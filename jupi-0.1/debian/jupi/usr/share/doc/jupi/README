Jupi 0.13

Author: Leo Szumel

Description:
  A script to quickly, easily, and temporarily post files to a 
  web host from the command line.
  Intelligent previews are created for known filetypes. 
  It is easy to add new file types.
  I am *very interested* in your experience using jupi; please
  send me feedback and/or post bugs / feature requests / etc!

Installation:
  I'd like to make an installer, but for now follow these three steps:

  1.0
  Put jupi in a good place (e.g. /usr/local/bin)
  
  1.1
  Create a ~/.jupirc containing the fields from jupi that you want to modify
  You should set at least these:
    cat > ~/.jupirc
    HTML_MACh = 'www.domain.net'
    HTML_DIR  = 'Html/jupi'
    HTML_USER = 'williewonka' 
    HTML_EXTERNAL_ROOT = 'http://www.domain.net/~williewonka/jupi'
    ZIP_ICON = '~/images/mr_zip.png'
    PAGEAUTH = 'Willie Wonka'
    AUTHEMAIL= 'willie@domain.net'

    Each field is commented inside jupi; check it out.

  1.2 
  You may need to install packages like imagemagick, pstools, pdftools, jhead, etc.
  Best way is to start using jupi and follow the errors. If folks send me a list
  of packages they had to install, I'll compile them into a list.

Usage:
  "jupi [option(s)] [file(s)] [dir(s)]
  A TinyURL is printed to the console. Send that link to your friend(s).

Options:
  try "jupi -h"

Bugs:
  -clip option currently not working; it should place the URL in the clipboard.
