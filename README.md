# devops-lab1

Lab work for practicing Git and GitHub Actions.

## Contents
- Java program `HelloDevOps.java`
- GitHub Actions workflow (`.github/workflows/ci.yml`) that compiles and runs the program

## How to run locally
```bash
javac src/main/java/com/yerassyl/HelloDevOps.java
java -cp src/main/java com.yerassyl.HelloDevOps
```
CI

On every push or Pull Request, GitHub Actions automatically:
	1.	Checks out the project
	2.	Sets up JDK 21
	3.	Compiles HelloDevOps.java
	4.	Runs it and prints the result in the Actions logs