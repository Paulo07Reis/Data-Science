# Matemática para Data Science: construindo a base

---

- **Fração:**
    
    $$
    \frac{P}{Q} 
    $$
    
    P: Numerador  Q: Denominador
    
    ---
    
    Equivalência de frações:
    
    $$
    \frac{150}{200} = \frac{75}{100} = \frac{15}{20} = \frac{3}{4} = 0,75
    $$
    
    ---
    
    Soma:
    
    $$
    \frac{A}{B} + \frac{C}{D} = \frac{AD + BC}{BD}
    $$
    
    Exemplo: 
    
    $$
    \frac{2}{5} + \frac{1}{3} = \frac{11}{15} <----> \frac {1}{1} - \frac{11}{15} = \frac {4}{15}
    $$
    
    ---
    
    Multiplicação: 
    
    $$
    \frac {4}{5} * \frac {1}{4} = \frac {4}{20} = \frac {1}{5}
    $$
    
    ---
    
    Divisão: 
    
    $$
    \frac{A}{B} / \frac{C}{D} = \frac{A}{B} * \frac{D}{C}
    $$
    
    Exemplo:
    
    $$
    \frac{3}{4} / \frac{1}{2} = \frac{3}{4} * \frac{2}{1} = \frac{6}{4} = 1,5
    $$
    
- **Porcentagem:**
    
    Uma mediada de razão com base 100 → 5% = 5/100
    
    ---
    
    Exemplo: 
    
    Vendas → 60.000
    
    Eletrônicos → 30% 
    
    $$
    60.000 * \frac{30}{100} = 60.000  * 0,3 = 18.000
    $$
    
    ---
    
    Aumento e Reduções
    
    Inicial: 800
    
    Final: 1000
    
    Qual o aumento percentual? 
    
    $$
    1000 - 800 = 200
    $$
    
    $$
    \frac{800}{200}=\frac{100}{x}
    $$
    
    $$
    800x = 20000 
    $$
    
    $$
    x = 20000/800
    $$
    
    $$
    x = 25
    $$
    
    ---
    
    Acertos: 11.960
    
    Total: 13.000
    
    Qual a taxa de acerto?
    
    $$
    13.000x = 1.196.000
    $$
    
    $$
    x = 1.196.000/13.000
    $$
    
    $$
    x = 92
    $$
    
    ---
    
    CC: 550
    
    Boleto: 300
    
    CD: 250
    
    Cheque: 150
    
    Total: 1250
    
    550/1250 = 0,44 → 44%
    
    300/1250 = 0,24 → 24%
    
    150/1250 = 0,12 → 12%
    
    250/1250 = 0,2 → 20%
    
- **Potenciação:**
    
    $$
    a^n
    $$
    
    A: Base
    
    N: Expoente
    
    ---
    
    Fevereiro 1.000 → Março 2.000 → Abril 4.000 → Maio 8.000 ou…
    
    $$
    1.000*2^3
    $$
    
    ---
    
    Multiplicação:
    
    $$
    a^n*a^m = a^{n+m}
    $$
    
    $$
    3^4*3^7=3^{11}
    $$
    
    ---
    
    Divisão:
    
    $$
    \frac{a^n}{a^m} = a^{n-m}
    $$
    
    $$
    \frac{5^8}{5} = 5^{8-1} = 5^7
    $$
    
    ---
    
    Potência de potência: 
    
     
    
    $$
    (a^n)^m = a^{n*m}
    $$
    
    $$
    (4^3)^7 = a^{3*7}= 4^{21}
    $$
    
    ---
    
    Casos especiais:
    
    $$
    \frac{7^3}{7^3} = 7^0 = 1
    $$
    
    $$
    \frac{7^2}{7^4} = 7^{2-4} = 7^{-2} = \frac {1}{7^2} = \frac{1}{49}
    $$
    
    $$
    (-4)^2 = (-4)*(-4) = 16
    $$
    
    $$
    (-4)^3 = (-4)*(-4)*(-4) = -64
    $$
    
    - Se a base  é negativa, e o expoente é par → resultado positivo
    - Se a base é negativa, e o expoente é impar → resultado é negativo
    
    ---
    
    Notação científica:
    
    $$
    51.300.000.000 -> 5,13*10^{10}
    $$
    
    $$
    0,000000000762 = 7,62*10^{-10}
    $$
    
    ---
    
    Exercício: 
    
    Inicio = 500
    
    $$
    500 * 3^3 = 500 * 27 = 13.500
    $$
    
