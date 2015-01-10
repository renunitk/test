<?php
header("Access-Control-Allow-Origin: *"); 
    if (isset($_POST['var_PHP_data'])) {
      $var1=$_POST['var_PHP_data'];
	  echo($var1);
    } else { echo "failed";}
?>
