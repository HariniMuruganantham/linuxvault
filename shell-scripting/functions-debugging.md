# Functions and Debugging

Functions help in organizing shell scripts.

---

## Creating a Function

function greet() {  
    echo "Hello World"  
}

Call function:

greet

---

## Debugging Scripts

Enable debug mode:

$ set -x

Stop debug mode:

$ set +x

Exit script on error:

$ set -e
