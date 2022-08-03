# 1. Introduction
shell type supported:  
```
cat /etc/shells 
```

locate bash: 
```
which bash
```

## Hello World: 

1. Create the sh file: 
```
touch hello.sh 
```

2. edit the sh file: 
```
#! /bin/bash 
# ^ let the interpreter know that this is for bash 
echo "Hellow Word"
```

3. Enable execute permission: 
```
chmod +x hellow.sh 
```

4. Run the shell script: 
```
./hello.sh
```

# 2. Comments and Variables
## 2.1 Comment 

```
# single line comment 
echo "hello" # another single line comment
```

## 2.2 Variables 

### System Variables 
variable name in CAPITAL cases 

```
echo our shell name is $BASH 
```

```
echo shell version is $BASH_VERAION
```

```
echo our home directory is $HOME
```

```
echo the present working directory is $PWD 
```


### User Defined Variables 

 - variable name should not start with number 
 - there is no " " before and after the = sign 
 
```
my_variable=value 
echo $my_variable
```

# 3. Read user input 


