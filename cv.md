# Akaeva Diana

Frontend Developer

## Contact information

* **Email:** cheperish@mail.ru
* **GitHub:** [Encors](https://github.com/Encors)

## Skills

* HTML5, CSS3
* БЭМ (BEM)
* JavaScript
* React
* Webpack
* Git

## Courses

* [Web-разработчик](https://practicum.yandex.ru/profile/web/) — Яндекс Практикум
* [JavaScript Manual](https://learn.javascript.ru/) (in progress)
* [RS Schools Course — JavaScript/Front-end2023Q1](https://app.rs.school/) (in progress)

## English

B1 (according to the online test at EFset Logo www.efset.org)

## Code example

**"Playing with digits" KATA from CODEWARS:** 

> Given a positive integer n written as abcd... (a, b, c, d... being digits) and a positive integer p. We want to find a positive integer k, if it exists, such that the sum of the digits of n taken to the successive powers of p is equal to k * n.

```function digPow(n, p) {
  const arr = String(n)
    .split("")
    .map((item) => Number(item));

  let sum = 0;

  arr.forEach((int) => (sum += int ** p++));

  const k = Number.isInteger(sum / n);

  if (k) {
    return sum / n;
  } else {
    return -1;
  }
}
```
