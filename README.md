#!/bin/bash


#enter the directory

cd /home/ubuntu/Documents/


 a=$(ls)

i=1

for file in $a

 do

           name="bi190$i.txt" 

           mv $file Sname

           num=$(($i+1)) 

           i=$num

cp /home/ubuntu/Documents/*.txt /home/ubuntu/Mah19/

done
