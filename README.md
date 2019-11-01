Task 1 Basic Task


    1. ls - List all of the contents of a specified directory. I see all the files that are on the home tab with all the directories and files. It means that these are the directories available currently.
    2. pwd - Displays the current working directory for the command line terminal. The directories and files are not visible only the path is visible. It shows which tab I am in
    3. Create a new folder and name it “workspace”  and changes the current working directory in the command line console.
    4. I see nothing, which means there is no content with the directory
    5. created a duplicate file of README.md and changed the name to CHANGELOG.md. The directory now has two files.

Task 2 Absolute and Relative Paths


mkdir exercise.md 
mkdir /tmp
mv exercise.md into /tmp 
cd tmp
ls tmp
rmdir exercise.md


Task 3 Cat Commands

    1. Created the following files:
       touch umuzi.md
       touch cohort.md
       touch recruit.md
       
    2. added text to the files by using, cat > umuzi.md
       enter “text”
       cat > recruit.md
       enter “text”
       cat > cohort.md
       enter “text”
       
    3. cat cohort.md recruit.md umuzi.md. The content of files was displayed on the terminal
       
    4. touch summary.md
       cat cohort.md recruit.md umuzi.md > summary.md
       
    5. cat>> summary.md
       “The end”

Task 4 The locate command

    1. locate umuzi
       
    2. locate umuzi.md > search_result.md
       cat search_result.md
    3. pwd

Task 5

    1. pwd
       
    2. cd Documents
       touch pad.md
       
    3. cd ~
       pwd
       cd Desktop
       mkdir work
       cd ~
       pwd
       cd Documents
       cp pad.md ~/Desktop pad_copy.md
       
    4. update: sudo apt update
    5. cd ~
    6. locate pad_copy.md


Task 6 Find commands

    1. Locate .pdf
    2. locate .pdf | tee -a output.txt
    3. find . -mtime -1 -print
       


Task 7 Text editor


    1. nano file name (my_bio.md)
    2. Ctrl+o
       enter
    3. mv my_bio.md my_files

       

        
       


