# Git_Devops
# SIMPLE SCRIPT PROGRAM
#!bin/bash
echo "Enter the score"
read x
if [[ $x -eq 90 ]];
then
echo "you have a one peg down"
else if [[$x -eq 60 ]];
then "you have two peg down"

else if [[$x -eq 30 ]];
then "you have three peg down"
else
echo "please try again"
fi

