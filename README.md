# zhouhongjian.github.io

A chinoiserie theme of Jekyll.

I may write the usage of it later.

**If you use unix-like operation,you don't viev the following content.**
---
I provide it for a test now.
Also, it is a normal project with jekyll.

I upstreamed the source in my Github Repositories. The link is https://github.com/zhouhongjian/ZHJchinoiserie-Jeykll-Theme

Problem:

In _config.yml, I writed "permalink: /:year-:month-:day/:title.html".
The directory named _posts has threes markdown file.
Two file's name contain Chinese,other file'name is English.
When I run it containing Chinese in my local machine,I can't visit the Chinese article.

For example,type
"http://localhost:4000/2016-04-30/%E6%B4%9B%E7%A5%9E%E8%B5%8B.html" in google chrome,I can't visit my article. (URL contain "%E6%B4%9B%E7%A5%9E%E8%B5%8B".the String is Chinese string of "洛神赋" 'sURLencode.If you type "洛神赋" directly,the result is same.)

But,when I want to visite the file whose name is English,the result is normal.

For example,type
"http://localhost:4000/2016-05-01/tengwanggexu.html" in google chrome.I can visit the article normally.

ps:
1. If I type "http://localhost:4000/2016-04-30/",I can find the URL of file whose filename is Chinese.But,the URL is different from the URL using URLEncode.
2. The problem only occur in local.It can run normally in GitHub Pages.
