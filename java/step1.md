

## Check that Java is installed
Just type the following command `java -version`{{execute}}


## Create a simple class



<pre class="file" data-filename="app.js" data-target="replace">class Test {
	public static void main (String ... args) {
		System.out.println("Hello World");
	}
}
</pre>



```
class Test {
	public static void main (String ... args) {
		System.out.println("Hello World");
	}
}

```{{open Test.java}}

## Compile and run the class

Java 11 introduced support for ... where you can simply invoke `java` to compile and run a given class.

`java Test.java`{{open}}


