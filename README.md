# BeaverRecon
The tool is finally decently stable if theres any errors please open a issue

Current Version: 0.7.9

## Installing
The tool runs on windows and linux 

### Linux

#### Debian Based
```
git clone https://github.com/Cat-Linux/BeaverRecon.git
cd BeaverRecon
chmod +x install.sh && ./install.sh
python3 BeaverRecon.py
```

#### Redhat Based
```
sudo yum update -y && yum upgrade -y
sudo yum install git curl python3 python3-pip -y
git clone https://github.com/Cat-Linux/BeaverRecon.git
cd BeaverRecon
python3 -m pip install -r requirements.txt
python3 BeaverRecon.py
```
#### Termux
```
pkg update  && pkg upgrade
pkg install git curl python
git clone https://github.com/Cat-Linux/BeaverRecon.git
cd BeaverRecon
pip install -r requirements.txt
python BeaverRecon.py
```

### Windows 10
PS: you need winrar installed for this other wise you can just do this manually

Download the latest python version from here: https://www.python.org/

make sure to add python to path

then run this in cmd or powershell

```
curl https://codeload.github.com/cat-linux/beaverrecon/zip/master -O -J -L
set path="C:\Program Files\WinRAR\";%path%
winrar x beaverrecon-master.zip
timeout /T 2 && cd beaverrecon-master && python -m pip install -r requirements.txt --user
python BeaverRecon.py
```


## About
This tool is unfinished so expect there to be common errors lol

BeaverRecon is a person OSINT tool that scrapes sites for information

### Tools
❌ - Down 
✅ - Up and Fully Implemented 
☑️ - Up But Not Fully Implemented
⚠️ - Yet To Be Added

- ✅ - http://ip-api.com/json/
- ✅ - http://instagram.com/
- ✅ - https://thatsthem.com/
- ✅ - http://scylla.sh/
- ✅ - https://emailrep.io/
- ❌ - http://hashes.org/
- ✅ - http://haveibeenpwned.com/
- ✅ - https://pwndb2am4tzkvold.onion.ws
- ✅ - http://validnumber.com
- ✅ - http://telnyx.com
