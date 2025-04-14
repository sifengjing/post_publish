# 如何发布新闻文章 - 简易教程

## 第一步：准备文章文件
1. 在 `src/content/news/english` 文件夹下创建一个新文件
2. 文件名用英文，用连字符（-）连接单词
3. 文件必须以 `.mdx` 结尾
   例如：`your-news-title.mdx`

## 第二步：复制以下模板
```
---
title: "在这里写标题"
meta_title: "在这里写SEO标题"
description: "在这里写文章简短描述"
date: 2024-03-20
image: "/images/news/你的图片名称.jpg"
author: "作者名字"
categories: ["分类1", "分类2"]
tags: ["标签1", "标签2"]
draft: false
---

# 在这里写大标题

在这里写开场白内容...

![图片说明](/images/news/你的图片名称.jpg)

## 第一个小标题

在这里写正文内容...

## 第二个小标题

在这里继续写内容...
```

## 第三步：填写基本信息
在文件最上方的 `---` 之间填写：
1. `title`: 文章标题
2. `meta_title`: SEO标题（可以和title一样）
3. `description`: 简短描述（1-2句话）
4. `date`: 日期（格式：年-月-日）
5. `author`: 作者名字
6. `categories`: 分类（用英文中括号，逗号分隔）
7. `tags`: 标签（用英文中括号，逗号分隔）
8. `draft`: false（如果是草稿就写true）

## 第四步：添加图片
1. 将你的图片放在 `public/images/news` 文件夹下
2. 在文章中这样插入图片：
   ```
   ![图片说明](/images/news/你的图片名称.jpg)
   ```

## 第五步：写正文
1. 用 `#` 写大标题（一个#）
2. 用 `##` 写小标题（两个#）
3. 用 `-` 写列表（减号后面空格）
4. 用 `**文字**` 加粗重要内容

## 实用技巧
1. 标题要用英文引号 `""`
2. 日期格式必须是 `2024-03-20` 这样的格式
3. 分类和标签用英文 `[]` 括起来，用逗号分隔
4. 图片路径前面必须有 `/`

## 示例参考
看看这个真实的例子（省略了部分内容）：
```
---
title: "Medical Titanium: The Future of Implant Technology"
meta_title: "Titanium Alloy–Miracle in Medical Implants"
description: "Exploring the revolutionary impact of titanium alloys"
date: 2024-03-20
image: "/images/news/titanium-medical-implant.jpg"
author: "Dr. Sarah Mitchell"
categories: ["Medical Technology", "Innovation"]
tags: ["Medical Implants", "Healthcare"]
draft: false
---

# Titanium Alloy–Miracle in Medical Implants

这里是开场白...

![Medical Grade Titanium Implants](/images/news/titanium-medical-implant.jpg)

## Key Advantages

- 第一点
- 第二点
- 第三点
```

## 注意事项
1. 所有文件名和图片名都用英文小写
2. 图片必须先上传才能显示
3. 写完后可以把 `draft: true` 改成 `false` 发布
4. 保存文件时注意用 `.mdx` 后缀

可以看news目录下的示例
