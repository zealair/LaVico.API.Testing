### 优惠券活动列表 {brand}/Coupon/Promotions

> 客户提供的xls内，并无type定义；~~测试数据请删除掉数组的情况~~

### 会员积分明细 {brand}/Point/Log/{memberId}

> 目前测试数据无MEMO；~~结果需按照时间倒序排列~~

### 会员所获优惠券的列表 {brand}/Coupon/GetCoupons

> ~~需要显示MEMO~~

### 领取优惠券 {brand}/Coupon/FetchCoupon

> ~~需传输MEMO~~
> 新增加参数 memo

### 门店列表 {brand}/Shops

> code返回了多余的空格；省份勿出现省字、城市勿出现市字；经纬度无数据；需抓取邮编；需按城市搜索；
> 
> 返回的城市是NULL，这可能是一个bug

### 会员消费记录 {brand}/Member/Spending/{memberId}

> 哪个用户可以查消费记录？

### 会员卡等级 {brand}/Member/Level/{memberId}

> 等级代码表示的含义需列出

### 保存会员资料到CRM {brand}/Member/SaveInfo/{memberId}

> 需确定行业、款式的定义及代号

### 从CRM读取会员资料 {brand}/Member/Info/{memberId}

> 无标签信息

### 会员积分增减 {brand}/Point/Change

> 需传输MEMO

### 会员消费记录 {brand}/Member/Spending/{memberId}

> 需增加产品图片URL
