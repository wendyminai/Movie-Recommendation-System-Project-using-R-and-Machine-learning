# Movie-Recommender-System
A Web Base user-item Movie Recommendation Engine using Collaborative Filtering By matrix factorizations algorithm and
The recommendation based on the underlying idea that is if two persons both liked certian common movies,then the movies that one person has liked that the other person has not yet watched can be recommended to him.   

###### Home page
![Uploading Screen Shot 2022-12-18 at 12.20.18 PM.png…]()

###### Recommendation page
<img width="1347" alt="Screen Shot 2022-12-18 at 12 29 21 PM" src="https://user-images.githubusercontent.com/111389636/208313586-bd67cab1-7a4e-4d8e-8ccb-6af3371ac617.png">


###### Rating page
<img width="1347" alt="Screen Shot 2022-12-18 at 12 29 21 PM" src="https://user-images.githubusercontent.com/111389636/208313492-e332edfa-ba54-41c8-99de-4431aef29cc2.png">


### Technologies Used

#### Web Technologies
Html , Css , JavaScript , Bootstrap , Django

#### Machine Learning Library In Python3
Numpy , Pandas , Scipy

#### Database
SQLite

##### Requirements
```
python 3.6

pip3

virtualenv
```
##### Setup to run

Extract zip file in your computer

Open terminal/cmd promt

Goto that Path

Example

```
cd ~/Destop/Movie-Recommender-System
```
Create a new virtual environment on that directory

```
virtualenv .
```

Activate Your Virtual Environment

for Linux
```
source bin/activate
```
for Windows
```
cd Scripts
then
activate
```
To install Dependencies

```
pip install -r requirements.txt
```

### Creating Local Server

Goto src directory, example

```
cd ../Movie-Recommender-System/src
```
To run
```
python manage.py runserver
```
Now open your browser and go to this address
```
http://127.0.0.1:8000
```
Thank you for visiting my repository.
