# Web browser using python

## Software to install

```
sudo apt-get install python3-pyqt5
```

## Instructions to run the app

```
python3 -m venv venv

source venv/bin/activate

pip3 install -r requirements.txt

python3 main.py

```

## Create executable file to run the app

```
pip3 install pyinstaller

pyinstaller -D -F -n main -c "main.py"

make it executable file using chmod +x main inside dist folder

Run ./main in dist folder

```

## References

[Stackoverflow link](https://stackoverflow.com/questions/31259856/how-to-create-an-executable-file-for-linux-machine-using-pyinstaller)

[Youtube link](https://www.youtube.com/watch?v=qiPS70TSvBk&ab_channel=Ssj6)