# Membership  会员制模块

---

* 非会员的注册后默认为会员买家
* 买家想申请为卖家或平台商家，必须提交商家入驻申请，经过管理员和平台系统审查后才可以成为平台卖家。为了流程清晰，买家和卖家登入户口独立存在。

![](/assets/UCMembership.jpg)

---

# User Interface 会员页面

![](/assets/FooterIcon1.png)

When user click on My Account / My Profile Icon on footer icon. Link to the page below:-

![](/assets/Membership.png)![](/assets/会员.png)

![](/assets/PofileNavigation.png)![](/assets/DesciptionNavigation.png)

当用户点击自己头像，就会去个人“信息管理”的页面

#### 1\) Click on your own profile

![](/assets/Profile Management.png)![](/assets/账户管理.png)

注：

× 真实名：在注册后，是不支持被更改。

× 用户名：4-20个字符，可由英文，数字，“\_"，"-"组成

× 性别：男，女，保密

当用户点击会员特权，会进入“会员特区”

#### 2\) Membership

![](/assets/会员特区.png)

---

#### 7\) My Order

![](/assets/MyOrderIcon.png)

![](/assets/MyOrder1.png)

#### Important!

#### Order Status - All, Payment, Shipping, Review, Refund Details, Ranking\(Filter\)

Each Order display 

--------------------------------------------------------------------------------------------------------------------------------------------

Merchant Shop Name

Items Name from Merchant Shop

Total Quantity from Merchant Shop

Order Status: Successfull or Fail

#### 8\) Return & Refund Process

![](/assets/Return.png)

###### ![](/assets/Refund2.png)

###### Lists of purchased product \(Display of product only available within refund/ return policy days\)

* Date of purchase per order 
* Quantity purchase per order 
* The first image of purchased product 
* Status of the product \(Pending Delivering, Delivered, Refund, Return Product 代出库，已收货，已退款，已退货）

One order can have many purchase products. Click on order if which to proceed for return and refund.

###### ![](/assets/import.png)

###### Each Order details must have:-

Shipping status\(Pending Delivering, Delivered, Refund, Return Product 代出库，已收货，已退款，已退货）

Shipping company details, Tracking number \(Ex: DHL - P10002L\)

Date, Time Ordered \( 2017-8-14 12:20:00 \)

Order ID \(1002\)

Shpping Address

Receiver

Delivery and Receive Time \(Morning Shift 10-11am , Afternoon Shift 12-4pm\)

Product name

Product details, Type, Color

Price

Delivery fees

Total Amount

---

#### Condition update in system

1\) Status\*

```
 User must select on the status to fill in reason and apply refund/ return request

-Received 

-Haven't receive
```

###### Status \(Received Product\)

1\) Request of :-

```
-Return Product button

-Return amount button
```

2\) If condition 'Return Amount', Fill in amount

3\) Return Reason

4\) Image proof of Reason

###### Status \(Delivering product\)

![](/assets/Refund6.png)

Mobile do refund

![](/assets/Return4.png)

Reason /原因\*

Type of reason:

```
       -Incorrect product or size ordered 订购错误
       -Product did not match description on website or in catalog 虚假发货
       -Merchant shipped wrong product or size 商家发错货
       -Delivery problem 快递问题
       -Empty Parcel 空包裹/少货/虚假发货
       -others 其他
```

Other refund reason: User type own reason

Proof of Image

Submit button of refund

![](/assets/Refund7.png)

Once clicked submit button, refund or retrun process will send mercant to approve refund process.

Rufund status record will update on \(7\)My Order.

![](/assets/RefundFlow.png)

# Refund Status

#### 1\) Fail and closed

#### 2\) Successful

Amount, Refund time and date, Check amount refund in "my wallet"

Agreed details:

-Merchant

-Type: Refund or Return

-Amount

-Reason

-Refund ID

-Apply Date and Time

![](/assets/Refundsuccessful.png)![](/assets/RefundClosed.png)

# Use Case Assumptions, Preconditions and Post-conditions

| Use Case Name | 订单查询 |
| :--- | :--- |
| Description | 当用户进行查看产品订单 |
| Assumptions |  |
| Pre-conditions | 会员必须购买了才会产生订单 |
| Initiation \(Triggering event\) | 当去结算付款成功后系统产生订单号 |
| Main flow of events |  |
| Post-conditions |  |

# Database

Basic \(member information\)

| Field | Type | Null | Default | Extra |
| :--- | :--- | :--- | :--- | :--- |
| member\_id | int\(11\) | No |  | 会员ID |
| member\_name | varchar\(50\) | No |  | 会员名称 |
| member\_truename | varchar\(20\) | Yes |  | 真实姓名 |
| member\_avatar | varchar\(50\) | Yes |  | 会员头像 |
| member\_sex | varchar\(10\) | Yes |  | 会员性别 |
| member\_pwd | varchar\(32\) | No |  | 密码 |
| member\_addtime | int\(11\) | No | 0 | 注册时间 |
| member\_epoints | int\(11\) | No | 0 | 会员积分 |
| member\_state | tinyint\(1\) | No | 1 | 开启状态0关闭，1开启 |
| member\_loginnum | int\(11\) | No | 0 | 登入次数 |
| member\_phone | int\(20\) | Yes |  | 会员电话 |
| member\_birthday | varchar\(10\) | No |  | 生日日期 |
|  |  |  |  |  |
|  |  |  |  |  |
|  |  |  |  |  |
|  |  |  |  |  |



