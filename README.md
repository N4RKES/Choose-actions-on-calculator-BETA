# Choose-actions-on-calculator-BETA
//in prompt 1 = add, 2 = multiplication

let a = Number(window.prompt('Podaj pierwszą liczbę'));
let b = Number(window.prompt('Podaj drugą liczbę'));
let info = Number(window.prompt('Wpisz 1 jeśli chcesz dodać lub 2 jeśli chcesz pomnożyć podane liczby'));
function dodawanie(x,y) {
return x + y};
function mnożenie(x,y) {
return x * y };
function dzielenie(x,y) {
return x / y }
let c = dodawanie(a,b);
let d = mnożenie(a,b);
if (info != 1) {
    window.alert(String(a) + "*" + String(b) + '=' + String(d))
}
if (info != 2) {
    window.alert(String(a) + "+" + String(b) + '=' + String(c))
} 
