## Rasa NLU官网文档翻译（翻译的版本是 0.13.8）

### Rasa NLU:针对聊天机器人和人工智能助手的自然语言理解框架


Rasa NLU是一个开源的自然语言处理工具，用于聊天机器人的意图分类和实体提取，例如，拿一个句子来说：

``I am looking for a Mexican restaurant in the center of town``

处理后返回的结果如下：

```JSON
{
  "intent": "search_restaurant",
  "entities": {
    "cuisine" : "Mexican",
    "location" : "center"
  }
}
```
Rasa NLU的目标受众是开发聊天机器人和语音应用的开发者。

使用开源Rasa NLU的主要原因如下：

    1. 数据敏感，不方便把训练数据交给Google、Microsoft、Amazon、Facebook、百度等
    2. 机器学习并不是放之四海皆准，通用的训练模型并不一定适合特定的需求，可以更加需求定制自己的训练模型。
    3. Rasa NLU是开源的框架，可以进行定制开发。
 
 
您可以在这篇[博客文章](https://medium.com/rasa-blog/do-it-yourself-nlp-for-bot-developers-2e2da2817f3d)中了解使用开源NLU的优点,您可以在[这里](https://drive.google.com/file/d/0B0l-QQUtZzsdVEpaWEpyVzhZQzQ/view)看到将Rasa NLU与闭源替代方案进行比较

### 有问题或反馈吗?

我们在Rasa社区论坛上有一个非常积极的支持[社区](https://forum.rasa.com/)，很乐意帮助你解答问题。如果您对我们有任何反馈，或者对改进文档有任何具体建议，请通过在[Rasa NLU GitHub repository](https://github.com/RasaHQ/rasa_nlu)上创建问题与我们分享。


### 翻译目录
    
   [尝试使用Rasa NLU ](/Doc/尝试使用Rasa%20NLU%20.md)





































