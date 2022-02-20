# ILLINI Datathon 2022
Customer Satisfaction Analysis of AI Chatbot Sydney 
> Jae Hyeok Doo (jdoo2@illinois.edu)
>
> Jeewon Koo (jeewonk2@illinois.edu)
> 
> Jeongwoo Choi (jc22@illinois.edu)
> 
> Jin Ho Lee (jinhohl2@illinois.edu)

## Description
The purpose of this project is to analyze customers' satisfaction while interacting with the AI chatbot Sydney of Synchrony. When customers chat with Synchrony, they first engage with Sydney. Based on the chat transcript and other provided information, out model detremine if customers were dissatisfied with their relationship.

## File Structures
- **Datathon.ipynb**: Includes all data preprocessing methods & models required for customer satisfaction analysis
- **Day2.csv**: Includes data for day2
- **day4.csv**: Includes data for day4
- **day5.csv**: Includes data for day5
- **day6.csv**: Includes data for day6


## Acknowledgement

* We would like to acknowledge Synchrony, Sandia National Labratories, and Statefarm for sponsoring the ILLINI Datathon 2022. We would also like to thank the University of Illinois Statistics Department for hosting the event.


## Youtube Video Link

{link:"https://www.youtube.com/watch?v=Lhalgtnks3M"}

## Model Output
![Alt text](accuracy.PNG?raw=true "Model Final Test Accuracy")

- The final accuracy with INPUT and RESPONSE as input using Logistic Regression Classifier

![Alt text](word_cloud_deflected.PNG?raw=true "Wourd Cloud of INPUT column if CHAT_TYPE = Deflected")

- The Word cloud of text in INPUT column of data with CHAT_TYPE == Deflected

![Alt text](word_cloud_livechat.PNG?raw=true "Wourd Cloud of INPUT column if CHAT_TYPE = LiveChat")

- The Word cloud of text in INPUT column of data with CHAT_TYPE == LiveChat
