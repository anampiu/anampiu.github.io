---
layout: post
title: Let's go fishing.
---

Private variables...we need 'em. Case in point, your bank balance in your bank's system might look something like this

```java
private int bankBal;
```

and that's good, some data should be hidden from the rest of the program, Encapsulation. The question then is, how does the program use the data if it can't find it? getters and setters...that's their cue!

What these daring duo do is quite simple. The getter method gains access to the private variable with controlled rights, and as for the setter, its work is to set a new value to the variable that is from the get method.

Let's make it a little visual...

```java
//this is how a set method would look like
public void setbankBal(){
    setbankBal();
}

//as for get method, it comes with a return type
public int getbankBal(){
    return bankBal;
}
```

Use this two for sensiteve data in your program. It's like magic, as always!

#### Challange:

Try and make a banking system that doesn't show your balance, but can debit and credit your account.