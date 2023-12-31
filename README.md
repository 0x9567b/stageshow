# Stageshow  < **9.8.5**
Unauthenticated information disclosure in the WordPress stage show plugin version:  &lt; 9.8.5

### Description
Vulnerable file location: : /wp-content/plugins/stageshow/lib/phpinfo.php <br>
Link : https://en-gb.wordpress.org/plugins/stageshow/#description <br>
Version : - < **9.8.5** <br>
Parameter: N/A <br>
Status: unpatched <br>

### Code snippet: 

```php
<?php
        phpinfo();
?>
```

### Proof of concept:

![image](https://github.com/0x9567b/stageshow/assets/72038577/ed8c49b9-6d5d-4bf8-8f4e-e8c8514baf0c)
