# Desafio-dio-cria-calculadora
Desafio dio cria calculadora
Programa em Ruby para Cálculos com Escolhas do Usuário
Vamos criar um programa em Ruby que apresenta ao usuário uma lista de operações matemáticas e realiza o cálculo com base na escolha do usuário.

Código do Programa
Aqui está um exemplo de como você pode escrever esse programa:

# Função para realizar as operações
def calcular(opcao, num1, num2)
  case opcao
  when 1
    num1 + num2
  when 2
    num1 - num2
  when 3
    num1 * num2
  when 4
    num1 / num2
  else
    "Opção inválida!"
  end
end

# Apresenta a lista de escolhas
puts "Escolha uma operação:"
puts "1. Adição"
puts "2. Subtração"
puts "3. Multiplicação"
puts "4. Divisão"

# Lê a escolha do usuário
print "Digite o número da operação: "
opcao = gets.chomp.to_i

# Lê os números
print "Digite o primeiro número: "
num1 = gets.chomp.to_f

print "Digite o segundo número: "
num2 = gets.chomp.to_f

# Realiza o cálculo e exibe o resultado
resultado = calcular(opcao, num1, num2)
puts "O resultado é: #{resultado}"
Explicação do Código
Função calcular: Recebe a opção e os dois números, realizando a operação correspondente.
case: Estrutura que verifica qual operação o usuário escolheu.
gets.chomp: Lê a entrada do usuário e remove a quebra de linha.
to_i e to_f: Convertem a entrada para inteiro e float, respectivamente.
Como Executar o Programa
Crie um arquivo Ruby chamado calculadora.rb:

touch calculadora.rb
Abra o arquivo em um editor de texto e cole o código acima.

Execute o programa no terminal:

ruby calculadora.rb
Siga as instruções na tela para escolher a operação e inserir os números.

Exemplo de Saída
Se você escolher a opção de adição e inserir os números 5 e 10, a saída será:

O resultado é: 15.0
