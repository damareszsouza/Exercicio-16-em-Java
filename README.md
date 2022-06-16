# Exercicio-16-em-Java
Laços wfor e e for- Livro Cartilha Java


Laços
Outro mecanismo de controle de fluxo importante em uma linguagem de programa-
ção é o laço. Java possui três tipos de laços.
Laços while
O tipo mais simples de laço em Java é o laço while. Este tipo de laço testa se uma 
certa condição é satisfeita e executa o corpo do laço enquanto essa condição for 
true. A sintaxe para testar uma condição antes de o corpo do laço ser executado é 
a seguinte:
 while (expressão_booleana)
 corpo_do_laço
No início de cada iteração, o laço testa a expressão booleana, boolean_exp, e então, 
se esta resultar true, executa o corpo do laço, loop_statement. O corpo do laço pode 
ser um bloco de comandos.
Considere-se, por exemplo, um gnomo tentando regar todas as cenouras de seu 
canteiro de cenouras, o que faz até seu regador ficar vazio. Se o regador estiver va-
zio logo no início, escreve-se o código para executar esta tarefa como segue:
 public void waterCarrots( ) {
 Carrot current -
 garden.findNextCarrot ( );
 while (!waterCan.isEmpty ( )) {
 water (current, waterCan);
 current -
 garden.findNextCarrot ( );
 }
 }
Lembre-se de que “!” em Java é o operador “not”.
Laços for
Outro tipo de laço é o laço for. Na sua forma mais simples, os laços for ofere-
cem uma repetição codificada baseada em um índice inteiro. Em Java, entretanto, 
pode-se fazer muito mais. A funcionalidade de um laço for é significativamente 
mais flexível. Sua estrutura se divide em quatro seções: inicialização, condição, 
incremento e corpo.
