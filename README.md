# 🧹 Jogo da Cobrinha - Tema Gari

Um clone do clássico **Jogo da Cobrinha (Snake)** desenvolvido em **Java** com a biblioteca gráfica **Java Swing**. Nesta versão temática, a cobrinha é substituída por um **gari** e as frutas por **lixeiras** que ele precisa coletar pelo mapa.

Projeto desenvolvido como Atividade Prática Supervisionada (APS) do 3º semestre do curso de **Bacharelado**, com foco na aplicação de **herança** e conceitos de Programação Orientada a Objetos.

## 📑 Sumário

- [Sobre o projeto](#-sobre-o-projeto)
- [Funcionalidades](#-funcionalidades)
- [Conceitos de POO aplicados](#-conceitos-de-poo-aplicados)
- [Tecnologias utilizadas](#-tecnologias-utilizadas)
- [Pré-requisitos](#-pré-requisitos)
- [Como executar](#-como-executar)
- [Como jogar](#-como-jogar)
- [Estrutura do projeto](#-estrutura-do-projeto)
- [Contribuindo](#-contribuindo)
- [Autor](#-autor)

## 📖 Sobre o projeto

O objetivo do jogo é controlar o gari pelo mapa, coletando lixeiras para aumentar sua pontuação e seu tamanho, evitando colidir com as bordas da tela ou com o próprio corpo. O projeto reaproveita a mecânica clássica do Snake, adaptando a temática visual e reforçando conceitos de herança entre classes do jogo.

## ✨ Funcionalidades

- Controle do gari através das teclas de direção (setas do teclado).
- Coleta de lixeiras que aparecem em posições aleatórias na tela.
- Crescimento do gari a cada lixeira coletada.
- Detecção de colisão com as bordas do mapa e com o próprio corpo, encerrando o jogo.
- Interface gráfica construída inteiramente com Java Swing.

## 🧠 Conceitos de POO aplicados

- **Herança**: estruturação das classes do jogo (personagem, elementos do mapa, etc.) a partir de superclasses comuns.
- **Encapsulamento**: atributos e comportamentos do gari e das lixeiras organizados em classes próprias.
- **Polimorfismo**: reaproveitamento de comportamento entre entidades do jogo, quando aplicável.

## 🛠 Tecnologias utilizadas

- [Java](https://www.java.com/)
- [Java Swing](https://docs.oracle.com/javase/tutorial/uiswing/) (interface gráfica)

## ✅ Pré-requisitos

Antes de começar, você precisa ter instalado:

- [JDK (Java Development Kit)](https://www.oracle.com/java/technologies/downloads/) 8 ou superior
- Uma IDE de sua preferência (recomendado: [IntelliJ IDEA](https://www.jetbrains.com/idea/), [Eclipse](https://www.eclipse.org/) ou [NetBeans](https://netbeans.apache.org/)) **ou** apenas o `javac`/`java` via linha de comando

## 🚀 Como executar

### Via IDE (recomendado)

1. Clone o repositório:
   ```bash
   git clone https://github.com/eduardocastro-dev/Bacharelado_APS_3SEM.git
   ```
2. Abra a pasta `JavaProjeto` na sua IDE de preferência.
3. Localize a classe principal do jogo (a que contém o método `main`).
4. Execute o projeto pela própria IDE.

### Via linha de comando

1. Clone o repositório:
   ```bash
   git clone https://github.com/eduardocastro-dev/Bacharelado_APS_3SEM.git
   cd Bacharelado_APS_3SEM/JavaProjeto
   ```
2. Compile os arquivos-fonte:
   ```bash
   javac *.java
   ```
3. Execute a classe principal (substitua `NomeDaClassePrincipal` pelo nome real da classe que contém o `main`):
   ```bash
   java NomeDaClassePrincipal
   ```

> 💡 **Nota:** ajuste os comandos acima de acordo com os nomes reais dos pacotes e da classe principal presentes na pasta `JavaProjeto`.

## 🎮 Como jogar

| Tecla | Ação |
| ----- | ---- |
| ↑ | Move o gari para cima |
| ↓ | Move o gari para baixo |
| ← | Move o gari para a esquerda |
| → | Move o gari para a direita |

O objetivo é coletar o máximo de lixeiras possível sem colidir com as bordas do mapa ou com o próprio corpo do gari.

## 📁 Estrutura do projeto

```
Bacharelado_APS_3SEM/
├── JavaProjeto/     # Código-fonte do jogo em Java
└── README.md
```

## 🤝 Contribuindo

Contribuições são bem-vindas! Sinta-se à vontade para:

1. Fazer um fork do projeto
2. Criar uma branch para sua feature (`git checkout -b feature/minha-feature`)
3. Commitar suas alterações (`git commit -m 'Adiciona minha feature'`)
4. Enviar um pull request

Sugestões e relatos de problemas também podem ser abertos na aba [Issues](https://github.com/eduardocastro-dev/Bacharelado_APS_3SEM/issues).

## 👤 Autor

Desenvolvido por [**Eduardo Castro**](https://github.com/eduardocastro-dev) como parte das atividades do curso de Bacharelado.
