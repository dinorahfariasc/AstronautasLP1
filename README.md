# Astronautas LP1
Atividade 1: Astronautas. da matéria Linguagem de Programação 1

# Objetivo
Implementar um sistema de gestão de astronautas e voos espaciais, em c++ utilizando classes, metodos e objetos. Atendendo os seguintes [requisitos](https://docs.google.com/document/d/1W9hH12mJCvyrJxH0JxaaUVHQdLYGfK461puEwYUkwtg/edit)

## Pré-Requisitos
- Compilador "g++" instalado
- Sistema operacional compatível com Makefile

## Executar o Programa
Na pasta principal do projeto abra o terminal e execute o makefile 
```
make final
```
Após a compilação, rode o programa executavél

```
./final
```

## Funcionalidades 
O sistema permite a gestão de astronautas e voos espaciais, oferecendo as seguintes funcionalidades:

### Cadastrar Astronauta
- Permite adicionar um novo astronauta ao sistema.
- Verifica se o CPF já está cadastrado, evitando duplicação.

### Cadastrar Voo:
- Permite adicionar um novo voo ao sistema.
- Verifica se o código do voo já está cadastrado, evitando duplicação.

### Adicionar Astronauta em Voo:
- Adiciona um astronauta a um voo específico.
- Verifica se o voo está planejado e se o astronauta está disponível e vivo.
- Remover Astronauta de um Voo:

### Remove um astronauta de um voo específico.
- Verifica se o voo está planejado e se o astronauta está a bordo.

### Lançar um Voo:
- Lança um voo planejado.
- Verifica se todos os astronautas estão vivos e disponíveis.
- Atualiza o estado dos astronautas e registra o voo em seu histórico.

### Explodir Voo:
- Simula a explosão de um voo.
- Marca todos os astronautas a bordo como mortos e indisponíveis.

### Pousar Voo:
- Simula o pouso de um voo lançado.
- Marca todos os astronautas a bordo como disponíveis.

### Mostrar Todos os Voos:
- Exibe a lista de todos os voos cadastrados com seus respectivos estados, e informacoes sobre os passageiros de cada um.


### Mostrar Passageiros Mortos:
- Exibe a lista de astronautas mortos e os voos que participaram.

## Estrutura do Projeto
- ```main.cpp```: Arquivo principal contendo a lógica de interação com o usuário.
- ```astronauta.h``` e ```astronauta.cpp```: Definição e implementação da classe Astronauta.
- ```voo.h``` e ```voo.cpp```: Definição e implementação da classe Voo.
- ```Makefile```: Arquivo de automação de compilação.

## Exemplo de Uso
Após executar o programa, siga as instruções do menu para utilizar as funcionalidades disponíveis. Por exemplo, para cadastrar um novo astronauta, selecione a opção 1 e siga as instruções fornecidas.

## Observações
Certifique-se de que todos os arquivos de código-fonte e o Makefile estejam na mesma pasta para a correta execução dos comandos de compilação e execução.


