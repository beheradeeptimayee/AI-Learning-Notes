- Supervised Learning are those where the models learns from the labeled data.

- labeled data: Inputs & Outputs exist and they are in a well structured manner.

 #### In Mathematical terms,

                          y=f(x)
where y=output,x=input 
f(x)=this is  stored in the training model,which is used for predictions.


###  For example:
###  Email Spam Detection
------------------------
### Input:
 Information about  the email.

### Features:
The useful characteristics extracted from the email such as :email text,sender email,whether it contains a link,number of exclamation marks.

### OUtput:
Spam /Not Spam


Email Message| Link| Exclamation Marks| Label
"Win a brand new phone!"| Yes| 2| Spam
"Please find the attached report."| No| 0| Not Spam

- When a new email arrives :
New Email-->Extract Features(x)-->Trained Model(f(x))-->Prediction(y)

Labeled Data-->Training-->Model learns(f(x))-->New Input-->Model-->Prediction
