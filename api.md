# user

## Setting.vue

![image-20250609100850242](C:\Users\suin\AppData\Roaming\Typora\typora-user-images\image-20250609100850242.png)

1. ![image-20250609095227731](C:\Users\suin\AppData\Roaming\Typora\typora-user-images\image-20250609095227731.png)

进入/setting自动调用并将返回的数据渲染到页面上

![image-20250609100917042](C:\Users\suin\AppData\Roaming\Typora\typora-user-images\image-20250609100917042.png)



2. ![image-20250609100934958](C:\Users\suin\AppData\Roaming\Typora\typora-user-images\image-20250609100934958.png)

点击退出登录按钮触发

![image-20250609101024156](C:\Users\suin\AppData\Roaming\Typora\typora-user-images\image-20250609101024156.png)

3. ![image-20250609101236947](C:\Users\suin\AppData\Roaming\Typora\typora-user-images\image-20250609101236947.png)

需要修改原有的界面，将修改密码独立出来，考虑做一个弹窗表格，不与修改其他用户信息一起

4. ![image-20250609101335784](C:\Users\suin\AppData\Roaming\Typora\typora-user-images\image-20250609101335784.png)

界面上删除个性签名，增加头像邮箱手机号

![image-20250609101409285](C:\Users\suin\AppData\Roaming\Typora\typora-user-images\image-20250609101409285.png)



5. ![image-20250609101719882](C:\Users\suin\AppData\Roaming\Typora\typora-user-images\image-20250609101719882.png)

管理员接口，先不用管



# order

## Order.vue

![image-20250609102814021](C:\Users\suin\AppData\Roaming\Typora\typora-user-images\image-20250609102814021.png)

![image-20250609101817904](C:\Users\suin\AppData\Roaming\Typora\typora-user-images\image-20250609101817904.png)

1. ![image-20250609101903177](C:\Users\suin\AppData\Roaming\Typora\typora-user-images\image-20250609101903177.png)

![image-20250609102013759](C:\Users\suin\AppData\Roaming\Typora\typora-user-images\image-20250609102013759.png)

根据所选的分类和页码获取对应的订单信息，每次点击上方的分类导航栏都会调用：

<img src="C:\Users\suin\AppData\Roaming\Typora\typora-user-images\image-20250609102241048.png" alt="image-20250609102241048" style="zoom:33%;" />

## OrderDetail.vue

![image-20250609103026935](C:\Users\suin\AppData\Roaming\Typora\typora-user-images\image-20250609103026935.png)



1. ![image-20250609101910417](C:\Users\suin\AppData\Roaming\Typora\typora-user-images\image-20250609101910417.png)

![image-20250609102704697](C:\Users\suin\AppData\Roaming\Typora\typora-user-images\image-20250609102704697.png)

2. ![image-20250609102909628](C:\Users\suin\AppData\Roaming\Typora\typora-user-images\image-20250609102909628.png)

点击取消订单按钮

![image-20250609103355551](C:\Users\suin\AppData\Roaming\Typora\typora-user-images\image-20250609103355551.png)



3. ![image-20250609101920279](C:\Users\suin\Desktop\image-20250609101920279.png)

   同取消订单，按钮会随着订单状态自动变化，![image-20250609102958629](C:\Users\suin\AppData\Roaming\Typora\typora-user-images\image-20250609102958629.png)



## CreateOrder.vue

![image-20250609103557420](C:\Users\suin\AppData\Roaming\Typora\typora-user-images\image-20250609103557420.png)

1. ![image-20250609101932040](C:\Users\suin\AppData\Roaming\Typora\typora-user-images\image-20250609101932040.png)

   ![image-20250609103544683](C:\Users\suin\AppData\Roaming\Typora\typora-user-images\image-20250609103544683.png)

   

2. ![image-20250609101936784](C:\Users\suin\AppData\Roaming\Typora\typora-user-images\image-20250609101936784.png)

在创建订单页面(CreateDetail.vue)点击生成订单后自动弹出支付窗口，

![image-20250609104115804](C:\Users\suin\AppData\Roaming\Typora\typora-user-images\image-20250609104115804.png)

在订单详情页（OrderDetail.vue）面如果状态为未支付则有去支付按钮，

![image-20250609104152963](C:\Users\suin\AppData\Roaming\Typora\typora-user-images\image-20250609104152963.png)

3.![image-20250609104648958](C:\Users\suin\AppData\Roaming\Typora\typora-user-images\image-20250609104648958.png)

![image-20250609105218007](C:\Users\suin\AppData\Roaming\Typora\typora-user-images\image-20250609105218007.png)

![image-20250609105445947](C:\Users\suin\AppData\Roaming\Typora\typora-user-images\image-20250609105445947.png)

根据选择获取地址信息

4. ![image-20250609105536477](C:\Users\suin\AppData\Roaming\Typora\typora-user-images\image-20250609105536477.png)

