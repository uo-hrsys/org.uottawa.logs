org.uottawa.logs
================

Allows to log every call of the DITA-OT for each transtype in a log directory.

This plugin is usefull if you want to document the DITA-OT useage.
it creates a logs diretory at the root of the DITA-OT installation, then one subdiretory per transtype called

logs
logs/pdf
logs/html5

Then it create one texte file per day.

ls would return

pdf-20120621.log
pdf-20120620.log
pdf-20120619.log
...

Using wc -l in the directory of your choice will return the number of lines per file and 
the total count of the lines (one line = 1 call)

You can concatenate files and analyse the file in Excel because there are output as csv.
