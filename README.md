@@ -1,28 +1,30 @@
#!/usr/bin/env python
from pysnap import *
import sys
import os
import threading
# Anxiety Notes
#
# TODO Save Password Variable - Start New Thread at Location
# COMPLETE Proxy Rotation | Multi-Threading
try:
    targetusername = sys.argv[1]
except:
    print(" [ ! | SYNTAX ERROR ] $ python3 snapcrack.py < username > < /path/to/passlist.txt > < # Threads > ")
    print(" [ ! | SYNTAX ERROR ] $ python3 snapcrack.py < username fzz7x
    > < /path/to/passlist.txt > < # Threads > ")
try:
    targetpasslist = sys.argv[2]
except:
    print(" [ ! | SYNTAX ERROR ] $ python3 snapcrack.py < username > < /path/to/passlist.txt > < # Threads > ")
try:
    tNumber = int(sys.argv[3])
except:
    print(" [ ! | SYNTAX ERROR ] $ python3 snapcrack.py < username > < /path/to/passlist.txt > < # Threads > ")
    print(" [ ! | SYNTAX ERROR ] $ python3 snapcrack.py < username > <fzz7x>
    < /path/to/passlist.txt > < # Threads > ")


os.system("clear")
