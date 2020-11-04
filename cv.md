# Михаил Александрович

> _за фронтенд и двор стреляю в упор_

## Контакты

- [MihailStar@mailforspam.com](mailto:mihailstar@mailforspam.com)
- [MihailStar@mailinator.com](mailto:mihailstar@mailinator.com)

## Стек технологий

- язык разметки **HTML** (~~Nunjucks~~ Pug)
- язык оформления **CSS** (~~Stylus~~ ~~Sass~~ SCSS, PostCSS)
- язык программирования **JavaScript** (Babel)

## Навыки

- программирую на HTML
- наверстываю упущенное
- применяю паттерны:
  - костылирование
  - инкостыляция
  - поликостылизм

## Опыт

- [codepen.io/MihailStar](https://codepen.io/MihailStar)
- [gist.github.com/MihailStar](https://gist.github.com/MihailStar)
- [github.com/MihailStar](https://github.com/MihailStar)

## Пример кода

```JavaScript
/**
 * @param {Array<number>} [preferences] indices of spichonees, whom they love
 * @return {number} number of love triangles
 */
const getLoveTrianglesCount = (preferences = []) =>
  preferences
    .map(preference => preference - 1)
    .reduce(
      (counter, preference, spichonee, array) =>
        preference !== spichonee && array[array[preference]] === spichonee
          ? counter + 1
          : counter,
      0
    ) / 3;
```

## Образование

- три класса церковно-приходской школы
- [htmlacademy.ru/profile/mihailstar](https://htmlacademy.ru/profile/mihailstar)
- [codewars.com/users/MihailStar](https://www.codewars.com/users/MihailStar)
