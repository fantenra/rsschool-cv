# Anastasiya Shalaeva

age 28, junior front-end developer
Kaliningrad, Russia

## Contacts
email: fa.nten.ra@gmail.com  
tel: +79005636284

## A few words about me
I’m a junior web developer. At the moment I work in a local web-studio. Our projects rather small and standard solutions. I realized that I need to grow because I want to be involved in interesting projects, which can make the IT industry and people's lives better. So I joined the Rolling Scopes School and I am now on my way up to the front-end developer. IT and especially web development industry growing very fast. It requires many personal skills to keep up. I consider myself responsible and patient. 

## Skills
* HTML5  
* CSS  
* SCSS  
* BEM  
* Adaptive layout  
* Git  
* Gulp

## Code examples

[Codepen flex grid blocks pure css](https://codepen.io/fantenra/details/qxjvbg)  
Search and highlight a specific word:
 ```
function search(a) {
    var words = a;

    var content = document.querySelector('body');
    var textContentAll = content.querySelectorAll('p, h1, h2, h3, .section-title, .font-change, .format-text');

    for (var i = 0; i < textContentAll.length; i++) {
      var elem = textContentAll[i];
      var textString = elem.innerHTML;

      var result = textString.replace(new RegExp(words, 'g'), "<span class='mont'>" + words + "</span>");
      textString = result;
      elem.innerHTML = result;
    }
  }
  search('word');
 ```

## Experience
| Position | Place | Date |
| ---------| ----- | ---- |
| Junior web developer | Cody Art Studio | Sep 2015 - to the present |
| Trainee web developer | Multitsite | Apr 2013 - Feb 2014 |

## Education
Kaliningrad State Technical University (KSTU)  
Faculty of Production Automation and Control  
Department of Control Systems and Computer Engineering

### Courses
* Codecademy Introduction to HTML  
* Codecademy Learn CSS  
* Wes Bos CSS Grid  

## English level
Russian - native  
English - B2