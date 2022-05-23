# Tate Data Analyst Technical Test
This is the repository containing instructions and base data for a technical test for analysts 

# Submission

Please return your code and results to mathilde@jolimoi.com .  


Please do not return the database via email (it's quite large!)

# The Data

The data used for this test is sourced from the **Museum of Modern Art data on Kaggle**: https://www.kaggle.com/momanyc/museum-collection

## Content

The artworks data set contains 130,262 records, representing all of the works that have been accessioned into MoMA’s collection and cataloged in our database. It includes basic metadata for each work, including title, artist, date, medium, dimensions, and date acquired by the Museum. Some of these records have incomplete information and are noted as “not curator approved.” The artists dataset contains 15,091 records, representing all the artists who have work in MoMA's collection and have been cataloged in our database. It includes basic metadata for each artist, including name, nationality, gender, birth year, and death year.

## The Database

To make sure that this test can run on any machine, we're using SQLite: https://www.sqlite.org/index.html

We have provided an example Python notebook showing how to connect to, and how to query the database using SQL. 

# The Test!

We'd like you to answer the following questions, using the language of your choice (Python, SQL or R)

If you are comfortable in more than one, please feel free to share one or more solutions in a different language. 

* SQL : Which artist in this data set lived the longest?
* SQL : Who are the top 10 artists by the number of artworks?
* SQL Which artist is created the most artwork by total surface area?
* SQL : Did any artists have artwork acquired during their lifetime?
* Please review the quality of the data, and present any issues
* SQL : Please group the artworks into as many clusters as you feel is appropriate, using attributes from both the artist and artworks tables, and assign each artwork to this new cluster. 

# The test submission

Clear responses using Excel or any other text editor will be accepted or Jupiter Notebook, provided both the response to each question and your workings are demonstrated.

# Good luck!

Thanks to osman.yilmaz@tate.org.uk to have created this test.
