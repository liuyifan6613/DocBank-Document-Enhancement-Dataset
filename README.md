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
- [X] 释放第二批印章数据
- [X] 释放第一批水印数据
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

| 名称         | 说明               | 链接                     | 提取码   |
|--------------|--------------------|--------------------------|----------|
| doc_img_10000    | 10000张文档图（第一批，编号10000）              | [百度网盘](https://pan.baidu.com/s/1zPFHpDYTM0D0yz6BL2dm1g)         | ibxf   |

### Seal
| 名称         | 说明               | 链接                     | 提取码   |
|--------------|--------------------|--------------------------|----------|
| seal-1-1    | 10000张，混合数据，与GT10000对应，文件名-(x1, y1, x2, y2)分别表示印章位置左上和右下的坐标              | [百度网盘](https://pan.baidu.com/s/1iotKgCHiO17DxiTNiTbMaw)         | hc6v |
| Seal-1-2    | 10000张，混合数据，GT10000对应，文件名-(x1, y1, x2, y2)分别表示印章位置左上和右下的坐标              | [百度网盘](https://pan.baidu.com/s/1QQCtKhfZCN5wbxfPcZNveQ)         |  esc8 |
| Seal-2      | 20796张，混合数据，印章区域成对数据                                                        | [百度网盘](https://pan.baidu.com/s/11E5WQG6cZTXZQxW_jzHw_Q)         |7t19|
| Seal-3      | 25033张，纯印章图片，无背景信息。GT为自行创建纯白对应shape图片                             | [百度网盘](https://pan.baidu.com/s/1kBtq-1UiVgmhizqdPSfzxA)         | 9qpf|
| Seal-4      | 80000张，PNG带有透明通道纯印章，可置于自定义背景上，亦可转成jpg同Seal-3                           | [夸克网盘](https://pan.quark.cn/s/62ddd822ba6d)           |C4b8|

### Watermark
| 名称         | 说明               | 链接                     | 提取码   |
|--------------|--------------------|--------------------------|----------|
| watermark-1   | 10000张，与GT10000对应，水印生成来自于Stable Diffusion              | [百度网盘](https://pan.baidu.com/s/14nR52T-2b4AZ48O8OrhYyw)         | ad9w |
 
## 引用
```
 @misc{DocBankEnc,
   author       = {Yifan Liu, Jiancheng Huang},
   title        = {DocBank Document Enhancement Dataset},
   year         = {2024},
   url          = {https://github.com/liuyifan6613/DocBank-Document-Enhancement-Dataset},
   note         = {GitHub repository},
 }
```

## 备注
文档的GT图片部分来自于互联网收集的公开图片，部分来自于真实数据。其中部分印章的真实数据来源于DocDiff以及ICDAR相关数据。大部分训练集由我们在GT上自己处理得到。**本数据集仅用于学术用途，请勿用于其他领域。**  
有任何疑问可邮件联系*yf.liu2@siat.ac.cn*，如果本项目对您有帮助，欢迎您给本项目点一个star，感谢！
