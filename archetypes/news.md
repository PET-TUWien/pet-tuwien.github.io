+++
title = '{{ replace .File.ContentBaseName "-" " " | title }}'
subtitle = '{{ replace .File.ContentBaseName "-" " " | title }}'
date = {{ .Date }}
release = {{time.Format "2006-01-02" .Date }}
image = ''
draft = false 
+++
