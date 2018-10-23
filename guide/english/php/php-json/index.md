## Handle the JSON input in PHP file.

```php
$json = file_get_contents($json_url);
$data = json_decode($json, TRUE);
```
The decoded json stored in '$data' can be used in the PHP file.
