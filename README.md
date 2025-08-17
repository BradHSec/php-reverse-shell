# php-reverse-shell
# PHP Reverse Shell (PentestMonkey)

This script provides a simple PHP-based reverse shell. Useful for scenarios where you have upload access to a web server running PHP.

## Usage
Upload `php-reverse-shell.php` to the target server and access it via browser:


## Configuration
Edit the IP and port in the script to match your listener: 
```php
$ip = 'YOUR_IP';
$port = YOUR_PORT;
```

## Listener
Set up the listener on your host machine:
```bash
nc -lvnp YOUR_PORT
```



#### 4. **Credit the Original Author**
Respect licensing by including attribution in your `README.md` or a `LICENSE` file:
```markdown
Original script by [PentestMonkey](https://pentestmonkey.net/tools/php-reverse-shell).
Licensed under GPL-2.0.





