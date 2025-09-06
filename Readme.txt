MAIN~
cd desktop
mkdir LAJERA_IT120_Act1
cd LAJERAR_IT120_Act1
touch Profile.txt Education.txt Background.txt Readme.txt Test.py
git init
git add .
nano Profile.txt
nano Education.txt
nano Background.txt
git add Profile.tx Education.txt Background.txt 
git commit -m "Add initial info to Profile, Education, Background; Readme left empty"

LAJERA_B1~
git switch -c LAJERA_B1
nano Profile.txt
git add Profile.txt
git commit -m "Added extra info to Profile"
nano Readme.txt
git add Readme.txt
git commit -m "Added new info to Readme"
git checkout master

LAJERA_B2~
git switch -c LAJERA_B2
nano Education
git add Education.txt
git commit -m "Added extra info to Education"
nano Readme.txt
git add Readme.txt
git commit -m "Added new info to Readme"
git checkout master

LAJERA_B3~
git switch -c LAJERA_B3
nano Background
git add Backgrond.txt
git commit -m "Added extra info to Background"
rm Test.py
git commit -m "Remove Test.py in this branch"
nano Readme.txt
git add Readme.txt
git commit -m "Added new info to Readme"
git checkout master

LAJERA_B4~
git switch -c LAJERA_B4
ls
nano Readme.txt
git add Readme.txt
git commit -m "Added new info to Readme"
git checkout master
git branch
git remote add origin https://github.com/alleaneed/LAJERA_IT120_Act1.git
git push -u origin master
git push origin LAJERA_B1 LAJERA_B2 LAJERA_B3 LAJERA_B4
