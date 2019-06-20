# Semantic Versioning with Git

## initial commit

git commit -m "first commit"

git tag -a v0.0.0 -m "version 0.0.0"

git push -u origin master

git push -u origin master --tags


## add first feature

git add *

git commit -m "first feature"

git tag -a v0.1.0 -m "version 0.1.0"

git push -u origin master v0.1.0


## add second feature

git add *

git commit -m "second feature"

git tag -a v0.2.0 -m "version 0.2.0"

git push -u origin master --follow-tags
