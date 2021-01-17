#!/bin/bash

for ARCHIVO in `ls`; do

echo -e "\e [92m `md5sum &ARCHIVO | cowsay `\e[0m"

done