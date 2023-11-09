# Coding_Assignment_3_Data_Bias
This project is for I310D. For this assignment, I am testing the accuracy of the Perspective API in its ability to identify toxic comments/tweets targeted to males and females. 
The hypothesis that I tested was that Perspective API would be less likely to identify harmful female tweets as toxic than harmful male content.
From my testing, I found that my hypothesis was incorrect. The overall accuracy of the model was 0.84375 which is only 84% which is not great, there is alot of room for error when identifying information. I found that the API better identified harmful female content than male. The API was 62% accurate for identifying toxic tweets for the males, while it was 75% accurate for females. Further explanation and results can be seen in the Coding Assignment 3 notebook. 

Question: When training models and using them as classifiers, how do we avoid unconscious bias that creators of the models may have unintentionally coded into the model?
