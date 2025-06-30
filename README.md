# Machine Learning Capstone Projects

## Project 1 - The Automated Book Categorization (ABC) Helper 
Data has been uploaded: summaries and titles are included in the data. Data came from multiple sources. 
- Kaggle - all csv files
- Google Books - apis in python file


Please see the following for how data was collected: [Project_1_Python_File](Project_1_Library/16.4%20Collecting_Book_Data.ipynb)

Total Count of Samples: 1,449,541

Upload using LFS objects. Please see LFS code section at the bottom of the page. 


## Project 2 - The Diatom Identifier 
Data has been uploaded: diatom images including annotations and outlines. Data came from multiple sources.
- Kaggle - Diatom folder was downloaded with over 4K samples
- Diatoms.org - Images were manually pulled and relabeled from this website in order to preserve the genus/species of the diatom image.
- Outlines were created by data gatherer for genus types needing more images in order to recognize the overall shape of the diatom. 

Please see the following for how data was collected: [Project_2_Python_File](Project_2_Diatoms/16.4%20Collecting_Diatom_Data.ipynb)

Total Count of Samples: 15,002

Upload using LFS objects. Please see LFS code section at the bottom of the page. 



## Project 3 - Mental Health Predictor
Data has been uploaded: Lifestyle, diagnosis, Answers to mental health questionaires. Data came from multiple csv files, but from the same source. 
- Kaggle - all csv files

Please see the following for how data was collected: [Project_3_Python_File](Project_3_Mental_Health/Project_3_mental_heath.ipynb)

Total Count of Samples: 16,226

Was uploaded normally.


### LSF Code - How was code uploaded? 

`git lfs install`

For Project 1...
`git lfs track "*.csv"`


For Project 2...
`git lfs track "*.jpg"
git lfs track "*.png"`


`git add .gitattributes
git add .
git commit -m "Add batch file(s) with Git LFS"
git push origin main `

