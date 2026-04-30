# Practice
sudo apt install unzip 
Install aws cli on your machine
create access keys
aws configure
# just incase it does it install normal with sudo apt update and sudo apt install awscli use below commands
cd /tmp

curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip"

unzip awscliv2.zip

sudo ./aws/install
git init
git branch -m main 
uv init
uv venv
activate the venv (source .venv/bin/activate)
uv add dvc dvc_s3 (main to run but )
# different options to install dvc dependencies
uv pip install dvc/ sudo snap install dvc --classic/ sudo apt update
sudo apt install dvc
dvc init 
dvc add data/wine_data.csv
# notice a wine_data.csv.dvc file will be created
cat wine_data.csv.dvc
vi or edit the wine_data.csv file and save it
git add data/.gitignore data/wine_data.csv.dvc
dvc add data/wine_data.csv
cat data/wine_data.csv.dvc
# compare before and after the md5 value will change

# Create an s3 bucket let the same is demo-bucket
dvc remote add -d winedata s3://my-dvc-project-bucket
# To check dvc list on s3 bucket 
dvc remote list
aws configure
# get the keys and configure it
dvc push
# check the data in s3

# Note below:

activate the venv - you'll need to use the appropriate command for your OS (e.g., source venv/bin/activate on Linux/macOS or venv/Scripts/activate on Windows)

vi or edit - replace with your preferred editor command (e.g., nano, vim, code)