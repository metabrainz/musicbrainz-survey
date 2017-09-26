# MusicBrainz User Survey Analysis

This repository contains all the scripts used for processing and analyzing the 
MB user survey.

## SENSITIVE DATA

Both the raw survey responses as well as all files containing "SENSITIVE" in their file name may contain unprocessed user data not intended for public release and are thus .gitignore'd.

Please make sure to not accidentally commit any of those files and to include "SENSITIVE" in the file name should you create new ones containing this kind of data.

The notebook file has also been stripped of all output using `nbstripoutput` but can replicate all other files using the raw survey data.

## Survey data
The files `mb_usersurvey_2017_general.csv` and `mb_usersurvey_2017_demo.csv` respectively contain the processed general survey and demographics data.
