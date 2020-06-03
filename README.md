# Olaf Official Documentation

After cloning this repository, `cd` into it and run:
```
python3 -m venv venv;
source venv/bin/activate;
pip3 install -r requirements.txt
```

In order to start the development server run:
```
sphinx-autobuild -i ".git/*" -i "venv/*" . _build/html/
```