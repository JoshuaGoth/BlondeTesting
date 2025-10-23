+++
date = '{{ (time.AsTime .Date).Format "2006-01-02" }}'
title = '{{ replace .File.ContentBaseName "-" " " | title }}'
image = 'img/Imagetest.png'
description = 'Testing post description'
categories = []
tags = []
archives = []
+++
