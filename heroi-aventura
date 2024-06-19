// Definição da classe Heroi
class Heroi {
  // Construtor para inicializar as propriedades da classe
  constructor(nome, idade, tipo) {
    this.nome = nome;
    this.idade = idade;
    this.tipo = tipo;
  }

  // Método para realizar o ataque
  atacar() {
    let ataque;
    
    // Estrutura de decisão para definir o ataque conforme o tipo do herói
    switch (this.tipo) {
      case 'mago':
        ataque = 'usou magia';
        break;
      case 'guerreiro':
        ataque = 'usou espada';
        break;
      case 'monge':
        ataque = 'usou artes marciais';
        break;
      case 'ninja':
        ataque = 'usou shuriken';
        break;
      default:
        ataque = 'fez um ataque desconhecido';
    }
    
    // Exibe a mensagem do ataque
    console.log(`O ${this.tipo} atacou usando ${ataque}`);
  }
}

// Exemplos de uso:

// Criando instâncias da classe Heroi
const heroi1 = new Heroi('Arthas', 30, 'guerreiro');
const heroi2 = new Heroi('Merlin', 150, 'mago');
const heroi3 = new Heroi('Ryu', 25, 'monge');
const heroi4 = new Heroi('Naruto', 20, 'ninja');

// Chamando o método atacar para cada herói
heroi1.atacar();  // Saída: O guerreiro atacou usando espada
heroi2.atacar();  // Saída: O mago atacou usando magia
heroi3.atacar();  // Saída: O monge atacou usando artes marciais
heroi4.atacar();  // Saída: O ninja atacou usando shuriken
