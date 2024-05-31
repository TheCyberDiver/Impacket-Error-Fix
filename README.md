# Impacket-Error-Fix
If you get this error:
**No module named 'impacket.examples.mssqlshell'**

For those that have this issue. Copy the contents of this file:https://github.com/fortra/impacket/blob/master/impacket/examples/mssqlshell.py

Then add a new file in your /home/kali/.local/lib/python3.11/site-packages/impacket/examples folder called mssqlshell.py with the contents from above. that will fix this issue. Saw a few people have this with no fix so here it is.
