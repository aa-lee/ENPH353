"HOW TO USE GIT"

<!-- Make a folder -->
cd WHEREVER_YOU_WANT
mkdir "NAME_OF_FOLDER"
rmdir "NAME_OF_FOLDER" 

<!-- Go into folder -->
cd where_you_were/NAME_OF_FOLDER

<!-- Put/write code files inside the folder -->
echo "Text" > text.txt
del text.txt

<!-- Initialize Git -->
git init

<!-- Add stuff to be committed -->
git add
git add . <!-- Adds everything in your current directory-->
git rm --cached <file_name> <!-- Removes files from the "to be added pile" -->

git status <!-- Tells you what files are in add + commit + differences? -->

<!-- Make a repo on GitHub from your computer terminal (is this possible?) -->

At this point, you should make a repository on GitHub and copy down the URL. 

git push --force URL <!-- This pushed git to the URL and overwrote everything -->