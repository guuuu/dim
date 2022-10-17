#### 17/10/2022

Utilizadores secundários é por exemplo a secretaria do ISMAI quando recebe uma senha que um aluno tirou anteriormente, ou seja, um utilizador que não use diretamente a “app” mas que faça uso dela, sem contacto direto.

Utilizadores terciários são aqueles que têm um pequeno impacto.

Necessidades explicitas é por exemplo “Deslocar a entrada do ISMAI para tirar senha para a secretaria”. Estas necessidades podem aparecer em:

- Entrevistas
- Caderno de encargos (cliente)
- Análise de criticas

Necessidades implícitas (deduzidas) é quando um utilizador diz “eu quero isto”, por exemplo o utilizador secundário definir / pedir que é necessário uma app para tirar senhas especificas no ISMAI. Estas necessidades podem aparecer em:

- Observação / *analytics* / *tracking*

Os requisitos do sistema:

- Funcionais (*features*) (detalhar ao máximo)
    - App local (sem registo / sem *[oAuth](https://oauth.net/2/)*)
    - App com *sync* (registo de users / precisa de uma BD)
- Não funcionais (não afetam o sistema do utilizador / o utilizador não faz uso destes requisitos)
    - Traking
    - Publicidade
    - MariaDB / PostgreSQL / Firebird
    - *Cybersecurity*
    - GDPR

### Teoria da carga cognitiva

- O conhecimento é obtido por camadas
    - Por exemplo, quando aprendemos a ler, aprendemos primeiro por reconhecer as letras depois por aprender palavras pequenas, pequenas frases, etc…
- É difícil estar a ler algo e a ouvir alguém torna-se complicado prestar atenção aos dois uma vez que há um conflito entre as cargas.
- Quanto menos carga cognitiva gastarmos com coisas supérfluas melhor vai ser a nossa capacidade de processamento.

### Princípios da coerência

- Material em excesso pode prejudicar a aprendizagem
- Audio, imagens, texto em excesso devem ser omitidos ou opcionais

### Princípios da personalização

- Encontra-se por exemplo nos tutoriais dos jogos
- Texto e narração em estilo conversacional

### Princípios da segmentação

- Divisão em segmentos mais pequenos

### Princípios a aplicar

- Tirar partido do **multimédia**
- Preservar a **Contiguidade**
- Evitar **redundâncias**
- Manter a **Coerência**
- **Personalização**
- **Segmentação** e **treino prévio**

### Necessidades dos utilizadores (clientes)

- Explicitas
    - O que é que nos disseram necessitam
- Implícitas
    - O que é que achamos que precisam (com base em análise)

### Requisitos do sistema

- Funcionais
    - Que funções satisfazem as necessidades?
- Não funcionais (nao alteram a funcionalidade mas são necessários)
    - O que implica a implementação das funções (tecnicamente / legalmente)
    - Limitações técnicas à implementação

### Compreender o problema

- Quem são os users
- Onde quando porquê e como é que atualmente a tarefa é feita.
- Quais os problemas que os users percepcionam
- Wish list dos users para melhorar a forma de como completam a tarefa

UX é um processo sistemático.

É um erro começar o design sem compreender o user, a tarefa, e como a mesma é executada

### Técnicas de recolha de dados

- Dados qualitativos (narrativas / temas emergentes)
    - Observação naturalista
    - Grupos focais
    - Entrevistas
- Dados quantitativos (numéricos)
    - Inquéritos
    - User *analytics*

### Técnicas de representação

- Cenários
- Casos de utilização
- Análise hierárquica
- Crítica de UI/UX actuais.

### Categorias de utilizadores

- Utilizadores primários (end-useres)
    - Interagem diretamente com o produto
- Utilizadores secundários
    - Obtêm alguns outputs do produto
- Utilizadores terciários
    - Não o usam mas são afetados pelo seu design
        - Por exemplo o gestor de produto de uma empresa que fabrica o seu próprio produto


# Desafio

>
> Escolham um outro produto ou app e escrevam sobre os seus potenciais utilizadores primários, secundários e terciários.
> 

## uBlock Origin

1. Utilizadores primários
    1. Todos os users que façam a instalação da extensão no seu navegador
2. Utilizadores secundários
    1. Outras extensões que trabalhem junto do uBlock Origin uma vez que o mesmo é ***********[open source](https://github.com/gorhill/uBlock)***********
3. Utilizadores terciários
    1. Todos os sites onde o utilizador **********não********** desligue o adBlock são afetados uma vez que todo e qualquer tipo de anúncio é removido

#### 10/10/2022

Quando surgiram as redes sociais, o twitter foi uma das primeiras a ter uma API o que cativava os seus utilizadores a criarem as suas próprias apps para interagir com o twitter.

Em 1981 os computadores vendidos pela IBM eram caros, devido a junto do computador ser vendido um serviço de assistência e de montagem, ou seja o user não precisava de se preocupar com a montagem do computador.

## Skeuomorphism

Skeuomorphism é um princípio de design em que os objetos derivados retêm ornamentos e estruturas que eram necessárias apenas nos objetos originais.

Com a nova onda flat, podem existir algumas dificuldades em por exemplo, num smartphone perceber que um bocado de texto é um botão, enquanto que num modelo de skeuomorphism não haveria nunca essa dúvida.

Ted Nelson foi a pessoa que explodiu com a hypermedia (links em texto, imagens, etc)

<aside>
💡 Artigo referido em aula —> [Projeto xanadu](https://en.wikipedia.org/wiki/Project_Xanadu)

</aside>

### Arpanet

**A** dvenced

**R** esearch

**P** rojects

**A** gency

**Net** work

![arpanet.png](https://github.com/guuuu/dim/blob/main/images/101022/arpanet.png)

Para passar da utilidade à usabilidade foi criado em 1983 o DNS por Paul Mockapetris.

### Os três princípios de cognição

1. Dois canais de processamento
    1. Visual + auditivo
    2. Verbal
2. Capacidade limitada
    1. Processamento simultâneo de pouca informação em cada canal
3. Processamento ativo
    1. Aprendizagem ocorre se o material é organizado numa estrutura coerente ou integrado com o conhecimento prévio.

### Os três processos cognitivos

1. Atenção e seleção
2. Organização
3. Integração com o conhecimento pré-existente
    1. Por exemplo, um icon representado com um papel e um lápis, leva a perceber que seja para editar / criar novo texto, este conhecimento vem de aplicações prévias, ou em último caso, vem da intuição do user perceber que se o icon é uma folha de papel e um lápis deve ser para escrever.

![Mayer.jpg](https://github.com/guuuu/dim/blob/main/images/101022/Mayer.jpg)

### As três cargas cognitivas

1. Processamento supérfluo (minimizar)
2. Processamento essencial
3. Processamento generativo (organização e integração)

Quantos mais pontos/sockets/ganchos etc… houver no nosso cérebro menor é o processamento generativo.

#### 03/10/2022

A partir dos anos 40 surgiram as primeiras máquinas que podem ser reconhecidas como computadores eletrônicos.

[Alan Turing](https://pt.wikipedia.org/wiki/Alan_Turing) liderou um projeto de criar uma máquina para quebrar códigos de mensagens durante a segunda guerra mundial.


💡 Filme referido em aula —> [Hidden Figures](https://en.wikipedia.org/wiki/Hidden_Figures)

O primeiro computador americano tem o nome de [ENIAC](https://pt.wikipedia.org/wiki/ENIAC) e apareceu em 1946.

![ENIAC.gif](https://github.com/guuuu/dim/blob/main/images/031022/ENIAC.gif)

Sempre que era necessário alterar o tipo de operações a serem feitas, o CPU tinha de ser recriado / reorganizado.

Em 1950 aparecem os primeiros computadores comerciais.

As primeiras formas de se inserirem instruções nos computadores era com cartões perfurados e surgiram por volta dos anos 60.

💡 Vídeo referido em aula —> [Sketchpad](https://www.youtube.com/watch?v=6orsmFndx_o)

💡 Vídeo referido em aula —> [The mother of all demos](https://www.youtube.com/watch?v=yJDv-zdhzMY)

O primeiro interface gráfico surgiu em 1973.

O primeiro computador caseiro foi o [Altair 8800](https://pt.wikipedia.org/wiki/Altair_8800).

![altair.jpg](https://github.com/guuuu/dim/blob/main/images/031022/altair.jpg)

💡 Emulador referido em aula —> [Spectrum](http://torinak.com/qaop)


#### 26/09/2022

# Conceitos

---

- Software educativo
    - Software com uma interface simples e intuitiva de maneira a que os seus utilizadores possam dedicar toda a sua atenção à autoaprendizagem / ensino e tenham gosto em usar o mesmo.
    - Um ponto importante que se deve ter em questão é qual o público alvo para o qual o software vai ser apontado, se for um público mais sênior, é necessário ter os devidos cuidados como por exemplo o tamanho da fonte.
- *Early adopters*
    - Pessoas que adotam um produto acabado de entrar no mercado.
    - Traz vantagens para o produto, uma vez que se o *early adopter* partilhar a app nova que utiliza com duas pessoas se estas a começarem a utilizar e se este mesmo ciclo se repetir mais N vezes rapidamente a app será conhecida por várias pessoas, este caso especifico pode ser comparado a uma [*Binary tree*](https://en.wikipedia.org/wiki/Binary_tree).



    ---

    ![Diagram1.png](https://github.com/guuuu/dim/blob/main/images/260922/Diagram1.png)


---

# Design

- Objetivo
    - Melhorar a UX (experiência do utilizador) na execução da tarefa
    - Útil
        - Funciona como previsto
    - Usável
        - Eficaz
            - Boa performance
        - Eficiente
            - EOU (ease of use)
                - Ex.: Os utilizadores associam um triangulo “deitado” como sendo o icon de play, e uma lupa como o icon de pesquisa.
        - Satisfatória
            - Uma atitude positiva
            - Não causa ansiedade

---

# Qualidades de um bom design

Livro referido em aula 👉 [The Design of Everyday Things: Revised and Expanded Edition](https://www.amazon.com/Design-Everyday-Things-Revised-Expanded/dp/0465050654)

### Conceitos

- *Affordances*
    - Propriedades factuais e percepcionadas dos objetos
    - Ex.: Uma porta com uma label a dizer empurre, no entanto tem um puxador. Resta a dúvida de se o utilizador se guia pela indicação ou pela intuição…
- *Signifiers*
    - Onde as ações ocorrem
    - Ex.: Um teclado tem quase todas as teclas iguais, no entanto o que as distingue é a forma como estão etiquetadas
- *Feedback*
    - Devolver algum tipo de informação sobre o input dado
    - Ex.: Vibrar o telemóvel ao clicar numa tecla, reproduzir um som ao clicar num botão, alterar a cor de um elemento após um input do user para o mesmo saber que foi válido.

---

# Design de interfaces

O design de interfaces é dividido em 4 etapas:

- Identificar requisitos / necessidades
- Design / Planeamento de alternativas
- Prototipagem / desenvolvimento
- Avaliação

---

# Desafio
> Affordances | Signifiers | Feedback
> Escolham um elemento de um interface que usem frequentemente e discutam como manifesta estas qualidades.

### DuoLingo

- *Affordances*
    - Facilmente o utilizador consegue perceber onde pode aprender sobre a língua escolhida, aprender os caracteres caso se aplique, ver as histórias, onde comprar coisas, etc…

        ![Untitled](https://github.com/guuuu/dim/blob/main/images/260922/Untitled.png)

- *Signifiers*
    - No caso dos caracteres, o utilizador consegue perceber quais caracteres já treinou o suficiente, quais é q falta treinar e todos eles são iguais, no entanto o que os distingue é a label que lhes é posta.

        ![Untitled](https://github.com/guuuu/dim/blob/main/images/260922/Untitled%201.png)

- *Feedback*
    - Usando outra vez os caracteres como exemplo, quando o utilizador clica num dos caracteres, além de ser reproduzido o respetivo som, existe uma alteração visual que transmite a sensação de clique ao utilizador.

        ![Botão não clicado](https://github.com/guuuu/dim/blob/main/images/260922/Untitled%202.png)

        Botão não clicado

        ![Botão Clicado](https://github.com/guuuu/dim/blob/main/images/260922/Untitled%203.png)

        Botão Clicado