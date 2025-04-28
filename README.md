 1  mkdir volkless - создаем новую паку
    2  cd volkless - переходим в эту папку
    3  git init - создаем репозиторий
    4  git status - содержимое
    5  git remote add origin git@github.com:SergeyVolkov20/volklessdosk.git - подключение к удаленному репозиторию
    6  git branch -M main - создание веткb
    7  git push -u origin main
    8  git remote -v
   10  touch README.md
   11  explorer .
   13  git add .
   15  git commit -m "random file"
   29  git push -u origin main
   30  ls -al ~/.ssh
   31  ssh-keygen -t rsa -b 4097 -C "sergey_2005_13@mail.ru"
   32  eval "$(ssh-agent -s)"
   33  ssh-add ~/.ssh/id_rsa
   34  cat ~/.ssh/id_rsa.pub
   35  ssh -T git@github.com
   36  git push -u origin main
   37  history

# git
