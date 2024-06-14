<h1 align="center">Learning Scala </h1>


## Installing the prerequisites

Go ahead and install these prerequisites if you haven't already.

* Install the [IntelliJ IDE](https://www.jetbrains.com/edu-products/download/#section=idea-Scala).
* [Install Scala](https://docs.scala-lang.org/getting-started/index.html#install-scala-on-your-computer).
  * This should install a JVM if you don't have one already.
  * You may have to restart your terminal for everything to work after this is done.

## Hello World

Let's begin with a simple Hello World.

Create a new directory for your project, and cd into it:
```
mkdir hello-world
cd hello-world
```

Now create a file for your code. In Scala, the directory structure is quite specific:
```
mkdir -p src/main/scala/
touch src/main/scala/Main.scala
```

`Main.scala` is the file where you'll write your code.

Open this file, and type in:

```scala
object Main extends App {
  println("Hello, World!")
}
```

In order to run your code, you'll have to create another file, called `build.sbt`.
```
touch build.sbt
```

You can now (build and) run your code by typing `sbt run`.
In IntelliJ, you could also run this code by clicking on the green ▶️ button next to the function.
