# seat-system
1.实现的效果：

    　　1. 学生

        首次登录载入数据，再次登陆载入上次登录的缓存。
        每个区域按照闲余座位的情况显示表情：“很多座位“，“较多座位“，“较少座位“，“很少座位“，
        点击座位选座，然后更新缓存。在”我的“页面会显示刚刚预约座位的时间段和地点

       2. 班级

        和学生账号不同的是可以选择时间段，预约整间教室

       3. 管理员

        更改图书馆状态为不可用。
        新增管理员账号（输入新账号和密码）

 

 2.可以输入账号2013190419、admin。分别是学生和管理员的账号，密码都是11111。

 3.问题：有时候storage获取不到值，用了同步setStoragesync后还是get不到，然而过了一段时间又可以了。循环往复。
 


