<?php
//function to generate example ishita13
function generateNumber($name = 'ishita'){ //function initialization with parameter variable name
$number = rand(6, 15);//random function to generate a random number
echo $name . $number;//it will print desired result
}
generateNumber();//function call
?>
