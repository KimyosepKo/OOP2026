# OOP2026
### Homework1
```java
package homework;
public class Homework {
    public static void main(String[] args) {
        int i, j;

        for (i = 0; i < 10; i++) {
            for (j = 0; j <= i; j++) {
                System.out.print("#");
            }
            System.out.println();
        }

        System.out.println();

        for (i = 0; i < 10; i++) {
            for (j = 0; j < 10 - i; j++) {
                System.out.print("#");
            }
            System.out.println();
        }

        System.out.println();

        for (i = 0; i < 10; i++) {
            for (j = 0; j < 9 - i; j++) {
                System.out.print(" ");
            }
            for (j = 0; j <= i; j++) {
                System.out.print("#");
            }
            System.out.println();
        }

        System.out.println();

        for (i = 0; i < 10; i++) {
            for (j = 0; j < i; j++) {
                System.out.print(" ");
            }
            for (j = 0; j < 10 - i; j++) {
                System.out.print("#");
            }
            System.out.println();
        }
    }
}

```
![Alt homework1](./img/homework1.png)

### Homework2
```java
package homework;
public class Homework {
    public static void main(String[] args) {
        int a = 0, b = 1, c;

        for (int i = 0; i < 20; i++) {
            System.out.print(a + " ");

            c = a + b;
            a = b;
            b = c;
        }
    }
}
```
![Alt homework2](./img/homework2.png)

### Homework3
```java
package homework;

public class Homework {
    public static void main(String[] args) {
        int a = 0, b = 1, c;
        double ratio;

        for (int i = 1; i <= 20; i++) {
            c = a + b;
            a = b;
            b = c;

            ratio = (double) b / a;

            System.out.println(i + "번째 황금비율: " + ratio);
        }
    }
}
```
![Alt homework3](./img/homework3.png)

### Homework4
```java
package homework;

public class Homework {
    public static void main(String[] args) {
        int i, j;

        for (i = 1; i <= 9; i++) {
            for (j = 1; j <= 9; j++) {
                System.out.print(i + " * " + j + " = " + (i * j) + "\t");
            }
            System.out.println();
        }
    }
}
```
![Alt homework4](./img/homework4.png)

### Homework5
```java
package homework;

public class Homework {
    public static void main(String[] args) {
        double pi = 0.0;
        int sign = 1;

        for (int i = 0; i < 100000; i++) {
            pi += (double) sign / (2 * i + 1);
            sign = -sign;
        }

        pi = pi * 4;

        System.out.println("계산한 원주율: " + pi);
        System.out.println("실제 원주율: " + Math.PI);
    }
}
```
![Alt homework5](./img/homework5.png)

### Homework6
```java

```
![Alt homework6](./img/homework6.png)

### Homework7
```java

```
![Alt homework7](./img/homework7.png)

### Homework8
```java

```
![Alt homework8](./img/homework8.png)

### Homework10
```java

```
![Alt homework10](./img/homework10.png)

### Homework11
```java

```
![Alt homework11](./img/homework11.png)


### Homework13
```java

```
![Alt homework13](./img/homework13.png)
