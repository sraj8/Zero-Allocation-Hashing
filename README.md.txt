# README #

This README would normally document whatever steps are necessary to get your application up and running.

### What is this repository for? ###

The project contains APIs that can be used to hash various data types in Java. This project contains different hashing functions like xxHash, FarmHash, CityHash and MurmurHash3.

### How do I get set up? ###

Open the project in IntelliJ IDE, Open tool windows for Gradle and SBT (it can be accessed via view --> Tool Windows).

* Dependencies - junit (4.12), guava (18.0/19.0) 
* SBT compile can be done by following ways:
	Using 'compile' command under SBT Task in Tool Windows
	Creating a new configuartion (Run --> Edit Configuration --> + SBT--> 'compile' / 'clean compile' as task)
* Gradle build can be done by following ways:
	Using 'build' command under Gradle Task in Tool Windows
	Creating a new configuartion (Run --> Edit Configuration --> + Gradle--> 'build' / 'clean build' as task)
	Right click on build.gradle and select Run 'build'
* Tests can be run by following ways:
	By right clicking on the test folder (under src/test) and select Run 'All Tests'
	Creating a new configuartion (Run --> Edit Configuration --> + Gradle/SBT--> 'clean test' as task)

### Contribution guidelines ###

* Additonal 3 test (classes) have been added:

1. HashValCompareTest.java :- To test whether the hash values obtained using various hashing methods using the same keys is unique and different
2. XxHashArrayCollisionTest.java :- To test whether the hash values of the elements in the two arrays (hashes of hexadecimal numbers multiplied by different numbers ) are same or different
3. xxHashSeqValTest.java :- To test whether the hash value is not null when the input string is empty.

### What can be infered from the JConsole, Java VisualVM, visualgc screen shots captured? ###

