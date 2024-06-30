# Vitmaer Evgeniy

# My contacts

- **E-mail:** masic135@mail.ru
- **Vkontakte:** https://vk.com/zvitmaer
- **Telegram:** @Drafmir_mol

# Briefly about me

My desire to study web development is to gain knowledge that will allow me to get a stable job. I am interested in algorithms, I like to understand and write code that works as planned.

I've had experience in front-end content development for about six months. I was hired after an internship, where I got acquainted with the Angular framework. After that, I developed on it, worked in a team, and actively used the git and github system. However, there was no proper control over my development, so the code, the names of variables, functions, classes, etc., as well as the names of commits left much to be desired.

Now I want to thoroughly study the frontend development base and immerse myself in this topic without ceasing to constantly develop.

# Skills

- Basic HTML5
- Basic CSS3
- Basic JavaScript
- Basic Git and GitHub

# Code examples

The code below was written during the development of a small application to generate a random color. It allows you to choose white or black font color depending on the brightness of the background color for better readability.

```
function brightnessCalculation(color) {
  const red = parseInt(color.slice(1, 3), 16);
  const green = parseInt(color.slice(3, 5), 16);
  const blue = parseInt(color.slice(5), 16);

  const relativeRed = Number((red / 255).toFixed(5));
  const relativeGreen = Number((green / 255).toFixed(5));
  const relativeBlue = Number((blue / 255).toFixed(5));

  const L =
    0.2126 * RGBCalculation(relativeRed) +
    0.7152 * RGBCalculation(relativeGreen) +
    0.0722 * RGBCalculation(relativeBlue);

  return L.toFixed(5);
}

function RGBCalculation(valueColor) {
  return valueColor <= 0.03928
    ? valueColor / 12.92
    : Math.pow((valueColor + 0.055) / 1.055, 2.4);
}
```
