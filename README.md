# Swift-PhotoBrowser
Swift写的一个简单的照片浏览器

使用示例:
    let vc = PhotoBrowserViewController.photoBrowserViewController()

    vc.urls = status.largeUrls
    vc.selectedIndex = photoIndex

    self.presentViewController(vc, animated: true, completion: nil)


###注意:使用此框架需要自己实现网络图像下载功能

![image](https://github.com/kouliang/Swift-PhotoBrowser/blob/master/image/1.png)
![image](https://github.com/kouliang/Swift-PhotoBrowser/blob/master/image/2.png)
![image](https://github.com/kouliang/Swift-PhotoBrowser/blob/master/image/3.png)
