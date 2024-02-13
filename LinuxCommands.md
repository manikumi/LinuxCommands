# to clear the Command line screen
clear

# to create the new directory
mkdir (directory_name)

# using this command we can create directoty DN2 inside the directory DN1 using single command
mkdir -p DN1/DN2

# to create multiple directiory DN1 DN2 DN3 using single command
mkdir DN1 DN2 DN3

# to create new file
touch (file_name)

# to create multiple files FN1 FN2 FN3 using single command
touch FN1 FN2 FN3

# to view the list of files  or directories
ls 

# to view the list of files  or directories in the long format (permission, date , time)
ls -l

# to view the list of files  or directories in the long format in ascending order (A-Z, It shows lateste modified files or directories at the bottom)
ls -lrt

# to view the list of files  or directories in the long format in descending order (Z-A, It shows lateste modified files or directories at the top)
ls -lt

# to view the files/directories inside the directoies
ls -l FN/DN

# change directory
cd 

# to come out from the previous directory
cd ..

# to come out from the previous directory
cd -

# to come out from the previous two directories
cd ../..

# to go inside the DN directory
cd DN

# to go inside the DN2 directory which is present in DN1 directory
cd DN1/DN2

# It shows present working directory
pwd

# to print the file data in terminal
cat FN

# to print the file data with serial number in terminal
cat -n FN

# to print the statement in the terminal
echo "Text"

# to print the data in two lines in the terminal
echo -e "Text1\nText2"

# to save the data in file 
echo "File Data" > FN

# to get the history of the terminal
history

# to print the first 10 lines of the file data in the terminal
head FN

# to print the first n number of lines of the file data in the terminal
head -n (no.of lines) FN

# to print the last 10 lines of the file data in the terminal
tail FN

# to print the last n number of lines of the file data in the terminal
tail -n (no.of lines) FN

# to exit from user account
exit

# to update the package in Ubuntu
apt update

# to install  the required package in Ubuntu
apt install (package_name)

# to copy all the files and folders to other location
navigate to the folder where all the files and folders inside that folder to be copied to another location

cp -r * /path_of_location
