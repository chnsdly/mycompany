+++
date = '{{ .Date }}'
draft = true
title = '{{ replace .File.ContentBaseName "-" " " | title }}'
+++
# 为每篇文章自动生成统一格式的字段，可以包含日期、标题等等。