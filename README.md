### 21/11/2022


# Simplificação de interfaces

- Nas interfaces de audio ainda está muito presente o skeuomorphism
- O audition é uma aplicação focada na parte de trabalhar o audio e o design está mais simplificado com multiplas pistas de audio

### Técnicas de simplificação

- Redução
    - Retirar / esconder elementos não essenciais.
- Antigamente não se utilizavam os icons da navbar inferior nos telemóveis android pois já existiam os 3 botões default do android, hoje em dia, esses botões foram trocados por gestos, abrindo assim a possibilidade de utilizar uma navbar inferior nos dispositivos móveis.

# Tipologias de protótipos

- Abrangência
    - Protótipo vertical
        - Modelo detalhado de parte das funcionalidades
        - Permite estudar o fluxo de poucas tarefas centrais
- Protótipos de baixa fidelidade
    - Desenvolvidos em primeiro lugar de modo a estudarmos o design do interface e verificar com colegas e com stakeholders.
    - Pode ser feito em:
        - papel
        - storyboards
        - cartões
        - Wireframes
- Protótipos de alta fidelidade
    - Podem ser utilizados alguns softwares como
        - Powerpoint
        - Illustrator
        - Dreamweaver
- Existem duas técnicas de prototipagem mais “exóticas”
    - Wizard of oz & Turco mecânico
    - Vantagem
        - Poupança ao evitar o desenvolvimento de um sistema funcional
    - Desvantagens
        - Tempo de ensaio do operador escondido
        - Ilude os utilizadores que testam o protótipo com impacto na validade do feedback




### 14/11/2022

# Padrões de design

### Padrões de navegação

- Breadcrumbs
    - Tem um aspeto mais gráfico ou como por exemplo no explorador do windows
- Paginação
- Widgets
    - Dropdown
    - Combobox
    - Menus
        - Podem ser usados como hierarquias
    - Escolhas
        - Radio buttons
        - Single Selection listbox
        - Toggle buttons
        - Evitar usar checkboxes para uma opção que pode signigicar duas coisas
            - Ex.:
                - [ ]  Insert vs overstrike
    - Organização
        - Tabs
        - Table of contents
        - Acordeão
        - Scroll
            - A forma de se perceber que há mais conteudo para se poder dar scroll em mobile, é o facto de aparecer conteudo cortado.

# Método atómico

Um exemplo de uma app que segue um modelo atómico é por exemplo o instagram.

- Átomos (foto de perfil)
    - Widgets / elementos (HTML)
- Moléculas (feed / area de comentários)
    - Componentes
        - Pesquisa = campo + botão + placeholder
- Organismos
    - Componentes complexos
        - Grelha de cartões / cabeçalho
- Templates
    - Modelos reutilizáveis de páginas
- Páginas
    - Instâncias especificas de templates

### 07/11/2022

# Discussão sobre as [propostas de enunciado](https://moodle.maieutica.pt/mod/assign/view.php?id=55277)

No meu caso, foi feita uma chamada de atenção, que o requisito não funcional de sistema
>"Os utilizadores necessitam de ter as propinas em dia (se não o login fica indisponível)"

deveria na verdade ser um requisito **funcional** uma vez que gera um erro/mensagem de aviso para que o utilizado saiba que perdeu o acesso à plataforma.

## Proposta submetida


#### Titulo

UDMchat —>Universidade da maia chat

#### Resumo

Chat app para alunos da universidade da maia, com um chat que engloba todos os
alunos, chats criados automaticamente por turmas, e possibilidade de mensagens
privadas. Os alunos podem tirar proveito para pedir ajuda / pedir material e os
professores / instituição usam a app para publicar alertas a situações adversas.

#### Utilizadores destino

Esta app será para utilizadores entre os 18 e os 24 anos, com no mínimo o 12º ano ou
equivalente e que não exige grandes conhecimentos tecnológicos por parte dos
utilizadores de qualquer faixa etária.

Os utilizadores primários são todos os alunos da universidade da maia que transfiram
a aplicação e façam uso dela.

