# CoviDesk HackJaipur MLH  
An application that will allow patients to submit their symptoms and get a **high-quality medical risk assessment** designed with experienced doctors, from the safety of their own homes, without creating additional pressure for our already stretched healthcare workers and crowded hospitals .  
Our idea aims to provide **at-home Covid-19 screenings** via flutter application. We have use computer vision and a symptom scoring system to assess Covid-19 risk and escalate critical patients to doctors virtually .
By uploading a **20-second video of their finger (to check for vital signs like Heart rate and Oxygen rate)** answering some questions about their symptoms and medical condition, patients will be scored using a screening process that will be designed with doctors for the identification of Covid-19.  
Users diagnosied with Covid-19 will then be redirected to top 3 most **optimal nearby hospitals** , we will be able to provide them by considering factors such as: number of COVID-19 tests, number of available beds/ventilators, PPE status, number of COVID-19 patients, type of medical facility(full care, testing only, non-COVID only), nearest possible hospital and weigh the features in an algorithm which then provides optimised hospital for COVID patients  
Based on the symptoms assessed by the app, we haved trained a **supervised learning model to predict the probability of a patient having covid 19** - i.e. risk factor of covid 19. The model has been trained on certain standard symptoms issued by the WHO. For additional precision, we have clustered these symptoms into 2 groups. One which has a high risk factor and one which has a low risk factor. Thus, a labelled dataset is created on which the classifier is trained. By predicting the probability of the person contracting covid 19 through the symptoms, we can get the risk factor  
  
  
**Technolgies used :**    
Flutter - App Development - User-side  
Javascript ,HTML , CSS - Web App  - Admin-side  
Azure - Web App to calculate Heart Rate and Oxygen Level of user : Python , Flask for Api   
Machine Learning  - Calculate Risk Score  



![Screen 1](Screenshot_1592725656.png)![Screen 1](Screenshot_1592741634.png)![Screen 1](Screenshot_1592742421.png)
