# 皮皮仔宣言
本宣言旨在对“底层程序的设计”进行思考  
+ 开发者应更重视“如何减少 bug 的产生”，而不是“如何善后”，善后工作是必要的，但不是最重要的  
+ 如果有问题（或潜在问题），应尽早崩溃，不要等到纸包不住火时，不应纵容任何不良习惯  
+ 本来仅通过功能测试就可以暴露的 bug，再加入“保护开发者”的代码后，会把 bug 的暴露推迟到上线  
+ Simplicity is beauty

# 原则
+ 不应严格遵守本宣言内容，包括这一条
+ 追求快乐
+ 追求进步
+ 追求低熵

# 宣言
##### 亲近“ppz 程序”
“ppz 程序”就是进行了皮皮仔宣言的程序  
非我族类，其心必异  

##### 不过度封装，让使用者参与  
使用底层程序的开发者，以下简称“使用者”  
至少让使用者参与思考，进而评论，进而帮助改进、共同进步  
思考，人是阻止不了的，但“复杂、繁乱”可以  

“（让使用者写的）代码量少”不等于“使用起来很简单”  
多行朴素的代码，比一行 ```new Chun()``` 简单得多  

##### 不过度保护
保护代码会使代码量剧增，从而降低代码可读性，使使用者迷惑  
由于不保护而产生的意外，因代码的简单而容易定位、解决，使使用者更加了解内部细节  

##### 只保留最普通的情况
少数（或极端）情况留给使用者自己处理  
比如，在 js 里，应可以通过 ```typeof str == 'string'``` 来判断“是否为字符串”  

##### 不过度兼容

##### 学习妥协，不应因追求而停滞不前
刚则易折
