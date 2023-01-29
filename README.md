# 中山大学 LaTeX 毕业答辩ppt模板

## 介绍

本模版基于[Cumtb-Beamer](https://github.com/JinLingxi/Cumtb-Beamer)进行中山大学个性化修改，并结合[sysu-thesis](https://github.com/SYSU-SCC/sysu-thesis)上的模版给出示例。

***注：学校并没有指定毕业答辩ppt模板的规范，这里仅给出一种比较美观的模版，如果同学们自己的学院有单独要求，请以学院的模版为准。***

## 模版特点

1. 调整颜色为中大的标准色
2. 支持宽屏(16:9)输出
3. 引入个性化的定理、引理、假设、定义的环境
4. 更新参考文献的方式
5. 调整部分标题格式
6. 统一英文字体为Times New Roman（支持无衬线/衬线模式）
7. 支持调整无衬线/衬线字体

## 部分样式展示



<div style="align: center">
<img src="https://github.com/Lovely-XPP/SYSU-PRE/blob/main/demo/1.png">
</div>

<div style="align: center">
<img src="https://github.com/Lovely-XPP/SYSU-PRE/blob/main/demo/2.png">
</div>

<div style="align: center">
<img src="https://github.com/Lovely-XPP/SYSU-PRE/blob/main/demo/3.png">
</div>

<div style="align: center">
<img src="https://github.com/Lovely-XPP/SYSU-PRE/blob/main/demo/4.png">
</div>

<div style="align: center">
<img src="https://github.com/Lovely-XPP/SYSU-PRE/blob/main/demo/5.png">
</div>


## 如何使用

### texlive编辑

本模板需要使用texlive(>=2020)进行编译，编译命令如下：

```
make pdf
```

即可生成 `main.pdf` 文件。



### overleaf 编辑

本模板可以使用[overleaf](https://www.overleaf.com/) 在线编辑。

步骤如下：

1. 进入网站https://overleaf.com并登录账号
2. 左侧`New Project`选择`Upload Project`
3. 上传`SYSU-PRE-master.zip`压缩包，建立新项目
4. 点击`menu`，滑动到下方`Settings`的`Compiler`选择`XeLaTeX`
5. 打开`main.tex`文件，点击中间右侧上方的`Recompile`进行编译
6. 如果顺利可以看到pdf的预览
7. 如果无法加载图片只有路径信息，点击`Recompile`旁边的倒三角，其中的`Compile Mode`选择`Normal`模式

此时可以得到完整的`main.pdf`文件。


## 错误反馈以及改进

1. 同学们如果在编译或者使用过程中遇到了一些问题，请参照[这里](ihttps://github.com/ryanhanwu/How-To-Ask-Questions-The-Smart-Way)的步骤尝试解决问题。如果还是没法解决，请开一个新issue汇报错误。
1. 如果您想参与本项目的维护，我们强烈建议您发起访问请求(Access request)到本项目，即可成为本项目的开发人员! 我们***非常欢迎校友的加入***。
   或者，Fork本仓库到您的 github 仓库中，修改完成后给本项目提交`Merge Request`。
