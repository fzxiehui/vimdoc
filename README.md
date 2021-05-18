# vimdoc
## 简介
在vim中添加帮助文件
  - :h 进行快速浏览
  - :h xtop 打开目录
  - ZZ 退出
  - :h xx + <Ctrl - D> 查找匹配列表
## 部署方式
- git clone https://github.com/fzxiehui/vimdoc
- windows NVim
```shell
cd <username>/AppData/Local/nvim/
mklink /j ./doc <vimdoc path>
cd doc
run nvim-qt
:helptags .
```

- ubuntu 
```shell
# clone
git clone https://github.com/fzxiehui/vimdoc

# 创建软链接
ln -s <vimdoc path> <user home>/.config/nvim/doc

# 创建 tags
cd doc
nvim
:helptags .
```
