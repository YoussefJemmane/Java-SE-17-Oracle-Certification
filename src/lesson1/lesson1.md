# Java SE 17 Oracle Certification - Lesson 1

This document outlines the steps taken to accomplish Lesson 1.

## Step 1: Verify Java Version

First, I opened the terminal and verified the version of Java installed on my machine.

```bash
$ java -version
```

## Step 2: Navigate to Project Directory

Next, I navigated to the project directory where I will be working on the Java SE 17 Oracle Certification.

```bash
$ cd /e/Code/Learn/Java\ SE\ 17\ Oracle\ Certifiacation/
```

## Step 3: Create a folder for Lesson 1 that contains Hello World.java file in the src directory

I created a folder named `Lesson1` and added a file named `HelloWorld.java` to it.

```bash
$ mkdir lesson1
$ touch lesson1/HelloWorld.java
```

## Step 4: Open File in Editor

I opened the `HelloWorld.java` file in my editor.

```bash
$ vim HelloWorld.java
```

## Step 5: View File Content

I viewed the content of the HelloWorld.java file.

```bash
$ cat HelloWorld.java
```

The content of the file was:

```java
package lesson1;

public class HelloWorld {
    public static void main(String[] args){
        System.out.println("Hello" + args[0]);
    }
}
```

## Step 6: Compile the File

I compiled the `HelloWorld.java` file.

```bash
$ javac -d ./classes ./src/lesson1/HelloWorld.java
```

## Step 7: Run the File

Finally, I ran the program.

```bash
$ java -cp ./classes lesson1.HelloWorld " Youssef Jemmane"
```

The output was:

```
Hello Youssef Jemmane
```