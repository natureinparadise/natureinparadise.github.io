### Deploying Changes to natureinparadise.github.io

**First**: it might be a good idea to update Hugo:

brew upgrade hugo

\_add and push your changes to natureinparadise/personal_page

cd /Users/David/Documents/GitHub/personal_page
git add -A
git push https://natureinparadise:Dk120026_gitnature@github.com/natureinparadise/personal_page.git

_deploy changes to natureinparadise repo_

hugo -d ../natureinparadise.github.io/

_add and push changes in natureinparadise/natureinparadise.github.io_

cd /Users/David/Documents/GitHub/web_development/natureinparadise.github.io
git add --all
git commit -m "adding web content"
git push

Now **WAIT** for a few minutes before loading https://natureinparadise.github.io
