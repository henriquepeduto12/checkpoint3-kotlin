Henrique Oliveira Peduto RM: 93658

# Aplicativo Android - Lista de Compras

Este é um projeto de aplicativo Android desenvolvido como prática de programação mobile. O objetivo principal é permitir ao usuário cadastrar, visualizar e remover itens de uma lista de compras, utilizando persistência local e arquitetura moderna.

## Objetivo do Projeto

Este projeto foi desenvolvido com a finalidade de aplicar os conhecimentos obtidos em aula sobre desenvolvimento de aplicativos Android, incluindo a utilização da linguagem Kotlin, persistência com Room (SQLite), RecyclerView para listagem dinâmica, e a arquitetura MVVM (Model-View-ViewModel) para organização do código.

## Funcionalidades

- Inserção de novos itens na lista de compras
- Visualização em tempo real dos itens cadastrados
- Remoção de itens da lista
- Armazenamento local dos dados com Room
- Interface responsiva utilizando componentes padrão do Android

## Tecnologias Utilizadas

- Android Studio
- Kotlin
- Android SDK
- RecyclerView
- ViewModel e LiveData
- Room (abstração do SQLite)
- Gradle

## Estrutura do Projeto

O projeto está organizado de acordo com o padrão MVVM:

- `model/` – Classes que representam os dados da aplicação, como o Item.kt
- `dao/` – Interfaces de acesso ao banco de dados local com Room
- `repository/` – Responsável por gerenciar as operações entre ViewModel e DAO
- `viewmodel/` – Lógica que conecta os dados com a interface
- `view/` – Activities e layouts da interface do usuário

## Considerações Finais

Este projeto serviu como exercício para reforçar os conceitos fundamentais do desenvolvimento de aplicativos Android, com foco na separação de camadas, reatividade da interface e persistência de dados. Além disso, foi uma oportunidade para entender como componentes modernos do Android se integram em um aplicativo funcional.


