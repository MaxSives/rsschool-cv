# CV

1. Maxim Fiodarau
2. Contacts for communication

- Telephone: +375 (29) 811-26-12;
- Discord: MaksimFeodaray#4204;
- [VK](https://vk.com/maxsive);

3. At the moment, my goal is to learn a programming language for further employment in the company. I think my strong point is workaholism, which allows you to achieve your goal no matter what. I have no experience in programming, however, in addition to studying at RS-school, I also take other courses on JS on my own.
4. At the moment I have basic knowledge of programming HTML, SCC and JS.
5. Code example for the Guess the Number mini-game:

```<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Угадай число</title>
  </head>
  <body>
    <script>
      let randomValue = Math.floor(Math.random() * 101);
      let pop = 0;
      alert("Отгадай число от 0 до 100");

      while (true) {
        pop++;
        let value = prompt(
          "Угадай число. ВВеди значение или введи стоп для завершения"
        );
        if (value == "стоп") {
          break;
        }

        if (value > randomValue) {
          alert(`Загаданное число меньше чем ${value}`);
        } else if (value < randomValue) {
          alert(`Загаданное число больше чем ${value}`);
        }
        if (value == randomValue) {
          alert(
            `Угадал, правильное значение ${randomValue}. Угадал с ${pop} попытки`
          );
          break;
        }
      }
    </script>
  </body>
</html>
```
