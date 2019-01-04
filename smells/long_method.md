---
title: Sample Smells
description: Long Method
layout: smells
---

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

Note that long method doesn't necessarily have many lines
