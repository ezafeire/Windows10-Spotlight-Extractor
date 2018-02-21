# Windows10-Spotlight-Extractor
A very simple .bat file that extracts Windows 10 spotlights

Q/A:

Why did you make this?

Whenever I locked my computer Windows 10 had those annoyingly beautiful landscapes and whatnot in the background. I searched for a way to acquire them
but it turned out that Windows 10 saved them in a folder with an obscure name, in a format that could not be opened, along with a gazillion other
files, which were not wallpapers.

How do I run it?

Save it as a .bat, double click it. It should create a folder called "temp" with all the image stuff at C:\Users\%username%\Desktop\temp.

How does it work?

It locates the folder in which the spotlights are saved, scrapes it, converts everything into jpg, throws away the garbage and keeps the beautiful wallpapers.
It also accounts for possible errors such as the directory not existing or a temp folder with other wallpapers in it.

Why a batch file?

No idea.

Known issues:

None.
