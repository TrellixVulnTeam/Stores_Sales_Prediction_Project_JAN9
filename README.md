# Stores_Sales_Prediction_Project
Nowadays, shopping malls and Big Marts keep track of individual item sales data in order to forecast future client demand and adjust inventory management. In a data warehouse, these data stores hold a significant amount of consumer information and particular item details. By mining the data store from the data warehouse, more anomalies and common patterns can be discovered.



#Create a new environment
conda create -p mlenv2 python==3.7 -y
#Activariate conda environment
conda activate mlenv2/ #for command prompt

#or 
conda activate mlenv2/ #for command gitbash
#to create Flask app
pip install-r requirements.txt

#to create new environment
......
conda create -p./mlenv3
.....
#to activate new environment
.......
conda activate ./mlenv3
......
#connecting to Heruku 
heruku id : krishnavizster@gmail.com
heruku API key : <enter_keyfromheroku>
heruku app name:storesalespredectionformall


#Build Docker Image 
....
docker build -t <image_name>:<tagname>.
....
#Note: Image name for Docker must be lower case 
#to list create Docker images
docker images 
# run docker images
dicker run -p 5000:5000 -e PORT=5000 f8c749e73678 
 #to stop docker container
 .....
 docker stop <container_id> #like docker stop e9c3 
 .....

 #to check running container in docker 
 .....
 docker ps
 ..... 
