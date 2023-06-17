#### spring commands

`
export JAVA_HOME=/Library/Java/JavaVirtualMachines/jdk-17.0.2.jdk/Contents/Home/
export PATH=/Library/Java/JavaVirtualMachines/jdk-17.0.2.jdk/Contents/Home/bin/:$PATH
`


### find all java local machine
`
mdfind -name 'java' | grep '/bin/java$' 
`
