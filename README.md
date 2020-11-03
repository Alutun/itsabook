# LET'S WRITE A BOOK TOGETHER

## GOAL : Publish a book

You have to separate roles as following :

Two editors
Four designer
All the rest are writers


Each writer will write on their own branch a new chapter in the Chapter Directory, the chapter will be in a text file, the textfile name will be the chapter title and their name as follow my-chapter-name-alutun.txt

Once written the writer will push is new chapter in his branch


Then designer will pull thoses branches from the writer and format the chapter to look nice.
One the deisgner finish to review, he will push the chapter into the "toPublishBranch"

Then the Editors will work and take the chapters validated by the designer and integrate them in the main story.txt file on the master branch


At the end all the Chapter has been validated by designers and published by editors.

Keep the Master branch clean and tidy, we should see only the Story.txt, chapters files should not be present since they are in other branches only.
