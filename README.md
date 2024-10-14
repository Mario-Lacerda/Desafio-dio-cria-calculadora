# Desafio-dio-cria-calculadora
Desafio dio cria calculadora
Programa em Ruby para Solicitar Nome Completo e Idade do Usuário
Vamos criar um simples programa em Ruby que solicita o nome completo e a idade do usuário e, em seguida, exibe essas informações na tela.

Código do Programa
Aqui está um exemplo de como você pode escrever esse programa:

# Solicita o nome completo do usuário
puts "Por favor, digite seu nome completo:"
nome_completo = gets.chomp

# Solicita a idade do usuário
puts "Por favor, digite sua idade:"
idade = gets.chomp

# Exibe a saída
puts "Seu nome completo é: #{nome_completo} e você tem #{idade} anos."
Explicação do Código
puts: Este comando exibe uma mensagem na tela.
gets.chomp: Este comando lê a entrada do usuário e remove a quebra de linha ao final.
#{nome_completo} e #{idade}: Esta é a interpolação de strings, que permite incluir variáveis dentro de uma string.
Como Executar o Programa
Crie um arquivo Ruby chamado usuario_info.rb:

touch usuario_info.rb
Abra o arquivo em um editor de texto e cole o código acima.

Execute o programa no terminal:

ruby usuario_info.rb
Siga as instruções na tela para fornecer seu nome completo e idade.

Exemplo de Saída
Se você executar o programa e inserir, por exemplo, "João da Silva" como nome completo e "30" como idade, a saída será:

Seu nome completo é: João da Silva e você tem 30 anos.
