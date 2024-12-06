For this script, modify file_path to your specific file path. I have the "/content/ placeholder for use w/in a Google Colab runtime file for simple and quick use. 
- The script also exports to this destination by default.

## Goal: Identify duplicates in the file 
1. I'm working off a single column "Names" - for my use case I wanted to know what the dups were, not just remove them from the list.

2. Remove the duplicates and create a "clean" file.

3. Write new files to my file destination - one that has the clean .csv file and the other that lists the names that were duplicated.

> Note: I'm using keep='first' b/c I don't want to totally remove the duplicates, I just want to remove all of the identical names after I have found one instance of it.

Pandas documentation on the drop_duplicated method here: https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.drop_duplicates.html
