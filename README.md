# natl-park-spp
BIODIVERSITY CAPSTONE PROJECT - INVESTIGATING PROTECTED SPECIES
CodeAcademy Capstone Project - Species Diversity in National Parks

Part 1- Biodiversity Project
Welcome to the Introduction to Data Analysis Biodiversity Capstone project!

You are a biodiversity analyst working for the National Parks Service. You have been given a CSV file species_info.csv with data about different species in our National Parks, including:

The scientific name of each species
The common names of each species
The species conservation status 

(CSV data based on data from the National Parks Service.)
The National Parks Service would like you to perform some data analysis on the conservation statuses of these species and to investigate if there are any patterns or themes to the types of species that become endangered. During this project, you will analyze, clean up, and plot data, pose questions and seek to answer them in a meaning way.

Let’s get started!


Part 2- In Search of Sheep
A team of ruminant-enthused scientists has been tracking the movements of various species of sheep across different national parks and have asked for your assistance in analyzing the observation and species DataFrames to help track sheep locations.

Because the observation DataFrame only contains the scientific names of species, you will have to use the species DataFrame to look for any names that refer to sheep.

The following code will tell us whether or not a word, such as “sheep”, occurs in a string:

>>> # Does "Sheep" occur in this string?
>>> str1 = 'This string contains Sheep, baa'
>>> 'Sheep' in str1

True
>>>  # Does "Sheep" occur in this string?
>>> str2 = 'This string contains Cows, moo'
>>> 'Sheep' in str2

False
