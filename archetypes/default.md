+++
image = ""
date = {{ .Date.Format "9999-12-31" }}
title = '{{ replace .File.ContentBaseName "-" " " | title }}'
+++
