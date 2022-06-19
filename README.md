# Theme for the ZASchools website project

Building a site from the theme using a download:
```
cd ~/hugo
hugo new site zaschool-site
cd zaschool-site

git init 
git add .
git commit -m 'Initial commit'

wget https://github.com/GeraldScott/zaschool-national/archive/refs/heads/master.zip

unzip master.zip
mv zaschool-national-master themes/zaschool-national
rm -f master.zip

\cp -af themes/zaschool-national/exampleSite/* .
\cp ~/hugo/archton2/.gitlab-ci.yml .
\cp ~/hugo/archton2/.gitignore .
```
