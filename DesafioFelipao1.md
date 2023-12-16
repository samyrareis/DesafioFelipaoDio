// XP do herói Blaze Avenger
const xpBlazeAvenger = 6500;

// Verificando o nível do herói com base no XP
if (xpBlazeAvenger >= 5001 && xpBlazeAvenger <= 8000) {
    console.log("Blaze Avenger está no nível Platina Diamante!");
} else if (xpBlazeAvenger >= 1001 && xpBlazeAvenger <= 2000) {
    console.log("Blaze Avenger está no nível Bronze!");
} else {
    console.log("Blaze Avenger está em um nível não classificado.");
}