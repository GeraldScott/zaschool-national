# Theme for the ZASchools website project

Build a site from the theme using a download:
```
hugo new site zaschool-site
cd zaschool-site

wget https://github.com/GeraldScott/zaschool-national/archive/refs/heads/master.zip

unzip master.zip
mv zaschool-national-master themes/zaschool-national
rm -f master.zip

\cp -af themes/zaschool-national/exampleSite/* .
```
