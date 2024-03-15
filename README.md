# Sunwoo's Portfolio
Hi! 👋  My name is Sunwoo Kim who is currently majoring in Data Science, minoring in Computer Engineering at the University of California, San Diego!
Here are some projects that I have done so far!

## [Enhancing Utility Pole Monitoring with Computer Vision](https://jcheung4.github.io/DSC180B-Website/)

### Workflow
- User gives two coordinates of interest(start and end of the street). The script will find the unique spots where 360 images were taken in Google Street View and collect images of the street. Then the model will detect each pole within the street through images and compare it with the database(the database in the code is a simple mock database to mock SDGE asset database). Then the script will demonstrate any discrepency between the database and the detection.
  
### Data Collection
- Data collection was done through Google Street View API request and each data is an image of a wooden or steel pole. A set of images is annotated and saved in COCO json format.

### Model Training
- DETR2 was selected for object detection model and finetuned with the collected data.

## [GWAS Database Dashboard](https://public.tableau.com/app/profile/sunwoo.kim1101/viz/GWASDatabaseDashboardPublic/Overview)
### George Lab Database
- George Lab's GWAS experiment is developed through the Azure data warehouse. After the automated data engineering process, the data is uploaded to the combined database
  
### Tableau Visualization
- This visualization allows the researcher to access different values of dependent variables and the distribution of them per database, cohort, and sex. 
Different types of visualization can be accessed by clicking on different buttons on the navigator bar and each visualization allows to filter and investigate specific rats per types of interest and separated by different visual marks such as color and shapes. 
There is the internal version of visualization that is accessible by only permitted users and this visualization is directly connected to the Azure Database. For the researcher outside of the lab who is interested, the nonsynchronous public version is published through Tableau Public and the link is hyperlinked above.

## [2024 Tritonhack Machine Learning Starter Kit Project](https://tritonhacks.github.io/Tritonhack2024-ML-Starter-Kit/)
### Tritonhack
- This starter kit is for students who are participating in a Hackathon event called Tritonhack which is for K-12 students who want to explore further in computer science. This project is to guide students who are interested but new to data science and make them familiar with the setup and workflow of data science projects.
- I was a project lead who managed version control and designed the whole project while managing a team of 4 through weekly meetings.

## [Pole Image Collection using Google Street View API and pole detection using DETR](https://github.com/sunwoo604/streetwatch)
### Image Collections
- Using Google street view API to collect images that can be used to train DETR later on.
  
### Fine-tuning DETR
- Utilizing DETR object detection model to detect overhead distribution structure(pole) in the collected images.


## [Shakespeare Sonnet Autogenerate NLP](https://github.com/sunwoo604/ShakespeareNLP)
### Character Level RNN
-  Divided every string into each character and assigned unique index to each unique character and converted each character into a numeric value.

### Word Level RNN
- Tokenized every string into every word(including punctuation) and assigned a unique index to each unique word and converted each character into a numeric value
- Implemented both single and multilayer RNN

## [UCL Liveboost Visualization for FC Online 4](https://github.com/sunwoo604/FCOnline4_UCL_Liveboost_VIz)
- Web scraped each player's live boost information
- Bracket formatted visualization to show the progress of each team in UCL tournament and each team's logo and game is clickable which allow user to view game results and player's stat
- Geospatial visualization to allow users to view each club's origin country.

## [Read and Category Prediction](https://github.com/sunwoo604/ReadCategoryPrediction)
### Read Prediction
- Used Logistic regression to determine whether user had read or not
- Given input for the prediction was user id and the book id

### Category Prediction
- Tried 2 different ways to predict(creating own featuer vectors and tfidf), and decided to use tfidf
- Convert each review_text to tfidf vector after removing stopword to prevent confusion

## [Court Decision Prediction](https://github.com/sunwoo604/CourtDecisionPrediction)
- Predict if the court favors the complaint or not
- Decision Tree Classifier was used

## [Decision Tree Classifier](https://github.com/sunwoo604/ScratchDecisionTree)
- Conducted Decision Tree from scratch with different uncertainty measurement
- Trained with real life dataset

## [Web VR Environment with Flask Server](https://github.com/sunwoo604/Aframe-Flask_Development_Server)
- Web VR environmet using HTML/A-frame and javascript for the functionality
- Built development server using Flask
