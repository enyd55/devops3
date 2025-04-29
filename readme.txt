freestyle:
Source Code Management
  SELECT        git
  Repository URL              https://github.com/enyd55/devops3.git

Triggers
  SELECT        poll SCM
  SEHEDULE     H/2 * * * *


BUILD STEPS:
  javac add.java
  java add




public class add {
    public static void main(String[] args) {
        int a = 5, b = 10;
        int sum = a + b;
        System.out.println("Sum: " + sum);
    }
}
