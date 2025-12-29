
git rm -r --cached --ignore-unmatch "积雪厚度20250905" "jup" "pachong" "chartss.rar" "jup.rar" ;
git add .gitignore ; 
git commit -m "Remove ignored files from tracking" ;


echo "No changes to commit" ; 
git status --short