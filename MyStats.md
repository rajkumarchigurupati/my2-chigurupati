# RAJ KUMAR CHIGURUPATI
I am from ongole,India.I did my undergraduate from Vignan University in 2020.After my bachelors,I have been working as a associate system engineer in Birla Soft pvt.ltd.Basically,I like to explore different traditions & cultures.I love watching films often.

![My Image](image/my-image.jpeg) 

**** 

## Sports:
It is one of the economics and accomplished in various field in sports .In ancient history and diversified culture substantially influence local and mainstream sports millions os people play and watch sports connected to the country'sc  colonial legacy these sports include Cricket,tennis,football,basketball,badminton
|NAME|REASON|NO.OF HOURS|
|----|------|-----------|
|cricket|fun|2hours|
|tennis|fitness|1hour|
|football|a team sport|45min|
|basketball|team work|1hour|
|badminton|physical skill|1hour|

****

## quotes

>There's no place like home said by-Dorothyv

>The truth will set you free said by- Bible

****

## Code Fencing:

stack overflow link: https://stackoverflow.com/questions/69399718/how-to-make-a-custom-error-page-using-htaccess-file

code snippet:

```
<?php

$status=$_SERVER['REDIRECT_STATUS'];
$codes=array(
      400 => array('400 Bad Request', 'The request cannot be fulfilled due to bad syntax.'),
      401 => array('401 Login Error', 'It appears that the password and/or user-name you entered was incorrect.'),
      403 => array('403 Forbidden', 'Sorry, employees and staff only.'),
      404 => array('404 Missing', 'We\'re sorry, but the page you\'re looking for is missing, hiding, or maybe it moved somewhere else and forgot to tell you.'),
      405 => array('405 Method Not Allowed', 'The method specified in the Request-Line is not allowed for the specified resource.'),
      408 => array('408 Request Timeout', 'Your browser failed to send a request in the time allowed by the server.'),
      414 => array('414 URL To Long', 'The URL you entered is longer than the maximum length.'),
      500 => array('500 Internal Server Error', 'The request was unsuccessful due to an unexpected condition encountered by the server.'),
      502 => array('502 Bad Gateway', 'The server received an invalid response from the upstream server while trying to fulfill the request.'),
      504 => array('504 Gateway Timeout', 'The upstream server failed to send a request in the time allowed by the server.'),
);

$errortitle=$codes[$status][0];
$message=$codes[$status][1];

if($errortitle==false){
       $errortitle="Unknown Error";
       $message="An unknown error has occurred.";
}

?>
<!doctype html>
<html>
<head>
<title><?php echo("$errortitle");?></title>
<meta charset="utf-8">
</head>
<body>

<!-- Insert headers here. -->

<?php
echo('<h1>'.$errortitle.'</h1>');
echo('<p>'.$message.'</p>');
?>

<!-- Insert footers here. -->

</body>
</html>
 




