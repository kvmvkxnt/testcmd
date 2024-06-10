<?PHP 
$output=null;
exec('hostname', $output);
print_r($output);
echo $output;
?>