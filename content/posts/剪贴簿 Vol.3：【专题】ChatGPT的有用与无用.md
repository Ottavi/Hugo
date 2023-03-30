---
title: "剪贴簿 | Vol.3：【专题】ChatGPT的有用与无用"
date: 2023-03-30T19:08:48+08:00
draft: false
tags: 
 - 专题
 - 技术
 - ChatGPT
categories: 
 - 剪贴簿
slug: "web-clipping-vol3"
---

这期剪贴簿是第一期专题阅读，涉及的文章大半来自于Fediverse用户的创作和推荐，感谢友邻们。如果遇到合适的选题或者积攒了同一个领域的多篇待读，我会继续以专题形式更新这个栏目并在标题中注明，从而和无主题的剪贴簿区分开来。  
Disclaimer：我完全不了解计算机和人工智能领域，如果本文出现任何错误，请一定要在评论区纠正我，万分感谢！

## 1. ChatGPT Is a Blurry JPEG of the Web
[原文链接](https://www.newyorker.com/tech/annals-of-technology/chatgpt-is-a-blurry-jpeg-of-the-web)，发布于The New Yorker。澎湃做了中译，[《降临》作者特德·姜：ChatGPT是网上所有文本的模糊图像](https://m.thepaper.cn/newsDetail_forward_21877769)。原文对不熟悉这个领域的人来说可能有一些生词，但句法非常平实，总体不难，请放心阅读。  
本文主要解释了ChatGPT是如何回答问题的，即根据使用者的提问来对互联网上的信息进行“洗稿”并输出。  
由于网络上的信息体量过于庞大，开发者只能使用有损压缩算法把它们尽可能地塞进服务器里。在压缩中原有的精确文本大量丢失了，当我们提出问题时，ChatGPT用插值（interpolation）的方式填补那些丢失的内容，即通过一些关键词补充出整个文本。这解释了它在回答一些事实性问题时糟糕的表现，但这种特性在生成论证性文本（比如大学论文）中非常有用。对人类来说，用自己的话复述而不是逐字逐句地精确引用是习得了知识的表现，因此在这个方面，做不明白数学题的ChatGPT看起来非常聪明。

## 2. Noam Chomsky: The False Promise of ChatGPT
[原文链接](https://www.nytimes.com/2023/03/08/opinion/noam-chomsky-chatgpt-ai.html)，发布于The New York Times，澎湃也做了中译，[乔姆斯基：ChatGPT的虚假承诺](https://mp.weixin.qq.com/s/yknwdKSJ1qkr0HcJcsSn6A)。这篇评论由两位语言学家和一位人工智能总监兼哲学家共同撰写，主要讨论了ChatGPT及相似的其它A.I.在学习模式和道德上存在的问题。  
文章指出，ChatGPT通过大量数据学习人类语言并输出最有可能出现的结果，也就是那些看起来很像人类的回答。这种学习模式和人类完全不同，人类可以通过极小的样本量无意识地推测出一种语言的语法，但ChatGPT没有这种推测规律的能力。推而广之，ChatGPT没有推测任何规律的能力，因此它不具备真正的智能。  
另外，当被问及个人观点和道德问题时，ChatGPT往往给出“我不具有个人观点”和“我不具有道德”这类回答。对于一个道德问题，它会综述现有文献并给出正反两方兼有的答案，这种“中立”实际上表现出了回避和漠不关心，有时它甚至会用“我只是遵守命令”和“我的创造者才应该为此负责”之类的语言来推卸责任。  
总而言之，作者们认为ChatGPT及相似产品在语言和道德上都是不完善的，它生成真假掺杂的回答，对任何观点都不予置评，对道德和不道德的言论都持同一态度。

## 3. Learn how to use ChatGPT to enhance your learning of Programming
[原文链接](https://github.com/BlackStar1453/Using-ChatGPT-to-Learn-Programming)，发布于GitHub，内容是中文。  
本文是用ChatGPT辅助学习编程的教程，大部分内容都极具针对性，但指出了向ChatGPT提问的有效方式，这个方法可以用于任何相同性质的提问之中，非常有价值。  
在另一位Fedi友邻写的用ChatGPT辅助英语教学设计的文章中也有提到（很可惜我找不到链接了），ChatGPT的回答质量取决于提问的质量，一个针对性明确的提问会让它生成更好的回答，并且它生成的答案中可能会有错误和不完善的部分，需要使用者根据自己的判断给出反馈来促使它修正答案。  
ChatGPT在辅助学习方面的优势在于，它是一个全天候在线且基本免费的老师，而且可以根据使用者的问题和反馈来定制解答。对于人文社科领域的学习者来说，ChatGPT能够起到的指导作用可能比较有限，不过用来辅助语言学习还是相当有效的。我尝试过在用英文与ChatGPT对话的同时让它纠正我的拼写和语法，并且评价我的表达是否合适。另外，我也看到有友邻说ChatGPT很擅长proofreading和paraphrasing。

## 4. 教ChatGPT讲福州话
[原文链接](https://sanguok.com/blog/teach-chatgpt-speaking-hokchew/#comments)，发布于山月的博客。  
作者是一位福州话（闽东语/平话）使用者，教ChatGPT说方言这个想法本身就足够有趣，作者还深谙与它打交道的方法，竟然真的完成了基本的教学。正如作者在文末所说，这个实践的一大意义在于为保存方言和濒危语言提供了一定的思路，或许有一天我们真的可以利用人工智能保存和学习一门未被普遍使用的语言。

## 5. 人不会输给AI，只会败于自己
[原文链接](https://newsletter.newslab.info/gpt-ai/)，发布于方可成的新闻实验室newsletter。  
这篇简短通讯的重点不在ChatGPT本身，而集中在当下中文世界对于A.I.技术热潮的讨论。作者认为，现下很多关于人工智能的讨论是技术中心主义、技术乐观主义和技术民族主义的，但新技术的出现应该成为人类反思自我主体性的机会，而不是迷失在“取代”与否的狂欢中。