# Prova do terceiro trimestre para os primeiros anos:
Os alunos ao longo do trimestre trabalharam no projeto da Biblioteca Virtual. Neste ponto do projeto é esperado que todas as funções de communicação com o servidor estejam concluídas.

Para os alunos que não completaram o projeto, será disponibilizada uma base onde poderão trabalhar em cima, mas neste caso a nota máxima para o aluno será seis (6), enquanto que para os alunos que usaram o próprio projeto, estes podem chegar a nota dez (10).

A prova consistirá em atividades de desenvolvimento de funcionalidades para a aplicação, sendo uma (1) delas obrigatória, valendo metade da nota, e mais duas atividades a escolha do aluno dentre quatro opções. Seguem as regras abaixo quanto as atividades:

1. Uma atividade ***obrigatória*** valendo cinco (5) pontos. Esta atividade tem duas partes "bônus", que são chance para ponto extra: meio (0,5) ponto cada.
2. Quatro (4) atividades, das quais o aluno poderá escolher duas (2) para realizar
3. Cada uma das atividades opcionais vale dois e meio (2,5) pontos.
4. A nota máxima do aluno para as atividades opcionais é de cinco (5) pontos, ***independente*** de quantas o aluno fizer. Ex: Se o aluno fizer três (3) questões opcionais, a nota máxima possível para estas questões é de cinco (5) pontos.

## Lista de atividades
### Obrigatória (5 pontos) (3 pontos para quem usar projeto disponibilizado pelo professor)

Antes que se assustem com o exercício, cada uma das instruções abaixo é uma única linha de código. Sejam sábios ao implementar estas funções, parece muita coisa, mas a maior parte do conteúdo delas é idêntica entre cada uma: vocês podem copiar e colar bastante coisa entre elas, bastando alterar poucas coisas em cada instrução.

- Implementar no HTML dois elementos:
    1. Um elemento `<h3>` com o ID "carregamento", o atributo style="display: none;", e o texto "Carregando itens da biblioteca..."
    2. Um elemento `<h3>` com o ID "erro" e o atributo style="display: none;"

- Implementar as quatro funções abaixo (todas pequenas):
    1. mostrarErro(mensagem), que faz o seguinte: 
        - Seleciona o `<h3>` com ID "erro" (usando document.getElementById e armazenando em uma variável "elemento")
        - Coloca dentro deste elemento o texto recebido no argumento "mensagem" acessando a propriedade "textContent" dele (elemento.textContent). 
        - Seleciona o atributo "style" do elemento e altera a propriedade "display" para "block" (usando elemento.style.display)
    2. esconderErro(), que faz o seguinte: 
        - Seleciona o `<h3>` com ID "erro" (usando document.getElementById e armazenando em uma variável "elemento")
        - Seleciona o atributo "style" do elemento e altera a propriedade "display" para "none" (usando elemento.style.display)
    3. mostrarCarregamento(), que faz o seguinte: 
        - Seleciona o `<h3>` com ID "carregamento" (usando document.getElementById e armazenando em uma variável "elemento")
        - Seleciona o atributo "style" do elemento e altera a propriedade "display" para "block" (usando elemento.style.display)
        - (bônus) Seleciona o atributo "style" da biblioteca (já armazenada na variável "biblioteca"), e muda a propriedade "display" dela para "none" (selecione com biblioteca.style.display)
    4. esconderCarregamento(), que faz o seguinte: 
        - Seleciona o `<h3>` com ID "carregamento" (usando document.getElementById e armazenando em uma variável "elemento")
        - Seleciona o atributo "style" do elemento e altera a propriedade "display" para "none" (usando elemento.style.display)
        - (bônus) Seleciona o atributo "style" da biblioteca (já armazenada na variável "biblioteca"), e muda a propriedade "display" dela para "none" (selecione com biblioteca.style.display)

### Livre-escolha (2,5 pontos cada) (1,5 pontos para quem usar projeto disponibilizado pelo professor)

1. (Foco em JavaScript) Implementar um elemento acima da lista de itens da biblioteca (pode ser um `<p>`, `<h1>`, `<span>`, etc) que mostre quantos itens a biblioteca têm no total. (Dica: deve fazer a conta de quantos objetos foram recebidos pelo servidor na função "carregarItens". Podemos usar a variável "bibliotecaItens" para armazenar os itens desta lista e contabilizar)

2. (Foco em CSS) Posicionar o formulário à direita OU esquerda da lista de itens da biblioteca, e deixar a lista de itens da biblioteca orientada na vertical.

3. (Foco em JavaScript) Implementar uma função associada a um botão que, ao ser clicado, insere valores de exemplo nos campos de input do formulário.

4. (Foco em HTML e CSS) Adicionar um rodapé na página contendo informações de que o projeto foi feito por você, e o texto do seu nome deve ser um link (uma tag "âncora", ou `<a>`) para o seu email.

# Instruções de envio

1. Se tiver uma pasta chamada node_modules no projeto, apague.
2. Compacte a pasta contendo seu código
3. Envie o arquivo compactado no classroom na atividade da N2

# Boa sorte
