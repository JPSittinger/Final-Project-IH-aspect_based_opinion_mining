# Aspect Based Opinion Mining on Google Reviews

## Key Questions:
- Get an overview of the development of 1-5 star reviews over time
- Besides just the count, I want to know what exactly is bad and what’s good
- Overview over the key aspects that need to be improve to get better reviews


### Step 1: Scraping Google Review Data
In the Jupyter Notebook files, you'll find the "Google Review Webscraping" file. This is specific to german browser settings. The file can be easily and quickly be changed to work for other languages. 
You can input the link and automatically get the reviews from the location you're interested in. By using the parameter "/10 - 1", you can choose to scroll down to the very first review. If your browser can't handle this many requests, leave it at a higher number.

### Step 2: Aspect Based Opinion Mining
In the same folder, you'll find the notebook for the Aspect Based Opinion Mining. It automatically cleans and prepares the text from the Google Reviews, outputting a .json file in the process with all the aspects and their semantics.
It will further create a dataframe with the count of each aspect. 
Careful: I combined those aspects even further manually since some topics that occured more often could be counted as e.g. "Customer Service", etc. This needs to be adjusted based on the input data and the location of interested.
