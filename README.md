# 小程序里面的客服按钮各种样例
小程序客服接入按钮各种说明


## 客服按钮
```
<button type='default' open-type='contact'> 打开客服 (普通客服) </button>
```

##把用户的头像和昵称传递给客服系统
```
<button type='default' session-from='{"nickName":"{{userInfo.nickName}}","avatarUrl":"{{userInfo.avatarUrl}}"}' open-type="contact" >带头像客服（微信头像）</button>

```


