# scala-design-patterns-v2

This repository contains design patterns implemented in the Scala programming language for the Scala Design Patterns - Second Edition book.
The code examples in the second edition of this book were written using both Maven and SBT
as build tools.

### Project Structure

The source code is available in both Maven and SBT under the following sub-folders:
* [scala-design-patterns-v2-mvn](scala-design-patterns-v2-mvn)
* scala-design-patterns-v2-sbt (Soming soon)

The examples are identical in both Maven and SBT as one would expect. The only difference is
the build tool, which is up to your personal preference.

> Note: The unit tests in the Maven project are slightly different, because every class is
annotated with `@RunWith(classOf[JUnitRunner])`. The reason for this is that `junit` is used to
execute the tests with Maven.

There is a separate module for each topic/chapter covered in the book:
1. Chapter 1: The Design Patterns Out There and Setting Up Your Environment
   There is no code for this chapter. It provides the readers with some useful skeletons.
2. Chapter 2: Traits and Mixin Compositions
   - mvn module name [traits](scala-design-patterns-v2-mvn/traits)
3. Chapter 3: Unification
   - mvn module name [unification](scala-design-patterns-v2-mvn/unification)
4. Chapter 4: Abstract and Self Types
   - mvn module name [abstract-types](scala-design-patterns-v2-mvn/abstract-types)
5. Chapter 5: Aspect-Oriented Programming and Components
   - mvn module name [aop](scala-design-patterns-v2-mvn/aop)
6. Chapter 6: Creational Design Patterns
   - mvn module name [craational-design-patterns](scala-design-patterns-v2-mvn/creational-design-patterns)
7. Chapter 7: Structural Design Patterns
   - mvn module name [structural-design-patterns](scala-design-patterns-v2-mvn/structural-design-patterns)
8. Chapter 8: Behavioral Design Patterns - Part One
   - mvn module name [behavioral-design-patterns](scala-design-patterns-v2-mvn/behavioral-design-patterns)
9. Chapter 9: Behavioral Design Patterns - Part Two
   - mvn module name [behavioral-design-patterns](scala-design-patterns-v2-mvn/behavioral-design-patterns)
10. Chapter 10: Functional Design Patterns - the Deep Theory
    - mvn module name [deep-theory](scala-design-patterns-v2-mvn/deep-theory)
11. Chapter 11: Applying What We Have Learned
    - mvn module name [functional-design-patterns](scala-design-patterns-v2-mvn/functional-design-patterns)
12. Chapter 12: Real-Life Applications
    - mvn module name [real-life-applications](scala-design-patterns-v2-mvn/real-life-applications) and 
    module name [job-scheduler](scala-design-patterns-v2-mvn/job-scheduler)
   
### Running the Code

Clone this repository. You can run the code using an IDE such as IntelliJ or you can
use Maven or SBT in the command line to build the jars with the examples.

#### Compiling the Projects

- mvn: `mvn clean compile` from the [scala-design-patterns-v2-mvn](scala-design-patterns-v2-mvn) folder.
- sbt: coming soon

#### Running the Unit Tests

- mvn: `mvn clean test` from the [scala-design-patterns-v2-mvn](scala-design-patterns-v2-mvn) folder.
- sbt: coming soon

#### Creating the Jars

- mvn: `mvn clean package` from the [scala-design-patterns-v2-mvn](scala-design-patterns-v2-mvn) folder.
- sbt: coming soon

The `package` command will build jars inside the **target** folder of each submodule.
