# Konstantin Shcherban
**Software Developer**

![Me](photo.jpg)
## Contacts
* LinkedIn: [shcherban](https://www.linkedin.com/in/shcherban/?locale=en_US)
* Telegram: [konstantin_shcherban](https://t.me/konstantin_shcherban)
* X: [shcherban_en](https://twitter.com/shcherban_en)
* Discord: kst82364

## About Myself
I'm a C# developer mostly experienced in desktop applications for Windows, but intended to focus on web. I have back experience in web development with PHP and JavaScript. My immediate plan is to refresh and strengthen my front-end skills.

## Skills
* C#
* JavaScript

## Code Examples
Array.diff KATA from CODEWARS (6 kyu):
*Implement a function that computes the difference between two lists. The function should remove all occurrences of elements from the first list (a) that are present in the second list (b). The order of elements in the first list should be preserved in the result.*
### C#
```
using System.Linq;

public class Kata
{
  public static int[] ArrayDiff(int[] a, int[] b)
  {
    var query =
      from x in a
      where !b.Contains(x)
      select x;
    return query.ToArray();
  }
}
```
### JavaScript
```
function arrayDiff(a, b) {
  let res = Array.from(a);
  b.forEach( (nB) => {
    res = res.filter( (nR) => nR !== nB );
  });
  return res;
}
```

## Work Experience
### August 2021 — currently
**Programmer** | *Moscow Jewelry Factory*

Developed a POS solution for jewelry shop (C#, WPF, SQL), integrated tax-free functionality (C#, JavaScript), developed an application for interchanging with government control system for precious metals and precious stones market (С#, SQL).

### May 2018 — august 2021
**Engineer/programmer** | *SPE Salyut JSС*

Development of web application for river information services (HTML, CSS/Sass, JavaScript, PHP, jQuery, Vue.js, Leaflet.js, Firebase, Gulp).

### April 2017 — april 2018
**Engineer** | *Krylov State Research Centre*

Prototyping, design and development of desktop and mobile applications for maritime information systems. (Photoshop, Inkscape, C#, WPF).

### December 2012 — march 2017
**Software developer** | *CSRI Kurs JSC*

Working on software components of information system for skippers on river transport (C#, WPF). Have developed simulator of vessel GPS-receiver for testing (C++).

## Education
**Moscow Aviation Institute** (graduated in 2004)

Engineer's degree, Informatics and control in engineering systems

## English Level
Intermediate ([Skyeng Certificate](https://skysmart-core.skyeng.ru/general/v1/certificates/366092/d09f341d0c1dffb162e58d1757d91155023b54510d49a732b7a0698bf8a08b46?source=lesson))