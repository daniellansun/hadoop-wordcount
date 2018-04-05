# hadoop-wordcount
Word counting example for hadoop 3.0 with gradle.

### Prerequisites
* Windows 10
* JDK 8
* Gradle 4.6
* Hadoop 3.0.1

### Setup
1. download [hadoop 3.0.1](http://www.apache.org/dyn/closer.cgi/hadoop/common/hadoop-3.0.1/hadoop-3.0.1.tar.gz)
2. set the environment variable "HADOOP_HOME" and "PATH", e.g.
    ```bat
    SET HADOOP_HOME=D:\_DEV\hadoop-3.0.1
    SET PATH=%PATH%;%HADOOP_HOME%\bin;
    ```
3. extract the [winutil](https://github.com/steveloughran/winutils) binary files(`winutils.exe`, `hadoop.dll`) to `%HADOOP_HOME%\bin`

### Run:
#### example in Java
```bat
gradlew runJar
```
#### example in Groovy
```bat
gradlew runGroovyJar
```
