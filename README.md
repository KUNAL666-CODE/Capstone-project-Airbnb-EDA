# Capstone-project-Airbnb-EDA
Airbnb is an online platform where one can book accommodation online in various parts of the world ,it also publishes ratings on its platform given by its customers,in this project we have a dataset which consists of all the booking information about the hosts who have listed their properties on Airbnb and EDA has been done over that project 

## **Introduction**


Airbnb has been a revolutionary technology driven company providing travellers accomodation while travelling at their finger tips ,they can book any accomodation online and it also provides its customers various options to review their stay after they checkout and share their feedback on its app and website. Our aim is to evaluate the dataset provided and derive conclusion and try to identify various trends which would help to take better decisions in respect of expanding the business and learn about various security concerns if any.


               
![airbnb 2](https://user-images.githubusercontent.com/127510355/228187933-01e5da15-1b03-44ca-934d-40f0322be58e.jpg)
### **Description of the Dataset columns**


![EDA_Air_Bnb_Bookings_Analysis_73e51f569a](https://user-images.githubusercontent.com/127510355/228478742-363ac3e0-92e7-4f63-ab17-9e98977734f7.png)

The above dataset consists mainly of the listing location ,reviews and the owner name and owner id of the listing and pricing as given above in the description box.

#### **Project Architecture**


![airbnb_98e86757bb](https://user-images.githubusercontent.com/127510355/230594069-86ad5044-67b0-44af-ac64-d666a552a451.png)

The project architecture explains the flow in which the analysis was carried out ,the process for forming insights and formulating conclusions and learnings which would 
help the stakeholders to expand their business.

## How is the analysis carried out

* First of all the data has been cleaned and null values has either been dropped or filled with zeros.
* After this data wrangling has been carried out on the data set so that the data becomes more clearer.
* The data visualization of the dataset to make the picture more clearer and in order form insights has been carried out.
* Various plots used for univariate,bivariate and multivariate analysis are bar plot,swarm plot,boxen plot,pie chart,heat map and lmplot to show the relations between various variables were used .

![download](https://user-images.githubusercontent.com/127510355/230598356-4df38dd2-3e6a-4ef7-add6-134a55f8669b.png)

The above bar plot shows the three most expensive neighbourhood group


![download (1)](https://user-images.githubusercontent.com/127510355/230599668-d709ffbc-2434-4e9c-9538-386b886a2faa.png)


The above pie chart shows Revenue generation from various neighbourhood .

![download (2)](https://user-images.githubusercontent.com/127510355/230600289-fa13e3ab-9207-48e1-8d8a-e6166e86cab6.png)

Heatmap works on the priciple of relativity it has two concepts positive relativity and negative relativity positive relativity means when one variable increases other also increases whereas negative relativity means when one variable increase other decreases Also relativity closer to zero have very less relativity and relativity closer to 1 and -1 has more relativity. In the above heatmap every number shows relativity across various columns of the datasets Here we can see that reviews_per_month and number_of_reviews are positively relative and their relativity count is 0.59

##  **Conclusion and solution to business objective**

After analysing the dataset it is evident that people mostly prefer private home or private apartment so the company should focus more on promoting them ,although room sharing is an affordable option,people give priority to privacy. Secondly the company could offer discounts and promotional codes on less revenue generating localities which are Bronx ,Staten Islands and Queens,to promote them and increase listing from these localities. Pricing threshold is 4000 above this price there are very few bookings,people prefer paying around this price.
