// Blumenobjekt erstellen
class Blume {
    constructor(name, farbe, duft) {
        this.name = name;
        this.farbe = farbe;
        this.duft = duft;
    }

    // Methode, um die Blume zu beschreiben
    beschreiben() {
        return `Die ${this.name} ist ${this.farbe} und hat einen ${this.duft} Duft.`;
    }
}

// Instanzen von Blumen erstellen
const rose = new Blume('Rose', 'rot', 'angenehmen');
const tulpe = new Blume('Tulpe', 'gelb', 'leichten');

// Blumen beschreiben
console.log(rose.beschreiben());
console.log(tulpe.beschreiben());
