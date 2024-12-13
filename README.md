# SabaSoalSade.php
https://quera.org/problemset/31025?tab=description
<?php
list($n, $k )= explode(" ", readline("Enter 2 numbers: "));
$n = (int)$n;
$k = (int)$k;
for($i = 0; $i < $k; $i++){
	$n /= 2;
}
echo floor($n);
