git clone https://github.com/szabopeter92/git-vizsga
git status
git add .
git commit -m 'README.md és .gitignore fájl létrehozása gitignore fájl kész'
git branch console 
git checkout
git status
git add .
git commit -m 'Sikeres oldal betöltése esetén kiirja, hogy Az oldal sikeresen betöltödött'
git status
git add .
git commit -m 'Style,css modositva hátérszíne színátmenetes'
git merge console
git remote remove origin
git remote add origin https://github.com/farkaskira/git-vizsga-farkaskira.git
git push -u origin main