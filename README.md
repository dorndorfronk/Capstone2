# Predicting Hotel Booking Cancellation

* While hotel reservations are user-friendly, they don't require commitment from the customer and potentially drive revenue-loss when the customer has the chance to book elsewhere. Canceling hotel bookings for free forces the hotel to quickly find a replacement customer, which could result in a lower price for that room or loss of sale altogether.

* Using a publicly-available dataset from Kaggle.com, which includes hotel guest reservation information over three years, I created two predictive models using Random Forest and Decision Tree model types to predict if a customer will cancel a booking with the highest accuracy being 90%. Predicting customer behavior is paramount to understanding demand and customer needs and the use of these models could increase hotel revenue rates as hotel cancellations potentially decrease.

## ![image](https://live.staticflickr.com/1337/5167872392_6bf0508a2e_b.jpg)

## Business understanding
* "[Hotel] cancellations negatively affect forecasting and controls, the two fundamental elements of revenue management" (Zvi Schwartz, 2021). Zvi, a professor at the University of Boston, drives at the main concept here that being cancelled reservations can impact the most critical aspects of managing a hotel. Being able to predict or forecast their behavior, such as whether the hotel reservation will be cancelled, is at the heart of what this project aims to address through predicting modeling. Decreasing reservations by better predicting and serving the customers will increase revenue for the hotel business.

## Data Understanding
* The data was selected since it encompasses three years of recent hotel reservation data including valuable metrics such as if the customer ultimately cancelled, number of people reserving, the lead time prior to the actual booking, etc. These variables are very well suited for this modeling because most are already numeric values that will be used in the models.

## Modeling and Evaluation
* I started by creating a Random Forest model using almost all of the variables present other than Booking_ID for example. The initial model performed extremely well with an accuracy rate of 90%, which was the best model I created. I tried using GridSearch to optimize my model further but that degraded performance so the 90% accuracy rate remained the greatest. The second model type I used was a Decision Tree but that had a lower accuracy rate by about 2% than the initial Random Forest.

## Conclusion
* I suggest this model be used to predict if a customer will cancel a booking based on what the model suggests. For example, if many customers booked in a very similar time of the year, number of children, room size and parking accomodation, it would be likely that new customer would cancelled or not based on the precedence set by previous guests. The model is very fitting for this application as the vast majority of customers are unique so it has a great point of reference with over 36k bookings collectively over the three year span of the dataset.

## Repository Navigation
* Below are the links to the major content of this repository. The repository link will take you to the repo in general, the Jupyter Notebook contains all code in the notebook for this project and the presentation includes a simplistic and very general summary of the content.
* Link to this repository: https://github.com/dorndorfronk/Capstone2
* Link to [Jupyter Notebook](./CapstoneNotebook.ipynb)
* Link to [Presentation](./Predicting Hotel Cancellation.pptx)

## Reproducibility
* Please use these steps to clone my repository which includes the dataset in the parent directory as well as all code used in the Jupyter Notebook. The data can be downloaded from Kaggle.com manually from here: https://www.kaggle.com/datasets/ahsan81/hotel-reservations-classification-dataset. These steps assume the user is operating Windows 10 or later but Git and Jupyter Notebook can be used on other operating systems including MacOS and Linux.
* 1. Install and setup Git Bash: https://git-scm.com/download/win
* 2. Install and setup Jupyter notebook: https://jupyter.org/install
* 3. Configure learning environment: https://towardsdatascience.com/creating-and-using-virtual-environment-on-jupyter-notebook-with-python-db3f5afdd56a
* 4. Clone repository: https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository
* 5. Activate your learning environment and navitgate to the cloned repository and type "jupyter notebook" to launch the notebook. 
* 6. Click "Run All" to run the entire notebook at once.

## Credits and References
* Hotel header image: https://live.staticflickr.com/1337/5167872392_6bf0508a2e_b.jpg
* Zvi Schwartz, Boston University: https://www.bu.edu/bhr/2021/06/29/consumers-vs-revenue-managers-the-case-of-cancelations-and-no-shows/
