  515  mkdir git-exercise
  516  cd git-exercise
  517  git clone https://github.com/mattpe/git-intro.git
  518  git remote rm origin
  519  cd git-intro
  520  git remote rm origin
  521  git remote add origin https://github.com/ohuji/git-exercise.git
  522  git branch -M main
  523  git push -u origin main
  524  touch notes.md
  525  ls -a
  526  history
  527  git status
  528  git add .
  529  git commit -m "added notes file"
  530  git push
  531  history