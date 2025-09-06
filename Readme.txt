MAIN~
cd desktop 
mkdir LAJERA_IT120_Act1
cd LAJERA_IT120_Act1
touch Profile.txt Education.txt Background.txt Readme.txt Test.py
git init
git add .
nano Profile.txt
nano Education.txt
nano Background.txt
git add Profile.txt Education.txt Background.txt
git commit -m "Add initial info to Profile, Education, Background; Readme left empty"

LAJAERA_B1~
git switch -c LAJERA_B1
nano Profile.txt
git add Profile.txt
git commit -m "Added extra info to Profile"
nano Readme.txt
git add Readme.txt
git commit -m "Added new info to Readme"
