<?php
$vAli=2;
$vBadu=5;
$sAli=0;
$sBadu=0;
$jarak=1000;
echo "Kecepatan Ali = $vAli m/detik<br>";
echo "Kecepatan Badu= $vBadu m/detik<br>";
echo "Jarak titik A ke titik B $jarak meter<br><br>";
for($t=1;$t<=10;$t=$t+1)
{
	$sAli=$sAli+$vAli;
	$vAli=$vAli+0.1;
}
echo "Setelah 10 detik, Ali sudah bergerak : $sAli menit<br><br>";
echo "Memasuki detik ke 11 Badu berangkat dari titik B ke titik A<br>";
$TJarak=$sAli+$sBadu;
$t=$t+1;
while($TJarak<1000) {
	$sAli=$sAli+$vAli;
	$vAli=$vAli+0.1;
	$sBadu=$sBadu+$vBadu;
	$TJarak=$sAli+$sBadu;
	$t=$t+1;
}
echo"<br>";
echo "Ali dan Badu berpapasan pada detik ke : $t setelah jam 08:00<br><br>";
echo "Setelah $t detik dari jam 08.00<br>";
echo "Saat berpapapsan Jarak Ali dari titik A : $sAli meter dan jarak Badu dari titik B : $sBadu meter";
?>
