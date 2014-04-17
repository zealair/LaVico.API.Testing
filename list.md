### 优惠券活动列表 {brand}/Coupon/Promotions

> 客户提供的xls内，并无type定义；测试数据请删除掉数组的情况

### 会员积分明细 {brand}/Point/Log/{memberId}

> 目前测试数据无MEMO；结果需按照时间倒序排列

### 会员所获优惠券的列表 {brand}/Coupon/GetCoupons

> 需要显示MEMO

### 领取优惠券 {brand}/Coupon/FetchCoupon

> 需传输MEMO

### 门店列表 {brand}/Shops

> _code返回了多余的空格；(测试数据库里既如此，我们删除空格，会导致错误)_
>
> ~~省份勿出现省字、城市勿出现市字~~
>
> 经纬度无数据；
>
> _需抓取邮编；(CRM无此信息)_
>
> ~~需按城市搜索；~~

### 会员消费记录 {brand}/Member/Spending/{memberId}

> _哪个用户可以查消费记录？_ 

### 会员卡等级 {brand}/Member/Level/{memberId}

> ~~等级代码表示的含义需列出~~
> 01: 白卡，02:普通VIP卡，03：白金VIP卡

### 保存会员资料到CRM {brand}/Member/SaveInfo/{memberId}

> 需确定行业、款式的定义及代号
> （沟通中 ...，不过基本可以确定，这两个字段不是代号，自由输入）

### 从CRM读取会员资料 {brand}/Member/Info/{memberId}

> _无标签信息；_（无需标签信息）

### 会员积分增减 {brand}/Point/Change

> ~~需传输MEMO~~

### 会员消费记录 {brand}/Member/Spending/{memberId}

> 需增加产品图片URL
> （沟通中）
