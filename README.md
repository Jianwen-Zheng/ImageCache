# ImageCache
iOS 图片缓存.


#缓存步骤
1. NSCache中是否存在
2. NSCache存在(返回),不存在(3)
3. 沙盒是否存在
4. 沙盒存在(返回并保存到NSCache),不存在(5)
5. 网络请求
6. 请求成功(保存沙盒,NSCache,返回对象),失败(标注失败清单)

