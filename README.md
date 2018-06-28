# simpleimage
Simple image class resize picture in PHP

How to usage:

$image = new SimpleImage();
$image->load($path1);
$image->resizeToWidth(300);
$image->resizeToHeight(300);
$image->save(getcwd().DIRECTORY_SEPARATOR.'PIC-NAME.jpg');
