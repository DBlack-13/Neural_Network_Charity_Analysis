# Neural_Network_Charity_Analysis

## Overview of Analysis:
With my new knowledge of machine learning and neural networks, I use the features in the provided dataset to help Beks create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.  From Alphabet Soup’s business team, Beks received a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. With that we can process the data for a neural network in which we can then compile, train, and evaluate the model to find optimal results.

## Results:
  - Data Processing:
    - The variable that is considered the target for this model would be the column name "IS SUCCESSFUL." The reason this was picked is because that is the purpose of what we are trying to solve for, wether or not applicants will be successful if funded by Alphabet Soup.
    - The variables that are considered features of this model would be all the other column names.
    - The variables that were removed from this model were columns named: EIN and NAME. The reason being is because the challenge told us to but also it makes sense as they do not have a relevency in executing this analysis.
    
  - Compiling, Training, and Evaluating the Model:
    - How many neurons, layers, and activation functions did you select for your neural network model, and why?
    
I used the same model from the challenge to first see if I can alter it and make it better by adding a call back save frequency of 100, just to see if adding more runs would make a difference. Turns out that it didn't and resulted in a 46.6 accuracy rating.
    
![Atmp_1 1](https://user-images.githubusercontent.com/106560752/201124629-437bfa7b-6b69-45da-b299-9e39e1af4d6b.png)
![Atmp_1 2](https://user-images.githubusercontent.com/106560752/201124645-27bfe122-4196-49e3-9b11-06ca82b4e201.png)
![Atmp_1 3](https://user-images.githubusercontent.com/106560752/201124699-b52314b9-7e0f-415a-9412-b595ebb4243e.png)

My second attempt I altered the outer layer by increasing the units to 5 and but also reducing the save frequency down to 50 percent. It resulted in a lower score of 43.8

![Atmp_2 1](https://user-images.githubusercontent.com/106560752/201127576-ecc7854c-9656-499e-b7b9-347326a15951.png)
![Atmp_2 2](https://user-images.githubusercontent.com/106560752/201127636-6366b286-200e-4b7f-b84f-992188bc4e80.png)
![Atmp_2 3](https://user-images.githubusercontent.com/106560752/201127695-93269a9b-cf76-483a-b34e-4f97efee8c8e.png)

 My third attempt I went back to the orignal format and altered the epoch train to see if that would increase the original results. That too failed and put me at 46.68
    
![Atmp_3 1](https://user-images.githubusercontent.com/106560752/201128498-bd1c925d-6364-45d0-9e6f-65fb6c5c4c8a.png)
![Atmp_3 2](https://user-images.githubusercontent.com/106560752/201128605-7831e0dd-c10a-4142-89df-90fcacca74e9.png)
![Atmp_3 3](https://user-images.githubusercontent.com/106560752/201128683-d27bd243-b690-4faa-9467-d27220199b05.png)

## Summary
Over all our change the original model failed, resulting in lower accuraccies accross the board. We could run hundreds of various alterations to get the outcome that we are looking. We could have removed more features to help simplify the data or we could have gathered more data to help strenghten the accuracy. 

