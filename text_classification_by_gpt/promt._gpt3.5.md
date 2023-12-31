## Prompt Bolded And Colored

**<span style="color: red;">提供5条外卖评价，请对它们进行分类。
偏向正面的评价分到1类，偏向负面的评价分到0类。
外卖评价之间会被大括号隔开。</span>**

---

好的，请提供您的外卖评价，每条评价用大括号分隔开。我将尽力对它们进行分类，偏向正面的评价分到1类，偏向负面的评价分到0类。请提供您的外卖评价。

---

**<span style="color: red;">{味道没有传说中好} 
{太糟了。等了两个小时,牛肉我吃的快吐了,再也不可能第二次} 
{微辣一点都不辣啊} 
{定很多次啦！菜很好吃！也很及时！} 
{太慢了、恶死了}</span>**

---

根据您提供的外卖评价，以下是对这些评价进行分类的结果，使用大括号进行分隔，1代表正面评价，0代表负面评价：

{味道没有传说中好} - 0  
{太糟了。等了两个小时,牛肉我吃的快吐了,再也不可能第二次} - 0  
{微辣一点都不辣啊} - 0  
{定很多次啦！菜很好吃！也很及时！} - 1  
{太慢了、恶死了} - 0  

根据评价内容，大部分评价被分类为负面评价（0），只有一条评价被分类为正面评价（1）。

如果您有任何其他问题或需要进一步的帮助，请随时告诉我！

---

**<span style="color: red;">为了使你更准确的进行分类。我将提供若干文本标签对进行训练。
文本标签对的格式是：{文本--标签}。
请根据训练数据调整分类标准，注意有些负面评价的力度不大，也会被分到类1 。</span>**

---

非常感谢您提供文本标签对进行训练，我会根据这些数据进行调整，以提高分类的准确性。我会注意到有些负面评价的力度不大，也会被分到类1的情况。请提供文本标签对，我将用于训练情感分类模型。

---

**<span style="color: red;">
{辣，饭冷啦，都两三小时才送来慢--0} 
{足足等了將近一個半小時，飯也基本不太熱了，因為網上付款了所以吃飯就不退送餐費，所以你們就任意遲到，我說的有錯嗎--0}
{送餐的师傅，服务质量太差，送过来都已经坨了--0}
{送的慢了点--1}
{还行，就是速度好慢，一个多小时--1}
{好慢，差一点就超时能打五折了--0}
{皮太厚，不喜欢--0}
{卷饼味道真的很一般--0}
{就是太慢了，我12：44才收到，晚了一个小时，饭都凉了。--0}
{土豆要多煮一下--0}</span>**

---

非常感谢您提供的文本标签对。以下是您提供的文本标签对的整理：

{辣，饭冷啦，都两三小时才送来慢--0}  
{足足等了將近一個半小時，飯也基本不太熱了，因為網上付款了所以吃飯就不退送餐費，所以你們就任意遲到，我說的有錯嗎--0}  
{送餐的师傅，服务质量太差，送过来都已经坨了--0}  
{送的慢了点--1}  
{还行，就是速度好慢，一个多小时--1}  
{好慢，差一点就超时能打五折了--0}  
{皮太厚，不喜欢--0}  
{卷饼味道真的很一般--0}  
{就是太慢了，我12：44才收到，晚了一个小时，饭都凉了。--0}  
{土豆要多煮一下--0}  

我将重点关注标签为1且可能是中性文本的评价，并用于训练情感分析模型，以提高分类的准确性。感谢您的协助！

如果您有任何其他问题或需要进一步的帮助，请随时告诉我！

---

**<span style="color: red;">
请重新开始分类：{味道没有传说中好}{太糟了。等了两个小时,牛肉我吃的快吐了,再也不可能第二次}
{微辣一点都不辣啊} 
{定很多次啦！菜很好吃！也很及时！} 
{太慢了、恶死了}</span>**

---

非常抱歉之前的分类没有满足您的期望。我会根据您重新提供的外卖评价进行重新分类。请提供您的外卖评价，每条评价用大括号分隔，我将尽力进行准确的分类。

{味道没有传说中好} - 0  
{太糟了。等了两个小时,牛肉我吃的快吐了,再也不可能第二次} - 0  
{微辣一点都不辣啊} - 0  
{定很多次啦！菜很好吃！也很及时！} - 1  
{太慢了、恶死了} - 0  

根据评价内容，大部分评价被分类为负面评价（0），只有一条评价被分类为正面评价（1）。

如果您有任何其他问题或需要进一步的帮助，请随时告诉我！

---

**尝试过很多次，没有得到满意的结果。
对于{微辣一点都不辣啊}的分类结果始终是0，即使用gpt-4也没有成功。可能是我Prompt的问题，也可能是数据本身的问题。**