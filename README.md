# CourseProject

Please fork this repository and paste the github link of your fork on Microsoft CMT. Detailed instructions are on Coursera under Week 1: Course Project Overview/Week 9 Activities.


# Running Projects

## Via Python
Open terminal and go to the *backend* folder of this project. From within this project run the following
1. install https://github.com/explosion/spacy-models/releases/download/en_core_web_lg-3.2.0/en_core_web_lg-3.2.0.tar.gz
2. pip3 install -U -r requirements.txt
3. python falconapp.py

In about a minute, you should be able to go to [http://localhost/main](http://localhost/main) and see the site

## Via Docker
The backend is also contained in a docker container and can be ran on your local docker environment or in the cloud on any cloud provider that provides docker (pretty much all of them). The instructions below is just for running the server locally on your computer.

Go to the *backend* folder and run *docker-compose up -d*. In about a minute, you should be able to go to [http://localhost/main](http://localhost/main) and see the site

## Recommender
To use spacy's en_core_web_lg, run the following command:

python3 -m spacy download en_core_web_lg

If this throws a linking error in the end, try:
sudo python3 -m spacy download en_core_web_lg
