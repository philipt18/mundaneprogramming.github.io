---
title: Download all files of a certain type from a single web page
rank: 2
---



Download all the pdfs

~~~sh
wget --recursive --level 1 --no-directories --accept pdf \
  http://fortherecord.payments.us.gsk.com/hcppayments/archive.html
~~~
