####################################################################################
# For validation of data alignmnets between [GPIO neural data , arduino behavioral data , camera locomotion data]

Use ka_Ca_Imaging environmnet (script: Ka_Step_5_Analysis_Correlations_WholeSession_Ca_Event_Rate.ipynb)

[Example: DS12-S6, P5-5]
####################################################################################

# Confirming alignment using infared port activities throught the session.  

(Left)
Infrared port activities from [previously already aligned GIPO] is matching perfectly with the newly aligned [overhead camera locomotion] data for the whole session.
The bottom shows that we have consistent alignment even when zooming at different time point througout the session.

(Right)
A whole session cross-correlation analysis using infarared activites from GIPO and overhead camera.  The correlation peaks at bin 0, further demonstrating proper data alignment. 
![Fig_v_1](https://github.com/user-attachments/assets/e33eb103-55fc-4425-bce1-7b9f696a422c)

####################################################################################
#  First look at brain cell activities and overhead camera locomotion activities 

(Left)
Example fluorescent activities from brain cells 

(Middle)
Fluroescent activities throughout the session 

(Right) 
Overhead camera locomotion showing that majority of locommotion activities is highest when the mice is 
  1. moving to respond to a side cue (left/ right)
  2. moving from side cue back to middle port to retrieve a reward

![Fig_v_2](https://github.com/user-attachments/assets/88c53ca5-0bce-41bc-89be-0af6975f1045)

####################################################################################
# Three example brain cells showing that the magnitude of fluorscent activities are related to locomotion.  


![Fig_v_3](https://github.com/user-attachments/assets/993900b3-8024-4fee-8849-c8c349932d06)

####################################################################################
# Neural activites preceeds locomotion by about 400 ms 

We can either look at the overall magnitude of fluroscent signal (Left) or  only when a fluroscent event occurs (Right).  
All 29 of our cells were positively correlated with locomtoin (Top).  Cross-correaltion analysis showed that that averaged cell activities precedes locomotion by about 400 ms (4 bins @ 100ms per bin).


![Fig_v_4](https://github.com/user-attachments/assets/d8520a1f-a80e-4924-9d14-37ccaec86b40)
