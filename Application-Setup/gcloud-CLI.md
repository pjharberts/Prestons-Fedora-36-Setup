# gcloud CLI

## Installation

Open Terminal, and run the following commands to download, unzip, and install Google Cloud CLI:

```
wget https://dl.google.com/dl/cloudsdk/release/google-cloud-sdk.tar.gz
tar -zxvf google-cloud-sdk.tar.gz
sudo mv google-cloud-sdk /usr/share/
bash /usr/share/google-cloud-sdk/install.sh
```

Answer each prompt like below:

```
Do you want to help improve the Google Cloud CLI: n
Do you want to continue (Y/n): y
Enter a path to an rc file to update, or leave blank to use [/root/.bashrc]: Press the Return key
```

Close and open a new instance of Terminal.
## Login and Testing Compute

Run the following commands to login and setup a project and compute instance:

```
gcloud auth login
gcloud auth login --project=PROJECT_ID
gcloud config set project PROJECT_ID
gcloud compute instances list
gcloud compute instances start INSTANCE_NAME
gcloud compute ssh USERNAME@INSTANCE_NAME
```

Quit the SSH session with Ctrl+D, and run the following command to stop the compute instance:

```
gcloud compute instances stop INSTANCE_NAME
```
