# Zadanie21.
<img width="700" height="847" alt="image" src="https://github.com/user-attachments/assets/5d41059f-aa93-4195-bf1b-344b50d29ba8" />
<img width="618" height="784" alt="image" src="https://github.com/user-attachments/assets/cfcfa359-d4d9-4fa7-a529-e25bbe44201e" />

let input = prompt("Podaj liczbę całkowitą:");
let liczba = parseInt(input);

// Sprawdzenie czy liczba jest poprawna
if (isNaN(liczba)) {
    console.log("To nie jest poprawna liczba całkowita!");
} else {
    console.log("Wprowadzona liczba:", liczba);
    console.log("Liczba o znaku przeciwnym:", -liczba);
    console.log("Liczba +15:", liczba + 15);
    console.log("Liczba +0.5:", liczba + 0.5);
    console.log("Kwadrat liczby:", liczba * liczba);
    console.log("Dzielenie przez 2:", liczba / 2);
    console.log("Reszta z dzielenia przez 2:", liczba % 2);
    console.log("Liczba +1:", liczba + 1);
    console.log("Liczba -1:", liczba - 1);
    console.log("Dzielenie przez 3 (w dół):", Math.floor(liczba / 3));
    console.log("Dzielenie przez 3 (w górę):", Math.ceil(liczba / 3));
    console.log("Dzielenie przez 3 (zaokrąglone):", Math.round(liczba / 3));
    console.log("Pierwiastek:", Math.sqrt(liczba));
    console.log("Iloczyn z losową (0-50):", liczba * Math.floor(Math.random() * 51));
    console.log("Wartość absolutna:", Math.abs(liczba));
}