![image-20250609105525295](C:\Users\suin\AppData\Roaming\Typora\typora-user-images\image-20250609105525295.png)



## Adress.vue

![image-20250609104315236](C:\Users\suin\AppData\Roaming\Typora\typora-user-images\image-20250609104315236.png)

![image-20250609104330032](C:\Users\suin\AppData\Roaming\Typora\typora-user-images\image-20250609104330032.png)

1. ![image-20250609104350546](C:\Users\suin\AppData\Roaming\Typora\typora-user-images\image-20250609104350546.png)

![image-20250609104509464](C:\Users\suin\AppData\Roaming\Typora\typora-user-images\image-20250609104509464.png)

进入页面自动获取收货地址信息



## AdressEdit.vue

![image-20250609105019183](C:\Users\suin\AppData\Roaming\Typora\typora-user-images\image-20250609105019183.png)

1. 

![image-20250609104648958](C:\Users\suin\AppData\Roaming\Typora\typora-user-images\image-20250609104648958.png)

![image-20250609104846459](C:\Users\suin\AppData\Roaming\Typora\typora-user-images\image-20250609104846459.png)



2. ![image-20250609105656672](C:\Users\suin\AppData\Roaming\Typora\typora-user-images\image-20250609105656672.png)

![image-20250609105756289](C:\Users\suin\AppData\Roaming\Typora\typora-user-images\image-20250609105756289.png)

3. ![image-20250609110006229](C:\Users\suin\AppData\Roaming\Typora\typora-user-images\image-20250609110006229.png)

![image-20250609110052060](C:\Users\suin\AppData\Roaming\Typora\typora-user-images\image-20250609110052060.png)

3. ![image-20250609110015349](C:\Users\suin\AppData\Roaming\Typora\typora-user-images\image-20250609110015349.png)

![image-20250609110118418](C:\Users\suin\AppData\Roaming\Typora\typora-user-images\image-20250609110118418.png)





# cart

## ProductDetail.vue

1. ![image-20250609110735539](C:\Users\suin\AppData\Roaming\Typora\typora-user-images\image-20250609110735539.png)



![image-20250609110834586](C:\Users\suin\AppData\Roaming\Typora\typora-user-images\image-20250609110834586.png)

点击加入购物车



## Cart.vue

![image-20250609110329189](C:\Users\suin\AppData\Roaming\Typora\typora-user-images\image-20250609110329189.png)

![image-20250609110433197](C:\Users\suin\AppData\Roaming\Typora\typora-user-images\image-20250609110433197.png)



1. 

![image-20250609111805897](C:\Users\suin\AppData\Roaming\Typora\typora-user-images\image-20250609111805897.png)

在进入购物车页面时自动调用

![image-20250609112108570](C:\Users\suin\AppData\Roaming\Typora\typora-user-images\image-20250609112108570.png)

剩下两个暂时不管



2. 

![image-20250609111017874](C:\Users\suin\AppData\Roaming\Typora\typora-user-images\image-20250609111017874.png)

![image-20250609110949775](C:\Users\suin\AppData\Roaming\Typora\typora-user-images\image-20250609110949775.png)



3. ![image-20250609111521173](C:\Users\suin\AppData\Roaming\Typora\typora-user-images\image-20250609111521173.png)

![image-20250609111726769](C:\Users\suin\AppData\Roaming\Typora\typora-user-images\image-20250609111726769.png)



## CreateOrder.vue

1. ![image-20250609111453165](C:\Users\suin\AppData\Roaming\Typora\typora-user-images\image-20250609111453165.png)

![image-20250609111432968](C:\Users\suin\AppData\Roaming\Typora\typora-user-images\image-20250609111432968.png)





# goods

## Category.vue

![image-20250609112343356](C:\Users\suin\AppData\Roaming\Typora\typora-user-images\image-20250609112343356.png)

1. ![image-20250609112701217](C:\Users\suin\AppData\Roaming\Typora\typora-user-images\image-20250609112701217.png)

获取商品分类列表和商品信息

![image-20250609112651130](C:\Users\suin\AppData\Roaming\Typora\typora-user-images\image-20250609112651130.png)



## ProductList.vue

![image-20250609113040932](C:\Users\suin\AppData\Roaming\Typora\typora-user-images\image-20250609113040932.png)

2. ![image-20250609112743898](C:\Users\suin\AppData\Roaming\Typora\typora-user-images\image-20250609112743898.png)

![image-20250609112838321](C:\Users\suin\AppData\Roaming\Typora\typora-user-images\image-20250609112838321.png)





## ProductDetail.vue

![image-20250609112958182](C:\Users\suin\AppData\Roaming\Typora\typora-user-images\image-20250609112958182.png)

![image-20250609112919188](C:\Users\suin\AppData\Roaming\Typora\typora-user-images\image-20250609112919188.png)

![image-20250609112929510](C:\Users\suin\AppData\Roaming\Typora\typora-user-images\image-20250609112929510.png)