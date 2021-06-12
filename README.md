# php-conditional-statement-
<?php
// conditional statement if, if...ilse, if..ilseif, ilse, switch
/*$a = 10;
if($a>5){
	echo "\$a is grater then 5";
}*/
/*$a=10;
if($a>15){
	echo "$a is grater then 15 ";
}else{
	echo "\$a less then 15";
}*/
/*$a= 5;
$b = 10;
$c = 15;
$d = 20;
if($a==$b){
	echo "a and b are equal";
}elseif($a==$c){
	echo "a and c are equal";
}elseif($a==$d){
	echo "a and d are equal";
}else{
	echo "all are not equal";
}*/
$t = date("H");
if($t < 10){
	echo "Have a good morning";
}elseif($t < 20){
	echo "Have a good day";
}else{
	echo "Have a good night";
}
?>
