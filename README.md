# How to deploy
Enable venv for your project and install initial dependencies:

####Install pip:

sudo apt install python3-pip

####Install virtualenv:

sudo pip3 install virtualenv

####Create a new virtualenv:

virtualenv venv

####Activate virtualenv:

source venv/bin/activate

####Upgrade pip:
pip3 install --upgrade pip

####Install project requirements:
pip install -r requirements.txt


####Running in Production:
export FLASK_ENV=production

####Upload Rohingya Data
* Run command: python datastore.py --dir {directory_path}
* Example: python datastore.py --dir /home/tarango/Workspace/rdata

####Sample Response
Directory:  /home/tarango/Workspace/rdata

Total Data Uploaded: 1

Total time taken: 0.009127140045166016 seconds


####Upload Rohingya Fingerprint
* Run command: python fingerprint.py --dir {directory_path}

* Example: python fingerprint.py --dir /home/tarango/Workspace/rdata


####Upload Rohingya Photo to Minio
* Minio configuration is saved in minio_config.py [Update the file if needed]

* Run command: python image_store_minio.py --dir {directory path} --minio_ip {ip_address} --minio_access {minio access key} --minio_secret {minio secret key}

* Note: ip_address, minio access key and minio secret key are optional. If not given then those are read from the config file
