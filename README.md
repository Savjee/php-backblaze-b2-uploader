# DEPRECATED!
This library is unmaintained! Please don't use it!

An alternative:
* https://github.com/gliterd/backblaze-b2



# php-backblaze-b2-uploader
PHP Class that allows you to upload files to Backblaze B2

## Simple usage

```PHP
<?php
require 'b2.php';
   
// Create new instance and pass it your credentials
$b2 = new B2Uploader([
  'accountId'         => 'XXXXXX',
  'applicationKey'    => 'XXXXXXXXXXXX',
  'bucketId'          => 'XXXXXXXXXXXX'
]);
 
// Upload a file!
$b2->uploadFile('myBackup.zip');
```
