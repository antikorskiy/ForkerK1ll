# MalWare.Win.ForkerK1ll.A (ForkerKill/ForkerK1ll)

SECURITY WARNING! THIS IS A DEMONSTRATION MALWARE PROGRAM! FOR EDUCATIONAL PURPOSES ONLY; DO NOT RUN IT ON A REAL PC—USE A VIRTUAL MACHINE!!!

A piece of malware created using Batch, designed exclusively for Windows.

First, it collects information about the victim and sends it to a recipient (an IP grabber or your own website) via the User-Agent header.

Second, it proceeds to terminate Task Manager (Taskmgr.exe) and Windows Explorer (explorer.exe), launches MS Paint (mspaint) and the Command Prompt (CMD), and creates messages and files on the desktop.

Set the data receiver URL in the file, line 61(https://your-logger-or-IP-grabber.xyz).

Save in UTF-8(No BOM).