# Encapsulamento

Encapsulamento
	- Capacidade de um objeto restringir o acesso a determinadas propriedades.
	- A visibilidade de uma propriedade interfere na herança? Sim.
	- Implementado por meio dos modificadores de visibilidade:
 
		- private: a propriedade pode ser acessada somente por objetos da mesma classe.
		- public: a propriedade pode ser acessada por objetos de quaisquer classes do mesmo projeto.
		- "package": a propriedade pode ser acessada por objetos de quaisquer classes do mesmo pacote.
		- protected: a propriedade pode ser acessada por: 
  
1) objetos de quaisquer classes do mesmo pacote ou;
2) superclasses desde que a propriedade tenha sido declarada na própria superclasse.




Criamos as classes A, D e E no package Control

Criamos as classes B e F no package Model

Criamos a classe C no package View
