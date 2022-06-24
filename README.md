# :computer: Repositório destinado a resolução de exercícios da disciplina de Programação Orientada a Objetos - BSI-UFRN

### [Exercícios - Texto 02](https://sites.google.com/view/fabricio10/p%C3%A1gina-inicial/cursos/poo1/texto02)
  2. Receber dois inteiros e retorná-los em ordem crescente
  3. Receber três números reais e retorná-los em ordem decrescente
  4. Receber um número real e retornar sua raiz quadrada
  5. Receber dois Strings e informar se o primeiro String está contido no segundo (use o método indexOf)
  6. Receber dois Strings e retorná-los em ordem alfabética (use o método compareTo)
  7. Receber três Strings e retorná-los em ordem alfabética (use o método compareTo)
  8. Receber um array de Strings na forma "nome sobrenome" e retornar um array na forma "sobrenome, nome" (use os métodos indexOf e substring)
  9. Receber um array de Strings e modificá-lo de forma que todos os seus itens fiquem com todas as letras maiúsculas (use o método toUpperCase)
  10. Receber um array de Strings e retornar um array com os mesmos Strings mas com todas as letras maiúsculas (use o método toUpperCase)
  11. Receber um vetor de inteiros. Percorrer o vetor com um comando for. A cada repetição, troque o elemento corrente com o que estiver uma posição à frente sempre que o elemento da frente for menor que o elemento corrente. 
  12. Adapte o exercício anterior de forma que as trocas sejam efetuadas e, além disso, o método retorne a quantidade de trocas realizadas. 
  13. Adapte o exercício anterior para que funcione com um vetor de Strings e faça as trocas sempre que um String for lexicograficamente maior que o String que está à sua frente no vetor. Lembre de retornar o número de trocas.
  14. (Desafio) Receber um vetor de inteiros e modificá-lo para que fique em ordem decrescente. Dica de amigo: se você usar o método do exercício 2.12 e a quantidade de trocas retornada for 0 (zero), o vetor estará ordenado. É possível chamar um método de dentro de outro, assim como em qualquer linguagem de programação que você já estudou.
  15. (Desafio) Receber um vetor de Strings e modificá-lo para que fique ordem alfabética. Dica de amigo: veja a dica de amigo da questão anterior.
  16. (Desafio) Receber um vetor de Strings na forma "nome sobrenome" e modificá-lo para que fique ordenado alfabeticamente por sobrenome. Por exemplo: se o vetor {"robert plant", "ian gillan", "neil young"} for passado como parâmetro, após a execução do método, o conteúdo do vetor deve ser {"ian gillan", "robert plant",  "neil young"}. Sem dicas, se vire sozinho.
  17. (Desafio) Receber um vetor de Strings na forma "nome sobrenome" e modificá-lo para que fique ordenado alfabeticamente por sobrenome e com a forma dos strings alterada para "sobrenome, nome".  Por exemplo: se o vetor {"robert plant", "ian gillan", "neil young"} for passado como parâmetro, após a execução do método, o conteúdo do vetor deve ser {"gillan, ian", "plant, robert",  "young, neil"}

### [Exercícios - Texto 03](https://sites.google.com/view/fabricio10/p%C3%A1gina-inicial/cursos/poo1/texto03)

  1. Obter a data atual do sistema e retorná-la na forma de String.
  2. Receber uma data (como String) no formato dd/mm/aaaa e retornar a mesma data (como String) no formato "<dia da semana>, <dia> de <nome do mês> de <ano>"
  3. Receber um caminho de diretório como parâmetro e retornar um vetor com todos os itens do diretório. Dica: objetos da classe File podem ser usados para realizar operações sobre diretórios, entre várias outras coisas. Analise a documentação da classe File para saber além do que já foi descrito no conteúdo deste texto.
  4. Receber um caminho de diretório como parâmetro e retornar um vetor com todos os itens do diretório. Cada item do vetor retornado deve estar precedido por "[A]", caso seja arquivo, e "D", caso seja diretório. Retorne um valor nulo caso o String recebido como parâmetro não corresponda a um diretório existente no disco. Mais uma vez, você precisará de um objeto da classe File para fazer o trabalho sujo para você.
  5. Receber um caminho para um arquivo como parâmetro e deletar o arquivo. 
  6. (Desafio) Escreva um programa que mostre uma janela com dois menus - Arquivo e Editar. Dica: você deverá utilizar objetos das classes JFrame, JMenuBar e JMenu). 
  7. (Desafio) Escreva um método que receba como parâmetro um String representando um caminho para um arquivo executável e execute tal arquivo. Dica: pesquise no google "java como executar programas externos" (SEM as aspas) e seja feliz (você pode ter que escrever código que não vai entender bem - a ideia aqui é que você desenrole a solução independentemente de entender o que está acontecendo. Acredite, isso lhe será muito útil em sua vida de programador)
  8. (Desafio) Escreva um método que receba o caminho de um arquivo de texto (txt) e abra o arquivo no bloco de notas (notepad no windows ou qualquer gedit no Ubuntu). Dica: você vai precisar apenas da solução da questão anterior e de um real a mais de esperteza.
  9. (Desafio) Faça um método que mostre uma Janela (vazia) do tamanho da tela. O programa deve funcionar em monitores com diferentes resoluções. Dica de professor: a classe ToolKit pode prover o tamanho da tela. Dica de MÃE: pesquise "como criar uma janela tela cheia em java" (sem aspas, pelo amor de Deus) e seja feliz.
  10. Receber duas datas como parâmetro e retornar a mais recente
  11. (Desafio) Receber um array de Dates e modificar o array de forma que fique em ordem cronológica. Dica: use o método compareTo da classe Date
  12. Receber uma data, na forma de String, no formato dd/mm/aaaa, e retornar o dia da semana referente à data.

