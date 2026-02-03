 LINUX BASIC COMMAND ASSIGNMENT

Q1. Creating and Renaming Files/Directories
Commands:
mkdir test_dir
cd test_dir
touch example.txt
mv example.txt renamed_example.txt

Q2. Viewing File Contents
cat /etc/passwd
head -n 5 /etc/passwd
tail -n 5 /etc/passwd

Q3. Searching for Patterns
grep root /etc/passwd

Q4. Zipping and Unzipping
zip -r test_dir.zip test_dir
unzip test_dir.zip -d unzipped_dir

Q5. Downloading Files
wget https://images.pexels.com/photos/1940772/pexels-photo-1940772.jpeg

Q6. Changing Permissions
touch secure.txt
chmod 444 secure.txt

Q7. Environment Variables
export MY_VAR="Hello, Linux!"
echo $MY_VAR
