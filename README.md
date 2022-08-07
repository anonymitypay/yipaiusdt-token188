
# 易支付usdt插件，注册即用
因为目前的方式是通过直接跳转到我们的支付网关进行支付的，所以如果某些系统是直接跳转到易支付的，比如需要跳转到submit.php易支付后台网关的，这种的网关地址是单独配置的
这个时候 网关地址是：https://epay.coinpay.best/
如果你不是跳转到submit.php的形式那就请继续看下面的流程
### 其他形式的易支付如果配置不成功，请联系我们进行适配
### 前提条件：系统本身已经集成了易支付的插件

### 网站配置 以独角发卡为例 其他系统可以参考

### 打开发卡后台 配置设置 >支付网关 > 点击新增，照着下面的内容添加
 - 支付名称	Token188
- 商户ID	你的商户ID
- 商户key 注意了这里需要填写我们的支付网关 https://payapi.coinpay.best/
- 商户密钥	你的商户密钥
- 支付标识	Token188-USDT
- 支付场景	通用
- 支付方式	跳转
- 支付处理路由	/pay/yipay（每个系统的易支付处理路由不一样，请根据你系统默认的易支付路由填写）
 - 商户ID, 商户密钥  请到[TOKEN188](https://www.token188.com/) 官网注册获取.
 
<p align="center">
<img src="https://www.token188.com/git/epay.jpg"/>
</p>

### 然后进去token188管理后台填写你需要收款的usdt地址和进行其他设置
1. 注册[TOKEN188商户中心](https://mar.token188.com)
2. 在商户中心添加需要监听的地址
3. 根据使用的不同面板进行回调设置(回调地址填写你网站的域名)
### 产品介绍

 - [TOKEN188 USDT支付平台主页](https://www.token188.com)
 - [TOKEN188钱包](https://www.token188.com)（即将推出）
 - [商户平台](https://mar.token188.com/)
### 特点
 - 使用您自己的USDT地址收款没有中间商
 - 五分钟完成对接
 - 没有任何支付手续费




## 有问题和合作可以小飞机联系我们
 - telegram：@token188
