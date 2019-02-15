---
title: Sample Smells
description: Primitive Obsession
layout: smells
---

```csharp
public class Contact(){
    string cell;
    string work;
    string address1;
    string address2;
    string city;
    string country;
    string zipcode;
    ...
}
```





vs.

```csharp
public class Contact(){
    PhoneNumber cell;
    Address homeAddress;
    Address workAddress;
    ...
}

public class PhoneNumber(){
    Digit3 areaCode;
    Digit7 localNumber;
    ...
}

public class Address(){
    int streetNumber;
    string? unitName
    string streetName;
    string suburb;
    City city;
    ...
}
```