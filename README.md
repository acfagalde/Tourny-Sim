This program alls you to simulate a tournament for the Flesh and Blood card game. It takes input data from the Input Data.xlsx file such as hero counts, player amount, and number of rounds. This is meant to be run repeatedly to account for variance, with the only required change between runs is updating the "Sheet Name" value cell in the above Input Data.xlsx folder so that your new data will be stored in a new page.

All 3 excel files included must be in the same folder as the code you are running and you must have permissions to write/save to that file.

The information for matchup winrates is stored in the file Talishar Meta Data.xlsx This information can be manually edited, but will be updated with new data as it becomes avaiable. Data in the cells can be manipualted, but if you move the cells you will not get the results you want.

The information after running the program will be exported to Calculator Export.xlsx This file will give you all players within the top 64, ranked including tiebreakers. It will also include a count of which hereoes are included in that top 64 and how many.

The zip file contains all necessary files and an executeable version of the python script for ease of use.

All files are currently contained within the second branch with an open pull request. 
