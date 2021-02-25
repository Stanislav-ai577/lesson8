1. Mixin - изучить.
2. подкасты веб-стандарт,Хекслет.
3. 2-ой час занятия идеальное высчитывание шрифта при мобильной вёрстке.

//task 2 js lesson 8

function User(name, finalName) {
    this.hello = function() {
        console.log(`hello, ${name} ${finalName}`);
    }
};
let user = new User('Дмитрий', 'Александрович');
user.hello();
