# prova1

Curso: Sistemas para Internet
Disciplina: Programação para Dispositivos Móveis II
Professora: Ana Paula Alves Guimarães de Cól
Data:


Turma:
Valor: 10.0
Nota:
Nome:



Avaliação da aprendizagem 

Crie um diretório com seu nome completo;
Para que as soluções sejam aceitas, as solicitações nos enunciados devem ser respeitadas, não devem apresentar erros de compilação e nem de execução;
É obrigatório a apresentação em sala sobre a implementação. A não efetivação desta etapa INVALIDA todo processo, dessa forma, o estudante terá o trabalho ZERADO;
O trabalho é individual, portanto, implementações iguais serão INVALIDADAS, dessa forma, o estudante terá o trabalho ZERADO;
Para o trabalho ser aceito com valor integral (10.0), o estudante deve entregar uma implementação parcial no dia da apresentação deste documento (12/11/2024), correspondendo ao item 1, 2 e 3. Caso contrário, o valor do trabalho passa a valer 5.0 pontos;
Design e organização serão também avaliados. Dessa forma, seguem algumas orientações: 
Strings estáticas coloque-as no arquivo string.xml.
As cores devem ser definidas no arquivo colors.xml.
Usem os conceitos de programação orientada a objetos para deixar os métodos, classes coesas e sem repetição.
Usem o padrão MVVM.
Crie um aplicativo com os seguintes requisitos:
1. Use o NavigationDrawer, o menu lateral deve ter os seguintes itens: (valor: 1.0)
Baixar Arquivos;
Converter Deuses;
Converter Armas;
Combinar Deuses e Armas;
Jogar;
Ranking.
Não se esqueça de personalizar o NavigationDrawer com o tema proposto. Personalize os itens, os ícones e imagens. 
2. Seu app deve acessar um arquivo JSON disponível através do recurso MY JSON SERVER (https://my-json-server.typicode.com/). Você deve criar um arquivo JSON que forneça 3 vetores:  
um array cujo conteúdo consiste nos 4 deuses: Zeus, Atena, Hermes e Deméter;
um array cujo conteúdo consiste nas armas: raio, cetro, caduceu e foice;
um array cujo conteúdo consiste nas letras do alfabeto, por exemplo, a = 1, b = 2, c = 3, d = 4 e assim por diante.
 Use a classe Executor.
3. Na aba Baixar deve ser mostrado todos os arrays consumidos (valor: 1.0)
4. Na aba Converter Deuses deve ser mostrado o nome de cada deus com o seu nome já convertido. Use o array de alfabeto para fazer a conversão. Por exemplo: ZEUS, sendo que Z = 26, E = 5, U = 21 e S = 19, o valor convertido do nome será a soma total de cada caractere 26 + 5 + 21 + 19 = 71. (valor: 1.0)
5. Na aba Converter Armas deve ser feito o mesmo processo de conversão como mostrado no item 4. (valor: 1.0)
6. Na aba Combinar Deuses e Armas deve ser mostrado a combinação de cada elemento do vetor Deuses com cada elemento do vetor Armas, ou seja, Zeus Raio, Zeus Cetro, Zeus Caduceu e assim por diante com seus respectivos valores. Portanto, este array deve ter 16 elementos.  (valor: 1.5)
7. Na aba Jogar, deve ser solicitado: (valor: 2.0)
O nome do usuário e um valor inteiro. Esse valor será usado para escolher um item do vetor combinação criado no item 6. 
O seu app deve escolher um elemento randômico que também corresponderá a um item do vetor combinação. 
Seu app deve mostrar cada elemento sorteado.
Os valores devem ser comparados e deve ser mostrado quem ganhou o jogo.
8. Na aba Ranking, deve ser mostrado a lista de jogadas (valor: 1.0)
9.  No botão flutuante deve ter um ícone de disquete que ao ser clicado deve solicitar a permissão para acessar a câmera do dispositivo e salve a imagem do Ranking em um arquivo interno. (valor: 1.0)

10. No menu flutuante ao ser clicado deve ser mostrado um mapa com um marcador personalizado (um girassol) focando na Praça dos Girassóis. (valor: 0.5)
