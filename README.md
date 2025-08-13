#### …or create a new repository on the command line
echo "# python_design_patterns" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M origin
git remote add origin https://github.com/jgq-tech/python_design_patterns.git
git push -u origin origin


#### …or push an existing repository from the command line
git remote add origin https://github.com/jgq-tech/python_design_patterns.git
git branch -M origin
git push -u origin origin

#### github代理
走 socks5 代理（如 Shadowsocks）
git config --local http.proxy "socks5://127.0.0.1:1086"