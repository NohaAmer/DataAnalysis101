# fun_with_data

##Resources Needed
- Python
- Text Editor (Let's start with atom)
- It will take around 1 week to publish your first project on Git

##References Used
- dataquest.com (Python Beginner Course)
- Kaggle.com
- GitHub

##Baby steps!

This tutorial acts as an introductory analysis to imdb Data. 

- Step 1: get the data from https://www.kaggle.com/. The data for this tutorial can be accessed via the following link: https://www.kaggle.com/deepmatrix/imdb-5000-movie-dataset
- Step 2: Get Atom (https://atom.io/) that is a text editor to write code
- Step 3: Create a workspace folder and include the following in it: (a) The database from step 1 and (b) The file you will write your code in. Let's call this file "analyze.py"
- Step 4: Run your "analyze.py" file using the command "python analyze.py" from the terminal or command prompt
- Step 5: Data Science fun!
  - (a) Explore your data. Let's be simple and just open it with Excel
  - (b) Determine our objective. I think it is interesting to see which country (column 20) have the highest facebook likes (column 22) based on its movies release
  - (c) Data Cleaning
    - Read the file #open ( ) and read ( )
    - Remove the header #yourList [1:]
    - Split on new line # split()
    - Split on the comma # split()
    - Now, we have a list of lists (Let's call it myList)
    - You can skip the drama of step c by importing csv!
  - (d) Data Analysis
  	- Create a function that takes in the fileName as a parameter for now
    - Create a dictionary #myDic { }
    - loop over every item in myList you created in step 5 (c)
    - If it is available in the dictionary, add it to the current sum
    - If not, add it as a new value 
    - Return the dictionary
  - (e) Making Conclusions:
  	- Based on my results, movies released from Egypt (my home country) have zero facebook likes! Maybe it is time to make some of my own movies and contribute to my country!
- Step 6: More analysis fun
	- Let's write a generic function that can analyze movies based on multiple criteria
	- Simple, let the function take another parameter. The new parameter is the column number that we want to analyze relative to the country!  
