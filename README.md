# Microsoft Outlook Offline Address Book parser

So microsoft has this file format called OAB, the Offline Address Book format which nobody has any way of parsing, but for some reason they spend all this effort documenting the format. 
```
    --..,_                     _,.--.
       `'.'.                .'`__ o  `;__.      cjr
          '.'.            .'.'`  '---'`  `
            '.`'--....--'`.'
              `'--....--'`
```

# Usage

```
python parse.py --help
usage: parse.py [-h] [-o OUTPUT] [-d] OABFILE

positional arguments:
  OABFILE               Path to OAB file

optional arguments:
  -h, --help            show this help message and exit
  -o OUTPUT, --output OUTPUT
                        Destination file, defaults to stdout
  -d, --debug           Debug
 ```
 


In reality, only the "udetails.oab" is supported.

# Why "boa"

*@antimatter15: bteedubs mad props to mah bro guillermo for coming up with da name. much clevarr. because it's like python, and boa constrictor and stuff anagram of oab*

*wow.*
