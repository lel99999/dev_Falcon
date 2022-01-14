# dev_Falcon
Falcon REST Development

##### Since Falcon doesn't include an HTTP server, we need to add guincorn
```
$python3 -m venv falconapi_dev
$source falconapi/bin/activate
$pip3 install falcon gunicorn

#run falconapi.py
$gunicorn falconapi:api
```


