urlPostTest
===========


Just a simple Testproject in xcode to test a POST Request to a php Script and write the content to a file on the server.

The PHP File is more than simple:

<?php

$key1 = $_POST['shift'];


file_put_contents("ip.txt", $key1, FILE_APPEND);

?>
