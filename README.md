# Martian

----
## Contents
1. [Introduction](#introduction)
2. Dummy programs
  1. [answer.pseduo](#answer.pseduo)

## Introduction

This repository is created to create dummy programs for test purpose.

---
### i. answer.pseudo

Dummy node.js application containing a function(```play()```) that takes a variable name as parameter and generates a random number between 6 and 15 and return the result in this format: “Name GeneratedNumber”. Eg: “Rahul 11”

#### How to run
```
node answer.pseduo
```

For testing, uncomment the test script at the end of file.

```javascript
for (var i = 10; i > 0; i--) {
    console.log(play('Rahul'));
}
```
