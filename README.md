# Program3
cd
git init
echo "line1" >> file.txt
echo "line2" >> file.txt
git add file.txt
git commit -m "initial commit"
git checkout -b branch-a
echo "change from branch A" >> file.txt
git commit -m "edit from branch A"
git checkout master
got checkout -b branch-b
echo "change from branch B" >> file.txt
git commit -m "edit from branch B"
Auto merging file.txt
CONFLICT: merge conflict in file.txt
line1
line2
git add file.txt
git commit -m 
