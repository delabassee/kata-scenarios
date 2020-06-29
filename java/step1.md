
<br/>
## Check that Java is installed
You first want to check that Java is correctly installed. The following command `java -version`{{execute}} should return of the version of Java installed.


## Create a HelloWorld application


Next we will create a simple HelloWorld. 
Create the following `Test.java` class in the editor.


<pre class="file" data-filename="Test.java" data-target="replace">class Test {
	public static void main (String ... args) {
		System.out.println("Hello World");
	}
}
</pre>



## Compile and run HelloWorld

To run a Java application, you first need to compile the source code using `javac`. You can then invoke that application using `java`.

<br>

Java 11 introduced support for [Launch Single-File Source-Code Programs](https://openjdk.java.net/jeps/330) where you can simply invoke `java` to compile and run a given class in a single step.

Invoke `java Test.java`{{execute}}

