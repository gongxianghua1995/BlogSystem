这个主要是我的博客代码，我博客地址：http://www.0duzhan.com

我的博客主要是通过Django进行开发，融合了一些有趣的小功能：

1：发完文章自动提取关键词/描述，进行SEO优化

2：可以自由切换模板

3：可以对用户留言进行初步的垃圾留言判定

4：可以限制每个IP每天访问次数

5：拥有用户注册功能，注册之后有后台

6：管理员后台和用户后台是分离的

7：拥有一个简历模块，可以随机切换简历

8：有相册模块

9：实现基本的文章发布，相册等功能

10：用户后台有APIcenter，有一些有趣的API功能

11：博客的搜索功能是融合了NLP相关知识

12：....


反正挺好玩的。哈哈哈哈



对了，有两个模型需要单独下载：

resnet50_coco_best_v2.0.1.h5

resnet50_weights_tf_dim_ordering_tf_kernels.h5




使用方法：

1：同步数据库

2：打开网站，选择注册，自己注册一个号。系统默认uid=1的为admin

3：管理员登录可以登录/admin

4：忘记说了，在配置数据库的时候，需要在BlogSystem/base.conf这个文件里面配置数据库信息，看一下就应该能看懂的

使用中有问题，或者想要帮忙改blog的bug，或者想要帮我提高博客性能，重构部分恶心代码的都可以联系我，service@52exe.cn
