# ZJNavigationController
一个方便实现全屏滑动返回的navigationController, 同时实现了常用的每一个界面都拥有一个独立的navigationBar的功能.


![navigationController.gif](http://upload-images.jianshu.io/upload_images/1271831-30de4f99b3a187f7.gif?imageMogr2/auto-orient/strip)

```
    UIViewController *vc = [ViewController new];
    ZJNavigationController *navi = [[ZJNavigationController alloc] initWithRootViewController:vc];
    // 开启
    [navi zj_enableFullScreenPop:YES];
```

> 这是我写的<iOS_CUSTOMIZE_ANALYSIS>这本书籍中的一个demo, 如果你希望知道具体的实现过程和其他的一些常用效果的实现, 那么你应该能轻易在网上下载到免费的盗版书籍. 

> 当然作为本书的写作者, 还是希望有人能支持正版书籍. 如果你有意购买书籍, 在[这篇文章中](http://www.jianshu.com/p/510500f3aebd), 介绍了书籍中所有的内容和书籍适合阅读的人群, 和一些试读章节, 以及购买链接. 在你准备购买之前, 请一定读一读里面的说明. 否则, 如果不适合你阅读, 虽然书籍售价35不是很贵, 但是也是一笔损失.


> 如果你希望联系到我, 你可以联系QQ:597769272
> 或者通过[简书](http://www.jianshu.com/users/fb31a3d1ec30/latest_articles)联系到我