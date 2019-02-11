# PAT题解说明

**文件夹**

- analysis: 放置题解说明的markdown文件
- html: 放置PAT原题网页，由download.py脚本下载，便于提取原题内容
- md: 放置最终成型的markdown文件，包含完整的题目、原题、题解、代码，方便浏览

**文件**

- build.py: 生成最终markdown文件。从html文件夹中的网页文件提取原题信息，从analysis文件中的markdown文件提取题解说明，从仓库的master分支的文件中提取原代码，生成最终的文件。
- config.py: 把一些可能会变得量放在这里，包括题目数量，文件夹名称，最终markdown微调参数等。
- download.py: 下载PAT网站题目网页
- makefile: 执行生成、清理文件的任务