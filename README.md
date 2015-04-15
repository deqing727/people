my readme file.

echo # people >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/deqing727/people.git
git push -u origin master

git config --global core.eol lf
git config --global core.autocrlf input
git config --global core.safecrlf true
git config --system core.eol lf
git config --system core.autocrlf input
git config --system core.safecrlf true


try the following
git config --global core.autocrlf false
git config --system core.autocrlf false
