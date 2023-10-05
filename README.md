# Bedrock Samples

## Installing the environment

Running the commands in the repo root:

```bash
python3.11 -m venv venv
. venv/bin/activate.fish
pip install notebook
pip install -U boto3
pip install black
pip install "black[jupyter]"
pip install polars
```

## Running the notebooks

```bash
jupyter notebook
```

## Setup

Change _your-profile-here_ inside the notebooks for a valid AWS profile to use as authentication. 
As an alternative you can hardcode your credentials (not recommended)

Make sure you request access to the models you wish to test here:  
https://us-east-1.console.aws.amazon.com/bedrock/home?region=us-east-1#/modelaccess