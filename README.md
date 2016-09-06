# Jurassic Word

Jurassic Word is full of wonderful prehistoric creatures...eating a lot. In this kata your task is to take in a lunchtime scene of a dinosaur and their food, and decipher exactly what ate what.

Now, there isn't much mystery in what a dino might be eating. It can be one of:

```
dead_dino = "_C     C}>";
flowers = "iii     iii";
leaves = "|||     |||";
```
These empty spaces in the middle of each food are reserved for the bitemarks made by a dinosaur, which will always be 5 characters long.

Unfortunately, you don't get to see the action. You have to look at the bite marks made on the leftovers, and make your judgement that way.

There are four kinds of dinosaurs in the park that you know of:

```
T_Rex = "VvvvV"; 
brachiosaurus = "uuuuu";
velociraptor = "vvvvv";
triceratops = "uuVuu";
```

Although a dinosaur will be eating one of the three available foods, some dinosaurs will only eat certain items. For example, both the brachiosaurus and the triceratops are vegetarians and would love to eat flowers. On the other hand, the T-Rex and the velociraptor would only want to eat dead dinos. Thus, if you see their bitemarks on a food that you know they wouldn't be eating, you must be mistaken..

* * * *


Here are a few examples of how your program should work:

```
lunchTime("_CVvvvVC}>") should give: "A T-Rex is eating a dead dino."
lunchTime("_CvvvvvC}>") should give: "A velociraptor is eating a dead dino."
lunchTime("iiiuuVuuiii") should give: "A triceratops is eating flowers."
lunchTime("|||uuVuu|||") should give: "Something is eating leaves."
lunchTime("_CVvVvVC}>") should give: "Something is eating a dead dino.`
```


This exercise was taken from [Codewars](https://www.codewars.com/)

