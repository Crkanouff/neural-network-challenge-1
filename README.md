# neural-network-challenge-1
Challenge 18
Due March 18, 2024

This goal of this project was to look at student loan refinanceing services and use ML to predict a borrower's likelihood of replaying a loan. I first downloaded and analysed and prepped the data provided. The core of the project was to construct and refine a NN model using TensorFlow. Following the model's compilations, it was trained and evaluated against the test data to determine its efficasy as reflected in its loss and accuracy metrics. 

The model was saved as a Keras file so we could use it to predict loan reapyemnet success using the reserved testing data. This involved reloading the saved model, making predictions on the test dataset and then converting these predictions into binary outcomes for interpretation.  A classification report was generated to provide a detailed evaluation of the model's performance.

More information could be gathered on the students to improve the accuracy of the model, however, this additional information would involve creating solutions for maintainin data privacy and managing a borrower's changing financial and academic status.
