# 1. Um pouco de contextualização
O Linux é um sistema operacional inspirado em outro sistema: o `Unix`, que foi criado em 1969.

Entre esse período, foram criadas outras tecnologias como o `GNU`, um projeto que visava criar um sistema operacional livre e compatível com o Unix.

Um componente essencial de um sistema operacional é o `kernel`, que é um software que gerencia os recursos do hardware e fornece uma interface para os programas. O kernel que viria a ser um dos mais populares é o Linux Kernel, criado por `Linus Torvalds` em 1991 como um hobby pessoal.

![Linus Torvalds](linus.jpg)

# 2. Interações básicas
## 2.1. Shell

Precisamos falar de uma ferramenta muito importante para o Linux: o `shell`. Este é um programa que pega os comandos que você digita para o Sistema Operacional.

Você pode entender o shell como se fosse apenas o terminal que estamos utilizando para enviar comandos. Para abrir o seu shell, você pode clicar com o botão direito em qualquer lugar de uma pasta, e clicar em "Abrir terminal"

O shell que iremos utilizar se parece com este: 

```
nome_de_usuario@nome_do_host:past_atual

Exemplo:

juliocode@meu_pc:/home/julio/ $
```

Para testarmos algum comando, digite o comando seguinte:

```
echo Ola mundo
```

Você verá que o seu terminal irá te "devolver" a frase `Ola mundo`. Este é um dos primeiros comandos que vamos ver

## 2.2. Trabalhando com pastas

Em nosso terminal, uma das coisas que vamos ver são as pastas, ou diretórios. A estrutura de pastas do Linux se assemelha com a do Windows.

As pastas do sistema formam algo como uma hierarquia

```
|--usuario1
|  |--documentos
|  |--downloads
|     |--filmes 
|--usuario2
|  |--imagens
|  |--documentos
|
``` 

Observe o exemplo acima. Ele nos mostra que temos duas pastas principais ```usuario1``` e ```usuario2 ```. Dentro da pasta usuario1, temos documentos e downloads

O caminho da pasta "filmes" seria o seguinte:

```
usuario1/downloads/filmes
```

Por que estamos aprendendo isso?

No terminal, iremos utilizar muito estes caminhos. Então é ótimo que você saiba sobre como eles funcionam.

Além disso, vale ressaltar que, no Linux, geralmente chamamos as pastas de "diretórios". Você verá que a maioria dos comandos utiliza esta palavra para se referir às pastas.

## 2.3. Comando pwd

O primeiro comando que podemos utilizar, com relação às pastas, é o comando ```pwd```. Este comando serve para mostrarmos no terminal qual o diretório (pasta) em que estamos (pwd = print working directory).

Nesse momento, creio que você já tenha feito o tutorial de introdução, no qual baixamos este repositório. Se tudo estiver correto, se você digitar o comando pwd no terminal, e apertar enter, você terá a seguinte saída:

```
/home/nome_de_usuario/Downloads/aprender-linux-main
```

Ou seja, ele irá te mostrar o caminho completo deste diretório.

## 2.4. Comando cd e ls

Agora vamos aprender dois comandos bastante importantes: o ```cd``` (change directory) e o ```ls``` (list)

O comando cd (mudar diretório)  serve para que possamos entrar em outra pasta. Já o comando ls serve para listarmos as pastas.

Faça o experimento de inserir o comando ls no seu terminal

Ele irá te retornar uma lista com todos os arquivos e diretórios da sua pasta. Para entrar em um dos diretórios, basta que você digite cd + o nome do diretório. Por exemplo:

```
cd pasta-de-exemplo
```

Neste momento, você agora entrou dentro da pasta "pasta-de-exemplo"

Se você der o comando ls, e apertar enter, você verá a seguinte saída no terminal:

```
pasta1 pasta2
```

Estas duas são pastas que eu já coloquei dentro para que possamos fazer nossos exemplos. A partir de agora, todos os nossos exemplos serão feitos baseados na pasta-de-exemplo.

Já vimos bastante coisa até agora. Esta foi uma breve introdução para que você se familiarize com o terminal, com os comandos e com as saídas. No próximo capítulo veremos um pouco mais sobre arquivos. 

**Lembrete**
Para ir para o próximo capítulo, é só sair desta pasta (voltar a página anterior do seu navegador) e clicar na pasta "02-arquivos".
