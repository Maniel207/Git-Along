# Journal de bord du projet encadré
## 09/10/26
Today I created a repository on git and am now trying to figure out how to use it while attempting to answer the questions on the exercise sheet provided by the teachers.
It all went without a hitch until I tried to Pull the repository, probably because i only had a vague idea of what that even meant.
I ended up figuring out that "pulling" meant syncing the changes that were made online on my computer, and "pushing" means exporting the changes on my computer to the online git repository.
I also learned that conflicts may exist if there's a discrepancy between the changes on the git online and on the compute.
This is all great, but I still don't know how to pull it off (pun not intended); Everytime i try to pull, i get an error message : stopping at filesystem boundary (GIT_DISCOVERY_ACROSS_FILESYSTEM not set).
After some trial and error i found the problem : i was not in the right directory, I was in the folder that contained it.
It worked after i switched using 'cd' and all the files were updated on my computer.
After I wrote the part above, i used the command git commit -F journal.md, then git push to sync.

## Pipelines
I tried starting with cat *.ann. the result was way too long. I need numbers.
i tried adding wc and i got 3 different numbers. I remember that it was mentioned in class that one was for the number of lines then words and then characters.
next i tried cat *.ann | wc -l in order to get the number of lines only. the result is 24191 which matches the first of the three numbers i got, but i'm not sure how to check that this is right.
I tried cat *.ann | ls *2016* | wc -l to see how many files are from 2016. I got 1143.
Now I'm confused about how I'm supposed to put this result in the text file that i have previously created since it's in an entirely different folder on my computer.
