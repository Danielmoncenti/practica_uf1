#!/bin/bash
echo indica el nombre del directorio que quieres crear

read directorio

echo indica el nombre del archivo que quieres crear

read archivo

echo indica una frase a guardar en el archivo

read frase

mkdir "$directorio"

cd "$directorio"

date > "$archivo"

echo $frase > "$archivo"