## **开发环境搭建(Windows) & STM32基础**

#### 学习内容
###### 环境配置
*  _CubeMX_
* _gcc-arm-none-eabi_
*  _Keil_
   > Keil和VSCode + EIDE各有优势，比如Keil有一些仿真和可视化的工具，VSCode更美观，编码体验更好，也有更好的社区生态，提高开发效率。建议都学一学，具体开发时根据自己习惯选择
* _VS Code_
  > 1. VSCode + EIDE 代替 Keil
  > 2. VSCode + CMake(怎么编译运行C/C++程序)
  > 2. VSCode + git
  > 3. VSCode + Markdown
  > 4. VSCode + LaTeX
  > 5. VSCode 代码主题（例如One Dark Pro）
  > 6. VSCode 快捷键提高效率
  > 7. VSCode 快捷注释与代码格式化
  > 8. VSCode + 知乎
  > 9. ......（网上有丰富的教程，通过安装扩展插件，实现各种功能，配置自己的工作环境）
* _串口调试助手_（很多，推荐几个：[VOFA+ ](https://www.vofa.plus/docs/learning/)）
  
###### STM32基础
- 简单了解，不理解的可以上网搜，后续实践后可能更容易理解
  > - 什么是单片机，和电脑有什么区别
  > - 什么是STM32
  > - 开发板一般由什么组成
  > - 命名规则
  > - 什么是HAL库，为什么选择HAL库
  > - 时钟树系统
  > - 同步/异步、阻塞/非阻塞、回调 的概念
  > - ......


#### 教程推荐
###### 配置环境
- [谢阳学长的开发环境配置详细教程](https://github.com/MirTITH/WTR-EC-Training/blob/main/01-stm32%E5%9F%BA%E7%A1%80%EF%BC%8C%E7%8E%AF%E5%A2%83%E9%85%8D%E7%BD%AE/01-stm32%E5%9F%BA%E7%A1%80%EF%BC%8C%E7%8E%AF%E5%A2%83%E9%85%8D%E7%BD%AE.md)
- 如果你想用VSCode,看看[这篇教程](https://github.com/MirTITH/WTR-EC-Training/tree/main/Tips%E5%90%88%E9%9B%86)，详细写了怎么配置VSCode，使用Debug等经验
- [EIDE官网](https://em-ide.com/zh-cn/docs/intro/)
- [配置环境的文章](https://blog.csdn.net/qq_38191568/article/details/126012144?spm=1001.2014.3001.5502)
- [配置环境视频教程](https://www.bilibili.com/video/BV1Sy4y1y7B1?p=2&spm_id_from=pageDriver&vd_source=baa784078e67e28c38d26cf6881f8357)
###### STM32基础
-  WTR培训讲义-STM32基础
-  [同步/异步/阻塞/非阻塞](https://www.cnblogs.com/IT-CPC/p/10898871.html)
-  [回调函数](https://www.zhihu.com/question/19801131)
-  [bin、hex、elf、axf文件的区别
](https://www.cnblogs.com/llxbl/p/10944160.html)

#### 小任务
   * 配置开发环境,遇到问题,可以在战队仓库Issues里提问或记录、分享自己的解决方案
   * 看看教程里的链接内容，了解STM32基础知识
   * 进阶任务 ： 尝试后续实验用VSCode+EIDE开发(根据自己喜好)