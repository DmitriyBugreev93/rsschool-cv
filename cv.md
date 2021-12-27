# **Bugreev Dmitriy**     
### Junior Frontend Developer

---

## **_My contacts :_**
  * **Phone:** +998-90-908-91-78
  * **GitHub:** DmitriyBugreev93
  * **Discord:** DmitriyB#8492
  * **E-Mail:** dmitriy.darya@gmail.com

---

## **_About me :_**

  Started studying programming at ProWeb courses in Uzbekistan. I began to independently study web design, and take an interest in additional tools related to front-end development. In the end, I enjoyed programming. At the moment, I am still studying at ProWeb, and at the same time I got a job as a junior front-end developer in a local company, and also started the "RSSchool" course for learning JavaScript.
I try to develop my skills and knowledge.

---

## **_Skills :_**

  + HTML
  + CSS (SCSS/SASS; Bootstrap)
  + JavaScript 
  + Gulp
  + Git/GitHub
  + VSCode/Figma

---

## **_Code example :_**
 
  Using the `for` loop, we created random examples with the conclusion of a correct and incorrect solution.
  ```
let numberOfexamles = +prompt('Введите количество примеров');
let max = +prompt('Введите макс. число');
let min = +prompt('Введите мин. число');
function randNum(max, min) {
    let randomNum = Math.floor(Math.random() * (max + 1 - min)) + min;
    return randomNum;
}
for (let i = 0; i < numberOfexamles; i++) {
    let num1 = randNum(max, min);
    let num2 = randNum(max, min);
    var operators = [{
        sign: "+",
        method: function (a, b) {
            return a + b;
        }
    }, {
        sign: "-",
        method: function (a, b) {
            return a - b;
        }
    }, {
        sign: "*",
        method: function (a, b) {
            return a * b;
        }
    }, {
        sign: "/",
        method: function (a, b) {
            return a / b;
        }
    }];
    var selectedOperator = Math.floor(Math.random() * operators.length);
    var ant = operators[selectedOperator].method(num1, num2);
    let total = prompt(num1 +  operators[selectedOperator].sign  + num2);
    if (total == ant){
        alert('Ваш ответ верный ' + total + ' Правильный ответ: ' + ant);
    } else {
        alert('Ваш ответ не верный ' + total + ' Правильный ответ: ' + ant)
    }
}
```
---
  
## **_Education and courses :_**

+ **Mirzo-Ulugbek Professional College Information :**
  + computer design and graphics

+  **Pro Web courses**
   + Html 
   + Css (SASS/SCSS)
   + Bootstrap
   + JavaScript
   + Git
   + PHP

---

## **_Languages :_**
  + Russian - Native
  + Deutsch - B1
  + English - primary-secondary

---