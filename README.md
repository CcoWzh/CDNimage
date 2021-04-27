# 云图片托管
本仓库主要用于存放博客的图片，进行云托管

使用步骤：

> 1. 克隆

```shell
git clone https://github.com/CcoWzh/CDNimage.git
```

> 2. 上传文件到 GitHub仓库

```text
git status                    //查看状态
git add .                     //添加所有文件到暂存区  不要忘记后面那个.
git commit -m '提交信息'      //把文件提交到仓库
git push                      //推送至远程仓库
```

在`markdown` 中，引用图片时，只需要：

```shell
https://cdn.jsdelivr.net/gh/GitHub用户名/仓库名/图片路径

# 在文件中引用，如：
# ![](https://cdn.jsdelivr.net/gh/CcoWzh/CDNimage/gRPC/gRPC-cert1.png)
```

