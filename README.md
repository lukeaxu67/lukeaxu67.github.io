```bash
npm install hexo-cli -g
npm install hexo-renderer-pug --save
mkdir blog && cd blog
hexo init
npm install
git clone -b master https://github.com/jerryc127/hexo-theme-butterfly.git themes/butterfly
cp themes/butterfly/_config.yml _config.butterfly.yml
hexo clean
hexo generate
hexo server
```