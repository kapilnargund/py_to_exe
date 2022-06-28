# Convert .py files to .exe

> pip install pyinstaller

> make python file

> convert .py file to exe: pyinstaller [filename]

> check .exe file in dist folder

### above steps create an environment with lot of files and folders, hence to pack all in one single .exe file we use:

> pyinstaller --onefile [filename]

> eg: pyinstaller --onefile test.py

### if you do not wish to run a cmd in background when opening a .exe file then we use: (Use test2.py for this step)

> pyinstaller --onefile --windowed [filename]

> eg : pyinstaller --onefile --windowed test2.py

### if you wish to change icon of .exe file: (you might have to change the view in windows to check the icon)

> pyinstaller --onefile --windowed --icon "[icon path]" [filename]

> eg : pyinstaller --onefile --windowed --icon "sample_icon.ico" test2.py

### if you wish to perform all the above tasks with the help of GUI:

> pip install auto-py-to-exe

> auto-py-to-exe