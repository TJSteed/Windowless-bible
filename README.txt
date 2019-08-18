how to install this application. V1 "Ecclesiasticus" sirach

in order to run this proram you must first install python.
go to this link to install python for windows 64 bit.
https://www.python.org/ftp/python/3.7.4/python-3.7.4-amd64.exe

save run and install python and check add python to path during install.

then install pyinstaller for windows with cmd or powershell as admin with the following command.

pip install pyinstaller


now download Ecclesiasticus.py from this repository.

open a powershell or cmd and change directory to the folder of Ecclesiasticus.py

type the followig command

pyinstaller --onefile -w Ecclesiasticus.py

this command will convert the python file to a windows executable.

the executable file is located in the "dist" folder at the location of ecclesiasticus.py file.

copy ecclesiasticus.exe out of dist and delete all of the other new files created from that command- they are no longer needed.

if this does not work you may have to install visual C++ redistributable: https://support.microsoft.com/en-ca/help/2977003/the-latest-supported-visual-c-downloads
then retry

next open file explorer. click view at the top and check off show hidden items.

next save ecclesiasticus.exe to C:\users\'your username'\appdata\roaming\microsoft\windows\start menu\programs\startup\

next enable task bar resizing in the windows settings menu.

double the thickness of your task bar by dragging and dropping it to desired size.

now restart your pc and the bible book ecclesiasticus will be displayed verse by verse on your windows taskbar unobtrusivly.

enjoy this book as you use your computer splitting glances between work and word.

after people become interested in the prject  will add more bible books or add a customization file and an acompanying reade.txt file so that you can program any book of your choosing to be displayed unobtrusivly, windowlessly on your taskbar.

this is great if you would like to study the bible or any book while working or using a pac.

God bless and enjoy.

enjoy the book while using your computer.

if you want to prevent the book from starting at start up of your pc simple go to your start up folder located here> C:\users\'your username'\appdata\roaming\microsoft\windows\start menu\programs\startup\
and move ecclesiasticus.exe out of the folder.

