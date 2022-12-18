ARCTool v0.4rc1 12/18/2022
By tpw_rules, fork by calmsacibis995

ARCTool is a Python script that can extract the multitude of different formats found in .arc game files. It has support for Yaz0, U8, and RARC, which are all that I have found.
The inspiration for this tool came about when I wrote a RARC extractor and realized that all the files I wanted to extract were U8, but they still had the arc extension.
I have confirmed Yaz0 and U8 support to be 100% working.
If you have any trouble with it, message me on IRC (nick is tpw_rules) or leave a note on the talk page.
The script now somewhat works with Python 3.10, under Linux (should work under Windows and macOS)

Usage: python ARCTool.py [-qlh] [-o <output>] <inputfile> [inputfile2] ... [inputfileN]

Options:
  --version             show program's version number and exit
  -h, --help            show this help message and exit
  -o FILE/DIR, --output=FILE/DIR
                        write output to FILE/DIR. If you are extracting
                        multiple archives, all of them will be put in this
                        dir.
  -q, --quiet           don't print anything (except errors)
  -l, --list            print a list of files contained in the specified
                        archive (ignores -q)

Requirements:
Python 3.x and newer (Python 2 has been deprecated). Get Python for your OS at http://python.org/download/

THANKS TO

tpw_rules for originally creating this program.
