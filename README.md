### Welcome to Kim's Text Classification and Gradio App

where we use Sklearn and Gradio.

#### Overview

Showcasing Python, Pandas, Sklearn, and Gradio, the challenge reads the contents of a csv into a dataframe.

It creates sms_classification function that splits the data into training and test, creates a model pipeline with TfidfVectorizer and English stopwords and LinearSVC, and fits the training data. The method returns the model.

A model is created by passing the dataframe into the function.

A second function sms_prediction is created that takes in text and uses the model from the first function to predict whether the text is spam or not spam.

A gradio app is created that passes in the prediction function and has one input and output textbox with the ability to copy the output.

The app is launched with share set to True so that a public URL is created.

#### Program

    └───root
        └───Assets
            │   message_1.png
            │   message_2.png
            │   message_3.png
            └───message_4.png
        └───Resources
            └───SMSSpamCollection.csv
        │   gradio_sms_text_classification.ipynb
        │   README.md
        └───sms_text_classification_solution.ipynb

Step 1:

Navigate to the "gradio_sms_text_classification.ipynb" file in GitHub repo. The output for each panel can be viewed in the "Preview" panel.

Alternatively,

Step 1:

Clone the repository.

Step 2:

Go to Google Colab

Step 3:

File upload

Step 4:

Select "gradio_sms_text_classification.ipynb".

Step 5:

Under "Runtime", select "Run All".

Step 6:

Scroll to the bottom of the file. A public URL is listed. While the app is still running, paste the URL in a web browers. Input text messages and review output. Four text messages are supplied at the bottom of the file.

#### Screenshots

![screenshot](Assets/message_1.png)
![screenshot](Assets/message_2.png)
![screenshot](Assets/message_3.png)
![screenshot](Assets/message_4.png)

#### Resources

The data was supplied as starter code by ASU edX Boot Camps, LLC.
