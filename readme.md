# 自定义Qt 按钮

## 1、修改日志

| 编号 |                             内容                             |   时间    |
| :--: | :----------------------------------------------------------: | :-------: |
|  1   | 第一次创建提交。DPushButton继承自QPushButton类，可以以图片的形式显示按钮，也可以以文字的形式显示按钮。 | 2019.7.16 |
|      |                                                              |           |
|      |                                                              |           |

## 2、接口说明

*日期：2019.7.16*

提供接口：

```c++
    void setPixmapScale(double i); //设置按钮显示大小相对于图片的比例。
    void setPixmap(const QPixmap &pixmap); 
    void setTextColor(const QColor &color);
    void setTextFont(const QFont &font);
    void setText(const QString& text);
```

