# Membership  会员制模块

---

* 非会员的注册后默认为会员买家
* 买家想申请为卖家或平台商家，必须提交商家入驻申请，经过管理员和平台系统审查后才可以成为平台卖家。为了流程清晰，买家和卖家登入户口独立存在。

![](/assets/UCMembership.jpg)

---

# User Interface 会员页面

![](/assets/Membership.png)![](/assets/会员.png)

当用户点击自己头像，就会去个人“信息管理”的页面

![](/assets/Profile Management.png)![](/assets/账户管理.png)

注：

× 真实名：在注册后，是不支持被更改。

× 用户名：4-20个字符，可由英文，数字，“\_"，"-"组成

× 性别：男，女，保密

当用户点击会员特权，会进入“会员特区”

![](/assets/会员特区.png)![](/assets/member's privilige.png)

---

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



