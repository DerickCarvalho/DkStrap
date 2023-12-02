# DkStrap - Classes CSS genéricas

- DESCRIÇÃO:

    Criei esse arquivo CSS contendo classes que costumo usar em meus projetos. Essas classes funcionam em qualquer projeto, pois utilizam apenas
    atributos padrões do CSS, eu apenas os organizo em classes para facilitar o uso.

- VANTAGENS:

    Vejo esse "simplérrimo framework" como uma vantagem no seguinte cenário: Programação FrontEnd de projetos básicos. Utilizar esse framework
    diminui muito a poluição do arquivo .css das páginas da aplicação, pois, por exemplo, ao precisar definir uma div como "display flex" e alinhar
    seus elementos, não é necessário designa-la uma classe, chamar essa classe no CSS e adicionar os atributos, basta apenas usar a classe padrão
    desse framework, chamada "flex-row-center", que funciona em qualquer div.

    Basicamente, esse framework usa o conceito de reaproveitamento máximo de código, evitando escrever novamente a mesma coisa.

- DOCUMENTAÇÃO:

    - ALINHAMENTOS E ORGANIZAÇÃO:

        - DISPLAY FLEX EM LINHA:
            - flex-row-center -> Irá centralizar os elementos de sua tag, baseando-se no alinhamento em linha;
            - flex-row-left -> Irá alinhar à direita os elementos de sua tag, baseando-se no alinhamento em linha;
            - flex-row-right -> Irá alinhar à direita os elementos de sua tag, baseando-se no alinhamento em linha;
            - flex-row-space-around -> Espaçamento ENVOLTA os elementos de sua tag, baseando-se no alinhamento em linha;
            - flex-row-space-between -> Espaçamento ENTRE dos elementos de sua tag, baseando-se no alinhamento em linha.
        - DISPLAY FLEX EM COLUNA:
            - flex-column-center -> Irá centralizar os elementos de sua tag, baseando-se no alinhamento em coluna;
            - flex-column-center-top -> Irá centralizar os elementos de sua tag, porém fixando-os no topo do elemento;
            - flex-column-center-bottom -> Irá centralizar os elementos de sua tag, porém fixando-os no rodapé do elemento;
            - flex-column-left -> Irá alinhar à direita os elementos de sua tag, baseando-se no alinhamento em coluna;
            - flex-column-right -> Irá alinhar à esquerda os elementos de sua tag, baseando-se no alinhamento em coluna;
            - flex-column-space-around -> Espaçamento ENVOLTA os elementos de sua tag, baseando-se no alinhamento em coluna;
            - flex-column-space-between -> Espaçamento ENTRE os elementos de sua tag, baseando-se no alinhamento em coluna.

    - TAMANHOS E ESPAÇAMENTOS:

        - TAMANHOS:
            - width-100 -> Largura de 100% para o elemento;
            - width-75  -> Largura de 75% para o elemento;
            - width-50  -> Largura de 50% para o elemento;
            - width-25  -> Largura de 25% para o elemento;
        - ESPAÇAMENTOS:
            - padding-100px -> Espaçamento INTERNO de 100px;
            - padding-75px  -> Espaçamento INTERNO de 75px;
            - padding-50px  -> Espaçamento INTERNO de 50px;
            - padding-25px  -> Espaçamento INTERNO de 25px;
            
    - ALINHAMENTO DE TEXTOS:
        - text-center -> Alinha o texto ao centro;
        - text-justify -> Justifica o texto;
        - text-left -> Alinha o texto à esquerda;
        - text-right -> Alinha o texto à direita;

- COMO USAR:

    - MÉTODO 01 (RECOMENDADO):

        - Copie a seguinte URL: https://cdn.jsdelivr.net/gh/DerickCarvalho/DkStrap@main/DkStrap.css
        - Cole-a no href de uma tag linkcss de seu arquivo
        - E pronto, o DkStrap já está funcionando!

    - MÉTODO 02 (PARA MÉTODOS OFFLINE OU POSSÍVEIS PROBLEMAS):

        - Faça o download do DkStrap.css aqui deste repositório;
        - Coloque-o na pasta do seu projeto;
        - Linke-o no href de um linkcss em seu arquivo html/
        - Pronto!
