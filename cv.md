1. __Dmitry Lugovsky__
2. * Email: dim56026257@yandex.ru
   * Phone: +375 (33) 349-45-24
   * Telegram: [Dmitry](https://t.me/dimastys)
3. I want to study JavaScript very deeply and write some website completely on it.
4. Skills: HTML5, CSS3, JS (ES2015), Bootstrap 4, jQuery.
5. Code exampe: from [codewars](https://www.codewars.com/kata/520b9d2ad5c005041100000f/javascript)
```javascript
function pigIt(str){
  let result = str.split(' ').map(elem => {
      let regexp = /[!?,.]/;
      if(!regexp.test(elem)) {
        let letters = elem.split('');
        [letters[0], letters[letters.length]] = [letters[letters.length], letters[0]];
        letters.push("ay");
        return letters.join('');
      } else {
        return elem;
      }
    });
  return result.join(' ');
}
```
6. Experience about 1 year ([codewars](https://www.codewars.com/users/Dimastus), [github](https://github.com/Dimastus), [codepen](https://codepen.io/dimastus/)).
7. English level: beginner.