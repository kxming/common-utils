# common-utils

1. 项目描述
    > 个人开发过程中收集到的常用开发工具函数及通用函数。

2. 如何运行
    `npm install --save-dev common-utils`

3. 介绍
    > console.log()劫持
    > ![console](./assets/console.png)

    > 汉字转拼音
    ```
    import { pinyin } from "pinyin.js";

    const test = "我是中国人";
    console.log('pinyin: ', pinyin(test));

    #echo
    woshizhongguoren
    ```