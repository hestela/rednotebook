[![Build Status](https://travis-ci.org/jendrikseipp/rednotebook.svg?branch=master)](https://travis-ci.org/jendrikseipp/rednotebook)

RedNotebook is a modern desktop journal. It lets you format, tag and
search your entries. You can also add pictures, links and customizable
templates, spell check your notes, and export to plain text, HTML,
Latex or PDF.

# Run RedNotebook under Linux

Install all dependencies, translate the application and run RedNotebook
without installation:

    $ ./run

# Run RedNotebook under Windows

Install Python 2.7 (32-bit version), clone the repo, change into the
`win` directory, run

    C:\Users\you\rednotebook\win> python create-build-env.py

and follow the instruction to add ``C:\gtkbin`` to your path. Now
change back into the rednotebook directory and run

    C:\Users\you\rednotebook> python rednotebook/journal.py

Be sure to run using the **32-bit version** of Python! (Or else install
the 64-bit versions of the various dependencies required for the
project.)


# Detailed instructions

There are many packages available for different distributions, so you might
want to check the Downloads page first.

It is recommended to install the distribution's appropriate package,
but of course sometimes you want to try out the bleeding edge, hot new stuff.

If you don't want to mess with your distribution's package system, you might
want to just run the program, without installing it by using the command above.

## Requirements
  - Python 2.7 (3.x not supported)
  - PyYaml (>=3.05)
  - PyGTK (>=2.16)
  - pywebkitgtk (>=1.1.5)

  - Optionally:
    - python-chardet (http://chardet.feedparser.org)
      Better recognition of file encodings

# Installation
Please pay attention: Installing is very easy, uninstalling however can only be
done by removing the installed files manually.

    $ sudo python setup.py install --record installed-files

(installs into path-to-python/site-packages/ and saves a list of installed
files in "installed-files" to make an uninstallation easier)


# Thanks

- The authors of the programs listed under 'requirements'. Remember that without
  them, RedNotebook would not be possible.
- Everaldo Coelho (www.everaldo.com) for the original icon (easymoblog.png) and
  Ciaran for the excellent redesign.
- The txt2tags team (http://txt2tags.sf.net) for their super cool markup tool.
- The people behind the Tango Icon Project and the creators of the Human Theme.
  Their work can be downloaded from http://tango.freedesktop.org/
- Ahmet Öztürk and Lifeograph for his markup highlighting idea
- Hannes Matuschek: The code for markup highlighting uses a specialized version
  of his pygtkcodebuffer module (http://code.google.com/p/pygtkcodebuffer/).
- Dieter Verfaillie: For his elib.intl module
  (https://github.com/dieterv/elib.intl)
- Eitan Isaacson: RedNotebook took his idea and some code for converting HTML
  documents to PDF (http://github.com/eeejay/interwibble/).


# License notes

RedNotebook is published either under the terms of the GPL version 2 or any
later version of the license. It includes the elib.intl module
(https://github.com/dieterv/elib.intl) which is released under the LGPLv3+.
This means that the resulting work is licensed under the GPLv3+.


Enjoy!
