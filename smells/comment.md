---
title: Sample Smells
description: Comment
layout: smells
---

````csharp
    // An implementation of the Hardy 
    // debt calculation method on p34
    // of "Finiancial Instruments" 
    // by H & L Fineman, 1993.
    public class DebtCalculator {
        ...
    }
````

````csharp
    private double rt;  // The calculation rate
    private double acc; // The accumulator 
````

````csharp
    public DoLotsOfStuff(x, y, z) {
        // First check that all the data is clean
        if( x == null || y ==null || z == null ){
            throw new Exception("values must have a value");
        }

        // Then calculate the ratios
        var i = 0;
        var ratio = 3.2;
        while( i < 100 ) {
            i = i + ( y / 10);
            ratio += i / x;
        }
        var offset = z;
        if( x > 34.5 ) {
            offset = z * 1.2;
        }

        // 3. Combine the data
        var result1 = ratio * x;
        var result2 = x + y / z;

        // Finally add up all the parts
        return result1 + result2 + offset * 100.0;
    }
````