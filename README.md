1写在前面，本项目重建了，由于之前教别人更新fork的项目，导致本项目被提交了一些pull requests，而且不知怎么的还变成了Contributor，非常无语，经过思虑再三，决定删除重建。重建后，之前的star和fork全部重置，如果你之前已经fork了，那么之间的关联自动解除，即在你的项目页面不会再展示“Fork from Arron/py_scripts”。好吧，把之前的项目数据记录一下：

![images-20200709171538](https://cdn.jsdelivr.net/gh/Arronlong/cdn/blogImg/20200709171538.png)

![image-20200709172617402](https://cdn.jsdelivr.net/gh/Arronlong/cdn/blogImg/20200709183623.png)

---

python脚本集，支持selenium，基于[SeleniumBase](https://github.com/seleniumbase/SeleniumBase)项目

当前功能：

1. [TextNow保号](<https://github.com/Arronlong/py_scripts/tree/master/scripts/textnow>)
2. [HostLoc赚积分](<https://github.com/Arronlong/py_scripts/tree/master/scripts/hostloc>)
3. [天翼云盘签到+抽奖](<https://github.com/Arronlong/py_scripts/tree/master/scripts/C189>)

功能对应的参数，请点击后自行查看。

根据需要自行修改.github/workflows/actions.yml进行任务定制

---

# Github Actions说明

## 一、Fork此仓库(已fork的无需再次fork)

![](http://tu.yaohuo.me/imgs/2020/06/f059fe73afb4ef5f.png)

## 二、设置Secret参数

根据需要添加对应任务的参数，参数说明请直接点上面的链接进行查看。
![](http://tu.yaohuo.me/imgs/2020/06/748bf9c0ca6143cd.png)

## 三、启用Action

1 点击**Action**，再点击**I understand my workflows, go ahead and enable them**  
2 修改任意文件后提交一次  
![](http://tu.yaohuo.me/imgs/2020/06/34ca160c972b9927.png)

## 四、查看运行结果

Actions > py_scripts > build  
能看到如下图所示，表示成功  
![](https://cdn.jsdelivr.net/gh/Arronlong/cdn/blogImg/20200707132455.png)

此后，将会在每天2:00和14:00各发送一次  
若有需求，可以在[.github/workflows/actions.yml]中自行修改，**【此配置所有任务共享，修改需谨慎】**


