get-os
================
Only creates a simple and consistent way to find out what operating system is the current is php running.

* Supports Linux, Mac and Windows

```php
// Unknown = 1
// Windows = 2
// Linux = 3
// Mac = 4

echo getOS::ofServer(); // Return a integer
```