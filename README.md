# prakticheskaya-js

console.log('hi world');

console.log(70000000+20000000);

let kolichestvo_zadach = 4*4;
let kolichestvo_dney = 5*4;
console.log(kolichestvo_zadach - (kolichestvo_dney/2));


console.log(20%3);

alert('Прочти меня и сразу же закрой');

console.log('пяти'+'этажка');

console.log('Владивосток'+' '+'200');

console.log('Первое произведение А.С Пушкина было опубликовано в ${1799+15}');

let fahrenheit = 451;

let celsius = (fahrenheit - 32)/18;

console.log(fahrenheit + 'градуса по фаренгейту - это ' + celsius + 'градуса по Цельсию');


console.log('смесь правды и лжи' === 'всё равно враньё');

if(2020%4==0){
    console.log('2020 високосный год')
} else {
    console.log('2020 невисокосный год')
};


if(2009%4==0){
    console.log('2009 високоснвй год')
} else{
    console.log('невисокосный год')
}

if((year%400===0)||(year%4===0)&&!(year%100===0))
    {
        console.log('год високосный');
    } else {
        console.log(year + 'год невисокосный')
    }

let zadachi = ['Встать с кровати','Почтстить зубы','Проверить сториз','Позавтракать'];
console.log(zadachi);

console.log(zadachi[0], zadachi[zadachi.length]);


zadachi[2] = 'Сделать зарядку';
console.log (zadachi);

for(i = 0; i<=zadachi.length; i=i+1)
{
    console.log(zadachi);

}


for(i = 0; i<=zadachi.length; i=i+2)
{
    console.log(zadachi);

}


let i = 0;
while (i<=zadachi.length)
{
    console.log(zadachi);
    i++;
}


let y = 0;
for(i = 0;i<3;i++)
{
     increaseCounter(y);
     console.log(y)
}

isLeapYear(year)
{
    if((year%400===0)||(year%4===0)&&!(year%100===0))
    {
        return('год високосный');
    } else {
        return(year + 'год невисокосный')
    }
}

isLeapYear(2020);
