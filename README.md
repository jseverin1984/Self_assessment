# Individual Self Assessment

## Self Assessment

As we started on our group project, nobody had any idea what role(s) each of us would be fulfilling.  As the project progressed past the data collection,
it started to become clear that I was most comfortable and best suited working with the data.  I dove into wrangling the data so it could be merged together
from our different sources and become compatible for our machine learning model.  I thoroughly enjoyed developing the code to run our ARIMA machine learning
model over our data sets. We needed to run the model on each city in our data, and we had 381 cities per data set that our model had to make predictions
with. So developing a for loop was a fun and exciting challenge. I also developed a couple python scripts so that a teammate would just have to load the proper
data set and hit run, and the script would wrangle the data, run the model, create a new column for predictions in the original dataframe, make calculations
on the rate of change for that prediction, rank the predictions and finally load the newly formed dataset into our non-relational database.

I was available to teammates 24/7 for help, discussion, or feedback on the parts of the project I did not work directly with.  I collaborated and helped with
building the web app and developing the order and content of the presentation. My biggest personal challenge was having to start over and build a new machine
learning model and scripts. I had spent many hours using linear regression, not knowing I should not have used it on time series data, to run predictions on all
of our data, then run error calculations and push it all to our database. Just to find out it all had to be trashed and start over from the beginning with a new
model. This was mentally devastating, but with the encouragement of my teammates and dedicating myself to learning a new machine learning model, we were able to 
re-write all of the code for our predictions of the data.

## Team Assessment

We came together and meshed quickly as a team.  Right from the beginning we trusted each other and found our strengths and weaknesses. We created a Google doc
in order to let each other know what we wanted to work on, what we were good at and what we were not strong in. Once we had it all out in the open, we were able
to assign tasks to each teammate effectively without anyone being overwhelmed or felt like too big of a burden was placed on their shoulders.  We created a new
discord channel for open  and free communication at anytime of the day.  We tracked our progress through a google doc and a Trello board. The only thing we should
have done differently was seek out more advice about time series machine learning models instead of just assuming we understood enough about them to dive right
making our predictions. 

Our greatest strength as a team was our ability to be honest with each other. Especially when it came to our strengths and weaknesses as individuals.  Also, everyone
was incredibly positive and uplifting with each other. Even when someone made a mistake or fell behind. We rallied behind each other with encouragement and offered
helped whenever it was needed or wanted.  I would share with a new cohort that you should always make it a point to reach out to someone on your team and let them
know how good of a job they are doing and congratulate them for any small victory or piece of the project they completed. No matter how small it may seem, when someone
receives that level of appreciation and encouragement, it only makes them want to work harder and be there for everyone.

## Summary of project

Our team wanted to develop a pipeline that would help forecast which cities in the United States would be considered emerging cities in the year 2024 and display
our findings to a client. This client could be into real estate and wanting to know where they can buy cheap and sell high in a few years, smaller businesses
wanting to expand into new areas, or just a family wanting to find a new place to move to. We gathered relevant historical data from federal websites and used
the machine learning model ARIMA to forecast what these numbers would look like in 2024 for 381 Metropolitan Statistical Areas (MSA's). With this data, we ranked
the MSA's and developed a dynamic web app to present our client with our findings. Feel free to visit [MetroGnomics],(http://msa-prediction.herokuapp.com/index?mode=dark)
our fully developed web app.