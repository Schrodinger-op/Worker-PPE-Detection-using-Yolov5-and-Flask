# Worker PPE Detection Demo using Yolov5 and Flask

## Folder Structure

models_train-------- pre-trained models
runs_results-------- results folder for training
static-------------- CSS Files and images for frontend
templates----------- index.html
app.py-------------- Flask app
UC-4_Obj_det.ipynp-- Python notebook


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