Os utilizadores secundários são os docentes, que mesmo não estando envolvidos
diretamente na app, beneficiam de uma maior agilidade entre alunos e de poderem
pedir à instituição que “lance” um aviso no grupo da turma X para os informar de
alguma situação inesperada.

Os utilizadores terciários será a instituição propriamente dita visto ter a
hipótese/funcionalidade de lançar avisos em todos os chats de grupo (falta de um
docente, falta de condições na universidade (inundações, etc..))

#### Como é executada atualmente a tarefa

Atualmente a solução mais comum é os alunos criarem grupos de WhatsApp /
Messenger para as turmas, a única área existente onde todos os alunos podem falar é
a área de debate geral na área privada. Um dos problemas com estas aplicações é
que geralmente faltam colegas no grupo da turma / colegas que gostariam de estar
presentes, mas não sabem da existência do grupo.

#### Necessidades explicitas

- Os utilizadores precisam de estar inscritos na Universidade da maia
- Enviar mensagens
- Fazer videochamadas
- A instituição publicar avisos em todos os grupos existentes para alertar de
situações adversas

#### Necessidades implícitas

- Mensagem visualizada
- Notificação de mensagem recebida
- Poder enviar ficheiros

#### Requisitos funcionais do sistema

- App com login (uso do login *******default******* da universidade da maia)
- Notificações em *background* (para que o aluno receba notificações mesmo sem a app aberta)
- Animação para mostrar que um aluno está a escrever

#### Requisitos não funcionais do sistema

- A aplicação deverá cumprir rigorosamente todas as regras do RGPD
- Base de dados para registar as mensagens
- Acesso à API/dados internos da universidade da maia (para a criação dos grupos e validações)
- Os utilizadores necessitam de ter as propinas em dia (se não o login fica indisponível)
- As mensagens serão encriptadas
- Tecnologias como (multiplataforma)
    - React native
    - Tailwindcss
    - Typescript
    - PostgresSQL

### 31/10/2022

# O que é uma obra

- Por exemplo um perfil digital
    - Tem 1 autor (ou mais)
        - Frequenta um contexto
        - Produziu obras
        - Possui uma ficha biográfica, link, etc
    - Foi produzida num contexto (grupo)
        - Existe numa hierarquia (Universidade / escola / curso )
        - Contém autores
        - Contém obras
        - Tem uma ficha própria com links
    - Tem metadados
    - Tem diferentes media (texto / imagem / vídeo / áudio / etc…)
    

# Design de interface úteis

- Quais são as necessidades explícitas dos utilizadores
    - Declaradas em entrevistas / questionários