### Série de Lucas
Cada Série de Lucas tem dois números inteiros fixos, p e q, que servem para calcular os termos da série.
Os termos da série são calculados da seguinte maneira:
* o primeiro termo é sempre 0
* o segundo termo é sempre 1
* o terceiro termo é calculado com base nos dois termos anteriores e nos valores de p e q. Se Xn for o enésimo termo, ele deverá ser calculado assim: Xn = p*Xn-1 - q*Xn-2, onde Xn-1 é o termo anterior a Xn e Xn-2 é o termo anterior a Xn-1.

Exemplos:
  
Uma Série de Lucas com p=1 e q=-1 seria: 
0 1 1 2 3 5 8 13...
  
[a Série de Fibonacci é um caso particular da série de Lucas]
Uma série de Lucas com p=2 e q=1 seria:
0 1 2 3 4 5 6...

Uma série de Lucas com p=2 e q=-1 seria:
0 1 2 5 12 29...

Agora reflita sobre uma potencial classe, SerieDeLucas, para calcular termos de séries de Lucas nos mesmos moldes que a classe que estudamos, SerieDeFibonacci, calcula termos de uma série de Fibonacci (ver vídeo-aula no canal da disciplina). Um objeto dessa classe SerieDeLucas deve, essencialmente, calcular, termo a termo, os números da série através de chamadas de um mesmo método, cada chamada calculando o termo seguinte (como faz a classe SerieDeFibonacci). Sob hipótese nenhuma chamadas sucessivas a um método para calcular o termo seguinte, num mesmo objeto, devem retornar valores que não estejam de acordo com os valores p e q que foram atribuídos ao objeto quando de sua criação.

Escreva na classe um método para calcular o próximo termo da série e um método para saltar n termos na série. Escolha os parâmetros adequados para a classe.
  
### Escola
  Considere as classes...
public class Estado{
 private String nome;
 private Cidade[] cidades;
 //construtores, gets e sets...
}
  
public class Cidade{
 private String nome;
 private Escola[] escolas;
 //construtores, gets e sets...
}

public class Escola{
 private String nome;
 private ArrayList<Estudante> estudantes;
 //construtores, gets e sets...
}

public class Estudante{
 private Strig cpf;
 private int nivelLeitura;
 //construtores, gets e sets...
}

Escreva métodos gets, sets e construtores para as classes e escreva métodos, também, para:
* calcular nível médio de leitura de uma escola (média dos níveis de leitura dos estudantes)
* calcular nível médio de leitura de uma cidade (média dos níveis de leitura das escolas)
* calcular nível médio de leitura de um estado (média dos níveis de leitura das cidades)
* obter estudantes de uma escola que estejam acima de uma determinada média
* obter estudantes de uma escola que estejam acima da média da própria escola
  
### Rede de Mercadinhos
  
public class Produto{
   private String descricao;
   private double preco;
   //construtores, gets e sets
}

public class Item{
   private int quantidade;
   private Produto produto;
   //construtores, gets e sets
}
  
public class Venda{
   private String data;
   private Item[] itens;
   //construtores, gets e sets
}

public class Mercadinho{
   private Venda[] vendas;
   //construtores, gets e sets
}

* implemente uma rede de mercadinhos
* implemente método para retornar o total de todas as vendas de um mercadinho
* implemente método para retornar o total de vendas de toda uma rede de mercadinhos
* implemente método para retornar todas as vendas de um determinado mês
* implemente método para retornar o total de todas as vendas de um determinado mês
