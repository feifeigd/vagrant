# vagrant
vagrant

把当前的vbox虚拟机制作成box
```
vagrant package --output ~/名字.box
```
如果不指定 --output 则生成在当前目录下名字为 package.box

把导出的box覆盖原有box列表里去
```
 vagrant box add arch64 ./package.box --force
```
