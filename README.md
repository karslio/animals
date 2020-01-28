Lenovo Thinkpad@karslio MINGW64 ~/Desktop/tum belgeler/PROGLAMLAMA/PYCODERS/animals (new-feature)
$ git checkout master
Switched to branch 'master'
Your branch is up to date with 'origin/master'.

Lenovo Thinkpad@karslio MINGW64 ~/Desktop/tum belgeler/PROGLAMLAMA/PYCODERS/animals (master)
$ git pull origin master
From https://github.com/karslio/animals
 * branch            master     -> FETCH_HEAD
Already up to date.

Lenovo Thinkpad@karslio MINGW64 ~/Desktop/tum belgeler/PROGLAMLAMA/PYCODERS/animals (master)
$ git merge new-feature
Updating 1f6b2b3..191aab2
Fast-forward
 pets.txt | 3 +++
 zoo.txt  | 7 ++++---
 2 files changed, 7 insertions(+), 3 deletions(-)
 create mode 100644 pets.txt

Lenovo Thinkpad@karslio MINGW64 ~/Desktop/tum belgeler/PROGLAMLAMA/PYCODERS/animals (master)
$ git push origin master
Total 0 (delta 0), reused 0 (delta 0)
To https://github.com/karslio/animals.git
   1f6b2b3..191aab2  master -> master
