Localizador do Primeiro Positivo Ausente
Bem-vindo ao projeto Localizador do Primeiro Positivo Ausente! Este programa em Java, simples mas elegante, mergulha em um array de inteiros para encontrar o menor inteiro positivo que está faltando. É como brincar de esconde-esconde com números, onde determinamos qual número positivo está se escondendo melhor de nós por não estar presente na lista.

Como Funciona?
Imagine que você tem uma fila de caixas numeradas onde cada caixa só pode conter o número correspondente à sua posição na fila. Por exemplo, a caixa 1 deve conter o número 1, a caixa 2 deve conter o número 2, e assim por diante. Agora, suponha que temos um monte de bolas numeradas que devem ir para essas caixas, mas notamos que algumas bolas estão faltando e algumas estão nas caixas erradas.

Etapa 1: Organizando as Bolas
Primeiro, passamos por cada bola e a colocamos na caixa correta. Se uma bola está rotulada com um número maior que a contagem total de caixas ou é negativa, deixamos ela de lado porque ela não nos ajuda a encontrar o menor número positivo ausente.

Etapa 2: Encontrando a Bola Ausente
Após a organização, olhamos para cada caixa na ordem. A primeira caixa que não tem a bola correta revela o menor número positivo que está faltando. Se todas as caixas têm as bolas corretas, então o número que falta é um a mais do que o total de caixas.

Entendendo o Código
Nós iteramos pelo array (nums), tentando colocar cada número na sua posição ideal (por exemplo, número 1 na posição 0).
Se um número já está em seu lugar correto ou não se encaixa no nosso array (números negativos ou muito grandes), seguimos adiante.
Após reordenar, fazemos outra passagem pelo array para encontrar a primeira posição onde os números não se alinham com seus índices, o que nos diz o menor número positivo ausente.
Se todos os números estão presentes e corretamente posicionados, o número que falta é apenas um a mais do que o comprimento do array.

*Como Executar o Programa
*Configuração: Certifique-se de ter o Java instalado em seu computador.
Salvar o Código: Copie o código para um arquivo chamado Solution.java.
Compilar: Abra seu terminal ou prompt de comando, navegue até o diretório contendo Solution.java, e execute javac Solution.java.
Executar: Rode o programa com java Solution.
