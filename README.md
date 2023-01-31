# Keyboard script for linux

## Install

### Installation dependencies

1) Install the required dependency for adding custom PPAs.

```bash
sudo apt install software-properties-common -y
```

2) Then proceed and add the deadsnakes PPA to the APT package manager
sources list as below.

```
sudo add-apt-repository ppa:deadsnakes/ppa
```

3) Install `python3.10`

```
sudo apt install python3.10
```

---

### Setting up a virtual environment

1) Install virtual environment

```
python3.10 -m pip install venv
```

2) Create new virtual environment

```
python3.10 -m venv venv
```

3) Use of createded virtual environment

```
source ./venv/bin/activate
```

4) Set the dependencies needed for the project

```
pip install -r requirements.txt
```

5) Run the script

```
python3.10 main.py
```
