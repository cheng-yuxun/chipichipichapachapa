# chipichipichapachapa

a passion coding side project which I've wrote a python script that runs tiktok's viral chipi chipi chapa chapa cat video on youtube and converted the python script to an executable file.

Setting Up Environment & Creating .exe File:
```
python -m venv .venv (for Windows) / python3 -m venv .venv (for macOS)
.venv\scripts\activate (for Windows) / source .venv/bin/activate (for macOS)
pip install -r requirements.txt
PyInstaller --onefile chipichipichapachapa.py
```

With PyInstaller, an .exe file of the python script will be created under dist folder.