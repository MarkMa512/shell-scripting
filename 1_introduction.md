# Introduction
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
