## Bash
```bash
#!/bin/bash

curl <URL>
```
<br />

## Nim
```nim
import HttpClient
var ip = newHttpClient().getContent("<URL>")
echo(ip)
```
<br />

## PHP
```php
<?php
    $ip = file_get_contents('<URL>');
    echo $ip;
?>
```
<br />

## PowerShell
```powershell
$ip = Invoke-RestMethod -Uri '<URL>'
"$ip"
```
<br />

## Python
```python
from requests import get

ip = get('<URL>').text
print(ip)
```
<br />

## Ruby
```ruby
require "net/http"

ip = Net::HTTP.get(URI("<URL>"))
puts ip
```
