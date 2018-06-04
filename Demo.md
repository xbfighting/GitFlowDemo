# 一个完整的GitFlow案例

git flow  demo

---
## 1.项目初始化

- 在 GitLab上创建项目 "GitFlowDemo"
 ![在 GitLab上创建项目 "GitFlowDemo"][1]
- 目前只有一个分支 master
 ![目前只有一个分支 master][2]
- 在本地获取项目
 ![目前只有一个分支 master][3]
- 首次提交 添加文件 Demo.md
 ![首次提交][4]

## 2.添加 Develop 分支

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

## 3.开始新Feature开发

``` shell
git branch feature/fea_AAA
git checkout feature/fea_AAA 
git push -u origin feature/fea_AAA 
``` 

- 基于develop 添加Feature分支并推送到服务端
![add featuee][8]
- gitlab 上出现feature分支
![gitlab][9]

``` shell
# 做一些改动    
git status
git add Demo.md
git commit -m "[mod] add feature code"
```

- 做一些改动并提交到feature
![add some feature][10]
- gitlab
![gitlab][11]


  [1]: http://o97p8x5mf.bkt.clouddn.com/01%20gitlab%E5%88%9B%E5%BB%BA%E9%A1%B9%E7%9B%AE.png
  [2]: http://o97p8x5mf.bkt.clouddn.com/01.01%20gitlab%E5%88%9B%E5%BB%BA%E9%A1%B9%E7%9B%AE%20%E5%8F%AA%E6%9C%89%E4%B8%80%E4%B8%AA%E5%88%86%E6%94%AF.png
  [3]: http://o97p8x5mf.bkt.clouddn.com/01.02%20gitbash%20master%20branch.png
  [4]: http://o97p8x5mf.bkt.clouddn.com/01.02.01%20master%20commit.png
  [5]: http://o97p8x5mf.bkt.clouddn.com/01.04%20develop%20branch%20remote.png
  [6]: http://o97p8x5mf.bkt.clouddn.com/01.05%20develop%20branch%20has%20already%20in%20gitlab%20.png
  [7]: http://o97p8x5mf.bkt.clouddn.com/01.06%20develop%20branch%20has%20already%20in%20gitlab%20.png
  [8]: http://o97p8x5mf.bkt.clouddn.com/02.01.add%20feature.png
  [9]: http://o97p8x5mf.bkt.clouddn.com/02.02.add%20feature.png
  [10]: http://o97p8x5mf.bkt.clouddn.com/02.03.add%20feature.png
  [11]: http://o97p8x5mf.bkt.clouddn.com/02.04.add%20feature.png
