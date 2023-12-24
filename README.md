<h1>Explicando o Código</h1>

<h3>Desafio</h3>
<p>O objetivo deste desafio é solicitar ao usuário que forneça dois valores, um inteiro e outro fracionado, armazenando esses valores em duas variáveis (num1 e num2). Em seguida, o programa deve calcular e exibir a divisão desses dois números.</p>

<h3>Código</h3>

<ul>
  <li><b>Entradas:</b></li>
      <ul>
        <li>num1: Solicita ao usuário que insira um valor inteiro utilizando a função input e converte o valor para um número inteiro usando int().</li>
        <li>num2: Solicita ao usuário que insira um valor fracionado (ponto flutuante)       usando a função input e converte o valor para um número de ponto flutuante usando float().        </li>
      </ul>
</ul>
<p>
  num1 = int(input('Digite um valor inteiro: '))<br>
  num2 = float(input('Digite um valor fracionado: '))
</p>
<ul>
  <li><b>Saida:</b</li>
  <ul>
    <li>
      Utiliza a função print para exibir a frase formatada, mostrando os valores de num1 e   num2, bem como o resultado da divisão entre eles.
    </li>
  </ul>
</ul>
<p>
  print(f"A divisão entre {num1} e {num2} é {num1 / num2}")
</p>

<h2>Exemplo de Uso:</h2>
<ul>
  <li>O programa solicitará que o usuário insira um valor inteiro e um valor fracionado.</li>
  <li>Após as entradas, calculará a divisão desses dois números.</li>
  <li>Exibirá o resultado formatado na saída.
  Observação: Certifique-se de inserir valores válidos para evitar erros durante a execução do programa.</li>
</ul>
