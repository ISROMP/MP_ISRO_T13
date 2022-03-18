# Steps for installation of XSM interpreter
- Clone the Repository
- Run the 
```
pip3 install -r requirements.txt
``` 
in the directory.
- Execute 
```
python3 main.py
```
# build
- Install PyInstaller
- run
```
PyInstaller --one-file main.py
```
- The built version will be in /dist directory.
# standalone
Run 
'''
./main
'''
The standalone file(main) will be sent through email.
(NOTE: The version here is built on mac and hence may not run on linux distros)
