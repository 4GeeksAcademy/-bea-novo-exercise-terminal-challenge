# thecommandchallenge
+ ls | cd
# print current directory path 
+ pwd
# List all the files from the current directory including the hidden ones
+ ls -la or ls -all
# Now list all the files inside the project, recursively (all files in the hierarchy)
+ tree -a or ls -R
# Clear all the clutter from the command line
+ clear
# Go to the last level below the small-name folder and show on the console the content of the trophy.txt file
+ ls 
  cd 
  cat
# Move one level up and get to the funcode directory and list all files with the JavaScript typical extension
+ cd.. (x3) / cd funcode/ find . -type f -name "*.js"
# Create a new directory inside funcode/the-most-funny/ called “not-that-funny“
+ cd the-most-funny/ mkdir -not-that-funny
# Create a copy of the-mostboring-text.txt (you can find it within /boringfolder/‘s children) and name it lol.txt
+ mv the-mostboring-text.txt lol.txt
# Move funcode/kids.jpg inside funcode/images/hello/
+  mv kids.1.jpg images/hello/
# Remove the “small-name“ directory
+ rm -r small-name/
# Print in the command line the content of the-ultimate-joke.txt
+ funcode/cat the-ultimate-joke.txt
# Remove all the contents from the boringfolder, they are extremely boring…
+ rm -r boringfolder/
# Open the file kamehameha/dragon-ball-jokes.md using the VI command line text editor
+  cd ..  vi dragon-ball-jokes.md/
# Update the file kamehameha/dragon-ball-jokes.md by removing the first joke you read on the file, finally save and close the text editor
+  nano dragon-ball-jokes.md 
