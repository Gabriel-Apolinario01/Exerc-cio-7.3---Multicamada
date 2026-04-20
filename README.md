# Exercício 7.4 - Arquitetura Clean

# Livraria Clean Architecture

Projeto desenvolvido em Python com Flask.

Arquitetura:

* Entities (entidades do sistema)
* Use Cases (regras de negócio)
* Interface (controllers)
* Infra (persistência em arquivo TXT)
* View (Flask)

Princípios aplicados:

* Dependency Inversion Principle (DIP)
* Baixo acoplamento entre camadas
* Independência de tecnologia

Persistência de dados:

* Os dados são salvos em um arquivo TXT
* Cada linha representa um registro no formato:
  Nome,Preço

Nova funcionalidade:

* Histórico de compras persistente em arquivo TXT

Como executar:

cd Livraria
python -m view.app
