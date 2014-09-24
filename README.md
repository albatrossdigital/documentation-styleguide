## Installation

#### Basic (repo already setup)
Just clone the repo, npm install and run grunt:
```
git clone git@github.com:albatrossdigital/<repoName>.git
cd pls
npm install && bower install 
grunt
```

#### Pushing changes
```
git status
git commit -m "msg" filenames
git push
```

#### Typekit urls
```
albatrossdigital.github.io,127.0.0.1:9000,*.albatrossdemos.com
```


#### Advanced (setting up repo)
Create repo in github
```
git clone git@github.com:albatrossdigital/albatross-style-guide.git
mv albatross-style-guide <repoName>
cd <repoName>
git remote set-url origin git@github.com:albatrossdigital/<repoName>.git
git push origin gh-pages
```
