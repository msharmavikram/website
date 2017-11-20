  git clone https://github.com/msharmavikram/website.git
  cd website/
  git rm -r --cached public
  rm -rf public
  git submodule add https://github.com/msharmavikram/msharmavikram.github.io.git public 
  cd public/
  hugo
  cd public/
  git add . 
  git commit -m "Latest research in arch added"
  git push -u origin master


look : https://georgecushen.com/create-your-website-with-hugo/
