This code works on lists of THOUSANDS of ip's, Enterprise level JSON's. The JSON I used had over 100,000 ip addresses. And my text file had about 2500 ip addresses... just make sure you follow these 3 Step directions in Linux. Good Luck!
Step 1)Inside the code, using Leafpad or Gedit , or your favorite, replace the text and Json with the full file paths (without full file paths, you will likely get an error! ) and exactly what you named them, inside quotes. 
Step 2) Save file , name it , using .py at the end. DON'T FORGET PERMISSIONS ! or else you will likely get an error
Step 3) in linux , remember to go to properties > permissions> check allow executing as a program. 
usage:  sudo Python3 "compareList.py" <or whatever you named it , can even drop and drag the file into terminal  , program will spit out amounts and when it's finished , how many the new list has.  Saves a new text file with the list of IPs.
