# Kseniya Pereguda

## Contacts:

* location: Minsk, Belarus;
* phone: +375 29 111-11-11;
* e-mail: ksyusha_pereguda@mail.ru;
* GitHub: KseniyaPereguda;

## About me

I am a self-motivated and responsible person who can work well alone or in a team. I have good listening and communication skills. I am always ready to develop new skills.

## Skills

* HTML
* CSS
* JavaScript (Basic)
* GIT, GitHub
* Figma, Photoshop

## Code example 
```
let win = [];
let sum = 0;
let userSolution = true;
function winningAmount(win) {
for (let i = 0; i &lt; 30; i++) {
    let randomAmount = -500 + Math.floor(Math.random() * (500 - -500 + 1));
    win.push(randomAmount);
}
return win;
}
winningAmount(win);
do {
let userAnswer = prompt('Введите номер от 1 до 30');
sum += win[userAnswer - 1];
alert(`Ваш выигрыш составляет: ${win[userAnswer - 1]}, итоговый выигрыш составляет: ${sum}`)
userSolution = confirm('Хотите продолжить игру?');
} while (userSolution);
```
## Education

University: VSMU
## Languages

* Russian (Native)
* English (A2)
