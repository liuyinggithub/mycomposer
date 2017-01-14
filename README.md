# mycomposer
<?php
 require_once 'vendor/autoload.php';

 $data = [
     'a' => 'test',
     'b' => 'test'
 ];
 $jsondata = \mycomposer01\Json::encode($data);
 print_r($jsondata);

 $data2 = \mycomposer01\Json::decode($jsondata);
 print_r($data2);
