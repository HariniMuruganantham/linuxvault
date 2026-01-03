# Conditions and Loops

Shell scripts use conditions to make decisions and loops to repeat actions.

---

## if Condition

Syntax:

if [ condition ]; then  
    commands  
fi

Example:

if [ $a -gt $b ]; then  
    echo "a is greater"  
fi

---

## for Loop

for i in 1 2 3  
do  
    echo $i  
done

---

## while Loop

while [ $a -lt 10 ]  
do  
    echo $a  
    a=`expr $a + 1`  
done

---

## case Statement

case $var in  
1) echo "One" ;;  
2) echo "Two" ;;  
*) echo "Other" ;;  
esac
