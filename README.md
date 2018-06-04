# Ada **Lovelace** 

Neural networks for sentiment analysis and phrase classification.

## Installation
#### Docker
You can build the docker image
```bash
cd /path/to/lovelace
docker build -t lovelace .
```

..and then starting a container in interactive mode

```bash
docker container run -it lovelace 
```

#### Downloading dependencies
If you don't download the docker image (recommended) then you can ensure you have the corrected dependencies by running the `requirements.txt`. If going this route, I would recommend a virtualenv or conda env before downloading. 

```bash
cd /path/to/lovelace
pip3 -r requirements.txt
```


### Training the Networks

```bash
python train_mulder.py
```

