**Installing Requirements**
1. Ensure python3 is installed: brew install python3
2. Create venv environment: python3 -m pip install --user virtualenv
3. Enter venv from project root: source venv/bin/activate

** You can also install all requirements already existing in requirements.txt:

Run: pip3 install -r requirements.txt

** Best practice for installing all required packages on new server: virtualenv --no-site-packages --distribute .env && source .env/bin/activate && pip install -r requirements.txt
