# *topy 汉字转换拼音*

> npm install topy --save-dev

+ use
``` 
    import toPy from 'topy'
    实例toPy,调用topy方法,传入汉字 将会返回一个数组,数组内容为对应汉字索引的拼音
    接收到非汉字将原样返回至对应数组索引

    let topy = new toPy()

    topy.topy('请输入')         // ['qing', 'shu', 'ru']

```