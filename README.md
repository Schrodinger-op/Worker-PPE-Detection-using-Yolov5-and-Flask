# Worker PPE Detection Demo using Yolov5 and Flask

## Steps to run the API in Localhost ##

```powershell

pip install -r requirements.txt
python app.py

```
## Steps to run the API using docker ##

1. Install Docker Desktop
2. Build Docker Image
```powershell

docker build . -t flask-yolov5:latest 

```
3. Run Docker Image
```powershell

docker run --rm -it -p 5000:5000 --user=42420:42420 flask-yolov5:latest

```




