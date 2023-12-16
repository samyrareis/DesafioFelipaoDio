// Definindo o XP do herói Blaze Avenger
const xpBlazeAvenger = 1500;

// Função para classificar o nível com base no XP
function classificarNivel(xp) {
    if (xp >= 5001 && xp <= 8000) {
        return "Platina Diamante";
    } else if (xp >= 1001 && xp <= 2000) {
        return "Bronze";
    } else {
        return "Nível não classificado";
    }
}

// Obtendo o nível do herói Blaze Avenger
const nivelBlazeAvenger = classificarNivel(xpBlazeAvenger);

// resultado
console.log(`O herói Blaze Avenger está no nível: ${nivelBlazeAvenger}`);