💡 Site referido em aula —> [BeHance](https://www.behance.net/)


Parte da aula foi em volta do perfil digital do docente e sobre os seus projetos —> [http://www.eduardomorais.com/](http://www.eduardomorais.com/)

Foram ainda discutidas dúvidas sobre a primeira entrega ["Enunciado e submissão da proposta ⬆️"](https://moodle.maieutica.pt/mod/assign/view.php?id=55277)


### 24/10/2022

# Recolha de dados

## Considerações éticas

- Preservação do anonimato
- Respeito pelas normas legais (ex. GDPR) —> Qualquer informação que identifique o utilizador necessita de autorização explícita.
- No caso de haver filmagens, a entidade que faz o estudo tem de dar a assinar uma declaração que informa que as imagens serão tratadas de forma anônima e será mantido o anonimato no resultado final.

## Observação naturalista

- Observação do utilizador enquanto cumpre a tarefa ***************Fly on the wall***************.
- Ter um observador “físico” traz vantagens porque consegue trazer dados importantes que por vezes digitalmente (analytics e logs) não é possível

## Questionários

- Self-report (experiência subjetiva do utilizador)
    - Comportamento Percepções
    - Atitudes
    - Sensações
- Items fechados
    - Dictomais (sim/nao)
    - Escalas de likert
        - Regra geral usa-se com opções impar para que o utilizador possa ter uma opinião neutra no entanto existem discussões sobre utilizar opções par para que o utilizador seja obrigado a ter uma opinião.
    - Listas ordenadas
- Items abertos
    - Opinião escrita
- Desvantagens
    - Conhecimento superficial
    - Enviesamento dos participantes (agradar ao investigador)
    - Enviesamento da amostragem
- Plataforma para os próximos passos da investigação
    - Resultados irão ditar as questões para os grupos focais ou entrevistas.

## Grupos focais

Conversa direcionada com grupos pequenos (5 a 10 pessoas) com no mínimo 2 investigadores o moderador e anotador e no máximo 60 minutos de duração e 3 tópicos de discussão. Esta conversa dá se sempre em um ambiente controlado.

- Quando há uma afirmação o anotador questiona toda a gente se mais alguém concorda, de forma a que depois se alguém concordar com o exato oposto, possa ser questionado e esclarecido o porquê.

Análise qualitativa de transcrições e anotações junto com a recolha de dados quantitativos sem participantes.

Os grupos focais têm desvantagens porque é necessário uma equipa de investigação e um moderador experiente, o groupthink é quando alguns participantes começam a reproduzir/copiar as opiniões dos outros.

## Entrevista

- Entrevista estruturada
    - As questões seguem um guião
- Entrevista aberta
    - Conversa livre sem perder a essência do tópico
- Entrevista semi-estruturada
    - Segue um guião mas permite que o entrevistado divague um pouco
    - Possibilidade de colocar questões que não estejam no guião
- Desvantagens
    - Necessidade de um entrevistador experiente
    - Processo muito exaustivo porque necessita de muito tempo e dinheiro.


💡 Video referido em aula —> [https://www.coursera.org/lecture/user-experience-design/user-results-aTZoM](https://www.coursera.org/lecture/user-experience-design/user-results-aTZoM)



💡 Video referido em aula —> [https://www.coursera.org/lecture/user-experience-design/presenting-task-findings-WB2gk](https://www.coursera.org/lecture/user-experience-design/presenting-task-findings-WB2gk)


## Novo design

### Individual

A atualização do design de uma aplicação pode melhorar a experiência do utilizador ficando adequado às características dele.

- Idade
- Educação
- Atitude / conforto perante a tecnologia
- Características físicas

### Sociedade

Atenção aos efeitos de um design novo nas dinâmicas sociais, necessidades de ompreender valores culturais relacionados com a tarefa.

# Desafio

> Escolham um outro produto ou app e escrevam sobre o que é que mudou após um upgrade.
> 

## Duolingo

As primeiras versões do duolingo tinham um design tipico da altura (2012), tendo sofrido um grande redesign com uma data da qual eu não tenho a certeza.

No entanto a versão atual do duolingo o *homescreen* dá asas ao utilizador para escolher aquilo que pretende fazer relativamente ao tópico que o user quer aprender, mas isso vai acabar, uma vez que está a ser planeado um redesign novo que vai tornar mais fácil ao user decorar e criar bases para a lingua que esteja a aprender.

Todas as imagens e todos os tópicos abordados neste desafio foram obtidos a partir do blog oficial do duolingo, e deste [post](https://blog.duolingo.com/new-duolingo-home-screen-design/) em especifico.

![Home scree antigo —> Home screen novo](https://github.com/guuuu/dim/blob/main/images/241022/oldHome_vs_newHome.png)

![oldCrowns_vs_newCrowns.png](https://github.com/guuuu/dim/blob/main/images/241022/oldCrowns_vs_newCrowns.png)

Estas novas alterações ao design do duolingo têm base em estudos científicos sobre a aprendizagem (tópico falado em sala de aula no ponto de recolha de dados), e vai seguir padrões repetitivos espaçados para que o utilizador não se aperceba de que está a repetir o mesmo tópico de aprendizagem e tornar assim mais suave a adaptação a uma nova língua.

A meu ver este redesign será para o melhor, mas como de momento ainda não foi feito referido redesign (no meu caso ainda não houve uma atualização, pode já estar a ser distribuída para outros dispositivos móveis) só tendo a experiência propriamente dita é que poderia ter um voto sólido sobre este tópico, uma vez que, com qualquer aplicação, quando se utiliza algo que é igual durante muito tempo, por vezes pode ser díficil adaptarmo-nos às novas funcionalidades e aspetos.


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