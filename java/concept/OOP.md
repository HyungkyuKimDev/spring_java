# OOP

## EX 1

- MotorBike.java

```java
package com.hk.oops;

public class MotorBike {
    private int speed;

    public void start() {
        System.out.println("Bike started!");
    }

    public void setSpeed(int speed) {
        this.speed = speed;
    }

    public int getSpeed() {
        return this.speed;
    }
}
```

- MotorBikeRunner.java

```java
package com.hk.oops;

public class MotorBikeRunner {
    public static void main(String[] args) {
        MotorBike ducati = new MotorBike();
        ducati.start();
        ducati,setspeed(-100);
        System.out.printf("Current Ducati Speed is : %d", ducati.getSpeed()).println();
    }
}

// Console Output
// Bike started!
// Current Ducati Speed is : -100
```