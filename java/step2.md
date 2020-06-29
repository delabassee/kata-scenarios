
<br/>
## Java 15
Java 15 comes with a bunch a features. We will introduce [Text Blocks](https://openjdk.java.net/jeps/378) into our HelloWorld application.




## Exerice - Add Text Block support


Adjust the exsiting code to display the new message that uses text block.

```
var msg = """
   H
    e
     l
      l
       o

         W
          o
           r
            l
             d
   """;
```

:warning: When running your application, you might get an error that says that you are trying to use a preview feature... blabla old OpenJDK 15 version... Text Block are standard in Java 15... blabla

To woraround the issue, type `java  --enable preview  --source 15 Test.java`{{execute}}
