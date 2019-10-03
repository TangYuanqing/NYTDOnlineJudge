# OnlineJudge 2.0

定制版QDUOJ,添加了比赛rejudge,代码查重,用户名限制等功能,需要与[前端](https://github.com/ExpMango/OnlineJudgeFE)配合使用.

# Feature

## Contest rejudge功能:

管理员先将需要rejudge的题目隐藏起来,等若干秒使得队列里没有该题目的新提交,然后点击比赛中题目列表的rejudge按钮即可.


## 用户名限制: 

在contest描述中 最后的地方添加 “limit:#xxxx#“(不包含引号)即可,其中xxxx为用户名需要满足的正则表达式,如 limit:#201[5-8]11[0-9]{4}# 将使得用户名为"2015111234"的用户能够进入比赛,而"acm201111"的用户不能进入比赛.

## 比赛代码查重

比赛结束后在前台点击一键查重,然后进入查重页面即可看到结果(相似度40%以上).该功能需要在比赛结束后点,同时被查到的代码会被公开(share).

# 功能列表与进度

- [x] 完成contest的rejudge功能
- [x] 添加contest用户名限制功能(正则检查)
- [ ] 重写contest rank字段逻辑,更好的支持rejudge功能
- [ ] 将比赛用户名限制作为单独一个字段,并在前端添加对应位置.
- [x] contest代码相似查重 
- [ ] PE(格式错误)