- **Radiciação:**
    
    Operação inversa da exponenciação
    
    $$
    \sqrt[n]a
    $$
    
    N → Indíce
    
    A → Radicando 
    
    Na exponenciação, queríamos descobrir o resultado da operação de um valor elevado a outro 
    
    Na radiação, queremos descobrir qual o número, que multiplicado por si mesmo n vezes, resulta em um outro número conhecido. 
    
    $$
    x^n = a  --x = \sqrt[n]a
    $$
    
    $$
    \sqrt100
    $$
    
    $$
    x^2 = 100
    $$
    
    $$
    100 = 2*5+2*5 = 10 *10=10^2
    $$
    
    ---
    
    Multiplicação
    
    $$
    \sqrt[n]ab = \sqrt[n]a * \sqrt[n]b
    $$
    
    $$
    \sqrt[2]100*49 = \sqrt[2]4900 = 70
    $$
    
    $$
    \sqrt[2]100 * \sqrt[2]49 = 10 * 7 = 70
    $$
    
    ---
    
    Divisão: 
    
    $$
    \sqrt[n]{\frac{a}{b}} = \frac{\sqrt[2]a}{\sqrt[2]b}
    $$
    
    $$
    \sqrt[n]{\frac{100}{25}} = \frac{\sqrt[2]100}{\sqrt[2]25} = \frac{10}{5} = 2
    $$
    
    ---
    
    Exponenciação:
    
    $$
    \sqrt[n]{a^m} = (\sqrt[n]a)^m
    $$
    
    $$
    \sqrt[3]{8^2} = \sqrt[3]64 = 4
    $$
    
    $$
    (\sqrt[3]8)^2 = (2)^2 = 4
    $$
    
    ---
    
    Radiciação 
    
    $$
    \sqrt[m]{\sqrt[n]a} = \sqrt[m*n]a
    $$
    
    $$
    \sqrt[3]{\sqrt[2]64} = \sqrt[3*2]64 = \sqrt[6]64 = 2
    $$
    
    ---
    
    Expoente fracionário
    
    $$
    \sqrt[n]{a^m} = a^{\frac{m}{n}}
    $$
    
    $$
    \sqrt[4]{3^2} = 3^{\frac{2}{4}} = 3^{\frac{1}{2}} = \sqrt3
    $$
    
    ---
    
    Radiciação de negativos
    
    - Se o radicando é negativo, e o índice é par → Não existe solução
    - Se o radicando é negativo, e o índice é ímpar → Resultado negativo
- **Logaritmo:**
    
    Operação inversa da exponenciação
    
    $$
    log_{b} a = x
    $$
    
    B = Base 
    
    A = logaritmando
    
    X = Logaritmo
    
    No logaritmo, o foco muda para o expoente. O logaritmo de um número positivo (a), na base (b), é um expoente pelo qual (b) deve ser elevado para se chagar a (a)
    
    $$
    log_{b} a = x - b^x = a 
    $$
    
    $$
    log_{3} 2187 = x <-> 3^x = 2187 
    $$
    
    $$
    2187 = 3^7
    $$
    
    ---
    
    Produto: 
    
    $$
    log_b(m*n)= log_bm + log_bn
    $$
    
    $$
    log_3(9*27)= log_39 + log_327
    $$
    
    $$
    3^x=9 <-> 3^y=27
    $$
    
    $$
    x=2 <-> x=3
    $$