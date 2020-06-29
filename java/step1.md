

## Check that Java is installed
Just type the following command `java -version`{{execute}}


## Create a simple class


Create the following `Test.java` class in the editor.


<pre class="file" data-filename="Test.java" data-target="replace">class Test {
	public static void main (String ... args) {
		System.out.println("Hello World");
	}
}
</pre>



## Compile and run the class

Java 11 introduced support for ... where you can simply invoke `java` to compile and run a given class.

Invoke `java Test.java`{{execute}}


