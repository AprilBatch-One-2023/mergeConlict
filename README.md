echo "# mergeConlicft" >> README.md
git init
#ADDING A FILE README.MD
touch README.md
#ADD TO STAGING AREA
git add README.md
#ADD MEANINGFULL NAME
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/AprilBatch-One-2023/mergeConlicft.git
git push -u origin main
