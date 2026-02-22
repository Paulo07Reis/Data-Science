### **Introdução a conjuntos, elementos e subconjuntos**
    
Conjunto é uma coleção de elementos

Tipos:

- Coleção de números
- Registros filtrados
- Colunas de uma base de dados
- Categoria de produtos
- Grupos de clientes

---

Conjunto vazio - sem nenhum objeto

Conjunto universo - Contém todos os elementos possíveis em uma análise

---

**Pertinência** 

- Pertence = ∈
- Não pertence = ∉

```jsx
Exemplo:
    A = {1,2,3}
    -> 3 ∈ A
    -> 4 ∉ A
```

---

**Subconjuntos:** 

Dizemos que um subconjunto A é subconjunto de outro conjunto B, se todos os elementos de A pertencem a B

```jsx
Exemplo:
    A = {1,2,3}
    B = {1,2,3,5,7}
    C = {1,2,3,6,7}
    A é subconjunto de B e C, mas B não é subconjunto de C
```

Como definir:

- Subconjunto = ⊂
- Não é subconjunto = ⊄
- **Operações com conjuntos e aplicações em dados**

Operações entre conjuntos: 

- União
- Interseção
- Diferença
- Complemento

---

**União (∪):**

O resultado da união de dois conjuntos é um conjunto de todos os elementos que pertencem a pelo menos um dos dois conjuntos

```jsx
A = {3,5,8,10}
B = {2,5,6,8,9}
A∪B = {2,3,5,6,8,9,10}
```

---

**Interseção (∩):** 

O resultado da interseção de dois conjuntos é um conjunto de todos os elementos que pertencem aos dois conjuntos simultaneamente.

```jsx
A = {3,5,8,10}
B = {2,5,6,8,9}
A∩B = {5,8}
```

---

Diferença (\ ou -):

O resultado da diferença de um conjunto A por B é um conjunto de todos os elementos de A que não pertencem a B.

```jsx
A = {1,3,5,8,10}
B = {2,5,6,8,9}
A\B = {1,3,10}
```

---

**Complementar:**

O complementar de um conjunto A é um conjunto de elementos que não estão em A. Pode ser entendido como a diferença entre o conjunto Universo e o conjunto A

```jsx
A = {1,3,5,8,10}
U = {1,2,3,4,5,6,7,8,9,10}
U\A = {2,4,,6,7,9}
```

### **Lógica proposicional e conectivos lógicos**

**O que é uma proposição?**

Uma proposição lógica é uma declaração que pode ser verdadeira ou falsa, mas nunca ambas.

---

Conectivos lógicos: 

---

**Disjunção (V\ou):**

A disjunção é avaliada a partir de duas proposições lógicas. A disjunção é verdadeira se pelo menos uma das proposições for verdadeira

| p | q | p ou q |
| --- | --- | --- |
| V | V | V |
| V | F | V |
| F | V | V |
| F | F | F |

---

**Conjunção (^\e)**

A conjunção é avaliada a partir de duas proposições lógicas. A conjunção é verdadeira quando todas as proposições forem verdadeiras.

| p | q | p e q |
| --- | --- | --- |
| V | V | V |
| V | F | F |
| F | V | F |
| F | F | F |

---

**Negação (~):**

A negação inverte o valor lógico da proposição lógica. Se for verdadeiro, se torna falso. Se for falso, se torna verdadeiro.

| p | q | ~ (p e q) |
| --- | --- | --- |
| V | V | F |
| V | F | V |
| F | V | V |
| F | F | V |

---

**Condicional (se… então…):**

A implicação representa uma regra condicional. Se uma proposição é verdadeira, então a outra também deve ser.  

| p | q | p → q |
| --- | --- | --- |
| V | V | V |
| V | F | F |
| F | V | V |
| F | F | V |
- **Tabelas verdade, equivalências e negações**

### Operações lógicas compostas:

Em muitos casos, os filtros que aplicamos em nossos dados envolvem múltiplas condições encadeadas. 

---

Usamos E, OU e negações para compor expressões lógicas complexas - e prever o comportamento dessas expressões é fundamental para garantir que estamos analisando o grupo certo. 

---

Exemplo: 

Em uma base de dados de transações financeiras precisamos identificar transações suspeitas que: 

- Tem valor muito alto (A)
- OU local incomum (B)
- E não são de clientes com histórico suspeito (C)

| A  | B | C | (A ou B) e  ~ C |
| --- | --- | --- | --- |
| V | V | V | F |
| V | V | F | V |
| V | F | V | F |
| V | F | F | V |
| V | V | V | F |
| V | V | F | V |
| V | F | V | F |
| V | F | F | V |
| F | V | V | F |
| F | V | F | V |
| F | F | V | F |
| F | F | F | F |
| F | V | V | F |
| F | V | F | V |
| F | F | V | F |
| F | F | F | F |
