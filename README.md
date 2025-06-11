## ubotlite Lite
```
apt update && apt upgrade -y && add-apt-repository 'ppa:deadsnakes/ppa' && rm -rf ubot*
```
```
git clone https://github.com/hanzyatim213/ubot.git
```
```
cd ubot && screen -S ubot
```
```
cp sample.env .env && apt install ffmpeg -y && bash installnode.sh
```
```
apt install python3.10 python3.10-venv -y && python3.10 -m venv natz
```
```
natz/bin/pip install -r requirements.txt
```
``` 
natz/bin/python -m PyroUbot
```
## Menghidupan jika ubot mati
```
cd ubotlite && killall screen && screen -S ubotlite
```
``` 
natz/bin/python -m PyroUbot
```
