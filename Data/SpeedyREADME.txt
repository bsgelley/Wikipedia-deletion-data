This archive file contains a dataset of Wikipedia articles nominated for Speedy Deletion from October - December 2011;
some of these were later deleted and some were not. The set also contains, as a comparison, articles that were not deleted from Wikipedia, 
obtained using Wikipedia's category hierarchy. (For more details, see the accompanying Description.txt file.)
The data is organized as follows: Each day's nominees are contained in a separate folder labeled 'For speedy' followed by the date;
for example, November 9, 2011's nominees are in the folder For speedy 11-09. (Please note that we do not guarantee that we retrieved all nominees 
for each day, as our download interval was large enough that a few may have been missed; some of the earliest dates contain significantly fewer files
than later ones.)

Each subfolder contains a number of files, which represent articles that were nominated for deletion but kept, and a folder called "Deleted", which 
contains all pages nominated for Speedy Deletion on that day and actually deleted. Each "Deleted" folder contains a folder entitled "Good", which
contains the subset of deleted pages which were nominated for deletion for one of the following reasons: "No indication of significance", 
"advertising or promotion", or "no context". (This last category was not used in our experiments documented in the paper, 
so articles belonging to it were later filtered out, but they are included here.) These files were selected by parsing each
file for the deletion reason given in the deletion nomination template on each page. Article talk pages that existed at 
the time of article download are included as well; these are denoted by the word "Talk", followed by an underscore
and the article name. (E.g., "Talk_Computer") 