---
layout: page
title: 欢迎！
tagline: Supporting tagline
---
{% include JB/setup %}

这里是 Roundhead 的博客，主要用来记录毫无意义的生活琐事和乱七八糟的脑补物，大概也不怎么会更新。

什么？你居然敢问以前的博客去哪了？还想见到明天的太阳吗？

## 关于我

随处可见的成年男子，头（大概）比较圆。喜欢尝试新鲜的东西，但是大多数想做的东西都坑了。

同人作品中有「圆头的内心住着一个萌妹子」的设定，不过在官方作品中并未提及。

## 喜欢的东西

### ACGN

轻小说入宅，不过其实什么小说都会看一些。印象比较深刻的有阿加莎、王小波和谷川流（的《逃离学校》）。

动画和漫画纯粹随心情看，喜欢无脑搞笑向和超展开向，不过像《Liar Game》或者《One Outs》这种也不错啦XD

游戏纯手残所以一般不玩和人对抗的，当然LOL有小炮娘这种萌系英雄所以偶尔玩一玩。印象比较深的游戏大概有《秋之回忆》、《星之梦》、《逆转裁判》、《口袋妖怪》、《太鼓达人》、《DJ max》和《Patapon》。（其实还有很多别的懒得列举了）

### 写代码

学学新语言啥的总归是很有意思的。不过总归是用不上啦。

## 朋友们

广告位招租






## Archive

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

