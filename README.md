# DocBank 文档图像增强数据集

> **DocBank: Document Enhancement Dataset**

此数据集用于文档图像增强，具体任务包括以下内容：
+ Seal detection & Removal  印章检测 & 移除
+ Watermark detection & Removal 水印检测 & 移除
+ Document deblurring 文档去模糊
+ Document shadow removal 文档去阴影
+ Document super-resolution 文档超分
+ Document Low-Light Enhancement 文档低光增强  


## To-Do List

- [X] 释放第一批可用于合成的GT数据（10000张）
- [X] 释放第一批印章数据
- [ ] 释放第一批水印数据
- [ ] 释放第一批阴影数据
- [ ] 释放第一批超分数据
- [ ] 释放第一批去模糊数据
- [ ] 释放第一批低光数据
- [ ] 释放数据合成代码
- [ ] 第二批数据的释放

## 数据集

>以下是各任务数据集及链接地址：

### GT
>以下为干净的文档底图，读者也可根据需要自行处理合成自己的数据。

| 名称         | 说明               | 链接                     |
|--------------|--------------------|--------------------------|
| doc_img_10000    | 10000张文档图（第一批，编号10000）              | [百度网盘](https://pan.baidu.com/s/1CEXbdE0ObZtHsmddisg9lg)         |

### Seal
| 名称         | 说明               | 链接                     |
|--------------|--------------------|--------------------------|
| seal-10000-1    | 与GT10000对应，文件名-(x1, y1, x2, y2)分别表示印章位置左上和右下的坐标              | [百度网盘](https://pan.baidu.com/s/1pCCgHQxPOX-RWkCwmmxoXg)         |
| Seal-10000-2    | 与GT10000对应，文件名-(x1, y1, x2, y2)分别表示印章位置左上和右下的坐标             | [链接](链接地址)         |


## 备注
文档图片大部分来自于互联网收集的公开图片。**本数据集仅用于学术用途，请勿用于非法领域。**  
有任何疑问可邮件联系*yf.liu2@siat.ac.cn*，如果本项目对您有帮助，欢迎您给本项目点一个star，感谢！
