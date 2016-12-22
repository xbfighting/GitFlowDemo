# 一个完整的GitFlow案例

标签（空格分隔）： git demo

---
## 1 项目初始化

- 在 GitLab上创建项目 "GitFlowDemo"
 ![在 GitLab上创建项目 "GitFlowDemo"][1]
- 目前只有一个分支 master
 ![目前只有一个分支 master][2] 
- 在本地获取项目
 ![目前只有一个分支 master][3]
- 首次提交 添加文件 Demo.md
 ![首次提交][4]

## 2 添加 Develop 分支

``` shell
git branch develop
git push -u origin develop
```
- 添加develop分支
![add develop][5]
- gitlab上已经存在develop分支
![dev has already in gitlab1][6]
- gitlab上已经存在develop分支
![dev has already in gitlab2][7]


  [1]: http://o97p8x5mf.bkt.clouddn.com/01%20gitlab%E5%88%9B%E5%BB%BA%E9%A1%B9%E7%9B%AE.png
  [2]: http://o97p8x5mf.bkt.clouddn.com/01.01%20gitlab%E5%88%9B%E5%BB%BA%E9%A1%B9%E7%9B%AE%20%E5%8F%AA%E6%9C%89%E4%B8%80%E4%B8%AA%E5%88%86%E6%94%AF.png
  [3]: http://o97p8x5mf.bkt.clouddn.com/01.02%20gitbash%20master%20branch.png
  [4]: http://o97p8x5mf.bkt.clouddn.com/01.02.01%20master%20commit.png
  [5]: http://o97p8x5mf.bkt.clouddn.com/01.04%20develop%20branch%20remote.png
  [6]: http://o97p8x5mf.bkt.clouddn.com/01.05%20develop%20branch%20has%20already%20in%20gitlab%20.png
  [7]: http://o97p8x5mf.bkt.clouddn.com/01.06%20develop%20branch%20has%20already%20in%20gitlab%20.png