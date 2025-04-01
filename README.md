# Revisao para prova
### Atividade em sala para revisar conteúdos da prova do dia 04 com objeto de apoio sendo um dinossauro. Perguntas estão no drive da semana 9 e as respostas estão no readme.md

### Atividade de Programação - 01/04

1.
a) nome, espécie e idade

b) Com o extends, ocorre a herança dos atributos (nome, espécie e idade) e método exibirInformacoes da superclasse e a ampliação do atributo habitat e do método exibirHabitat

2.
c) A subclasse AnimalSelvagem herda atributos e métodos da superclasse Animal

d) Com super(...), o método construtor da superclasse AnimalSelvagem é acionado e os atributos e métodos são herdados para a subclasse AnimalSelvagem da superclasse Animal

3.
e) O objeto animal2 da classe AnimalSelvagem é criado pela recurso new do construtor da classe cos os parâmetros declarados. Assim, os atributos da classe AnimalSelvagem recebem como valor os parâmetros declarados e, com a chamada do método da exibirHabitat(), a função é executada com os valores declarados pelo objeto

f) Objeto1 e objeto2 são diferentes objetos, com diferentes parâmetros e de diferentes classes. O Objeto 1 declara parâmetros que substituiram atributos apenas da classe Animal, já o objeto2, com seus parâmetros substituirá os atributos da classe AnimalSelvagem e Animal, já que a classe AnimalSelvagem é uma subclasse da superclasse Animal. Assim, seus parâmetros poderão substituir os atributos da classe Animal e o atributo habitat da subclasse, portanto, poderá substituir o método de exibirinformações  exibirHabitat.

4.
g) Caso ocorrerá métodos com chaves iguais na superclasse e na subclasse, como essa situação, já que o JS não possui sobrecarga de método, o método na subclasse irá substituir a da superclasse, além de com o método construtor e o recurso extends a subclasse herde atributos e métodos, como esse caso, da superclasse

h) Não, pois o método exibirHabitat() pertence a um escopo inferior (subclasse), já o objeto animal1 pertence a um escopo maior (superclasse)

5.
i) Com a sobscreção de método e a herança de atributos, a herança mitiga a necessidade de repetir códigos iguais para a declaração desses métodos e atributos (código modular)

j) A ideia da superclasse Animal é incluir todos os atributos compartilhados por todos os animais, portanto o método dormir() deve ser adicionado na superclasse Animais

6.
k) Nome: Tico, Espécie: Macaco, Idade: 4
Nome: Nala, Espécie: Leoa, Idade: 5
Habitat natural: Savana Africana

l) Os atributos (nome, espécie e idade) não seriam utilizáveis para a subclasse AnimalSelvagem, logo não seria possível a utilização do método exibirInformações para o objeto2 

7.
m e n)
``` javascript
class AnimalDomestico extends Animal {
constructor(nome, espécie, idade, nomeDono) {
	super(nome, especie, idade);
	this.nomeDono = nomeDono;
	}

	exibirDono() {
	return `Dono de ${this.nome}: ${this.nomeDono}
	}
}
```
