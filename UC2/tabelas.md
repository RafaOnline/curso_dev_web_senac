# 🧾 Aula 9 - Uso de Tabelas em HTML5

## 📚 **O que é uma Tabela no HTML?**

Uma **tabela** serve para organizar informações em **linhas e colunas**, como se fosse uma planilha do Excel. Ela é muito útil para exibir dados de forma clara e organizada.

# 🧠 **Exercícios Práticos**

### 1️⃣ **Tabela de Filmes**

Crie uma tabela com pelo menos 4 filmes. Cada filme deve ter:

* Nome
* Ano de lançamento
* Gênero
* Nota (de 0 a 10)

Inclua cabeçalho (`<thead>`) e corpo (`<tbody>`).

---

### 2️⃣ **Tabela de Horários de Aulas**

Monte uma tabela que simule os horários de uma turma com:

* Dias da semana
* Matérias
* Horário de início e fim

Inclua também um rodapé (`<tfoot>`) indicando o total de horas da semana.

---

### 3️⃣ **Tabela de Lista de Compras**

Crie uma tabela com:

* Item
* Quantidade
* Preço unitário
* Preço total do item

No rodapé some todos os preços para mostrar o valor total da compra.

---

### 4️⃣ **Desafio Extra**

Monte uma tabela de classificação de um campeonato de algum esporte que você goste, com pelo menos:

* Time / Jogador
* Jogos
* Vitórias
* Derrotas
* Pontos

Capriche no uso do `<thead>`, `<tbody>` e `<tfoot>`.

---

Código:
```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tabelas</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-sRIl4kxILFvY47J16cr9ZwB07vP4J8+LH7qKQnuqkuIAvNWLzeN8tE5YBujZqJLB" crossorigin="anonymous">
</head>

<body class="container">
    <div>
        <h1 class="text-center mb-4">Exercício criação de tabelas</h1>
    </div>
    <div>
        <h2 class="text-center">Filmes</h2>
        <table class="table table-bordered mb-5">
            <thead>
                <th>Nome</th>
                <th>Ano de lançamento</th>
                <th>Gênero</th>
                <th>Nota (de 0 a 10)</th>
            </thead>

            <tr>
                <td>O Senhor dos Anéis: O Retorno do Rei</td>
                <td>2003</td>
                <td>Fantasia / Aventura</td>
                <td>9.5</td>
            </tr>

            <tr>
                <td>A Origem (Inception)</td>
                <td>2010</td>
                <td>Ficção Científica</td>
                <td>9.0</td>
            </tr>

            <tr>
                <td>Gladiador</td>
                <td>2000</td>
                <td>Ação / Drama</td>
                <td>8.7</td>
            </tr>

            <tr>
                <td>Vingadores: Ultimato</td>
                <td>2019</td>
                <td>Ação / Super-heróis</td>
                <td>8.8</td>
            </tr>

        </table>

    </div>

    <div>
        <h2 class="text-center">Horário de aulas</h2>
        <table class="table table-bordered mb-5">
            <thead>
                <th>Dia da Semana</th>
                <th>Matéria</th>
                <th>Horário de Início</th>
                <th>Horário de Fim</th>
            </thead>

            <tr>
                <td>Segunda-feira</td>
                <td>Matemática</td>
                <td>08:00</td>
                <td>09:30</td>
            </tr>

            <tr>
                <td>Terça-feira</td>
                <td>Português</td>
                <td>09:40</td>
                <td>11:10</td>
            </tr>

            <tr>
                <td>Quarta-feira</td>
                <td>História</td>
                <td>08:00</td>
                <td>09:30</td>
            </tr>

            <tr>
                <td>Quinta-feira</td>
                <td>Ciências</td>
                <td>09:40</td>
                <td>11:10</td>
            </tr>

            <tfoot>
                <tr>
                    <td class="fw-semibold">Total de horas:</td>
                    <td colspan="3" class="text-center">06:00</td>
                </tr>
            </tfoot>

        </table>
    </div>

    <div>
        <h2 class="text-center">Lista de compras</h2>

        <table class="table table-bordered mb-5">

            <thead>
                <th>Item</th>
                <th>Quantidade</th>
                <th>Preço Unitário (R$)</th>
                <th>Preço Total do Item (R$)</th>
            </thead>

            <tr>
                <td>Arroz (5kg)</td>
                <td>2</td>
                <td>25,00</td>
                <td>50,00</td>
            </tr>

            <tr>
                <td>Óleo de cozinha (900ml)</td>
                <td>2</td>
                <td>7,50</td>
                <td>15,00</td>
            </tr>

            <tr>
                <td>Feijão (1kg)</td>
                <td>3</td>
                <td>8,00</td>
                <td>24,00</td>
            </tr>

            <tr>
                <td>Açúcar(5kg)</td>
                <td>1</td>
                <td>20,00</td>
                <td>20,00</td>
            </tr>

            <tfoot>
                <tr>
                    <td class="fw-semibold">Total de compra:</td>
                    <td colspan="3" class="text-center">R$ 109,00</td>
                </tr>
            </tfoot>

        </table>

    </div>

    <div>
        <h2 class="text-center">Campeonatos CS:GO 2</h2>
        <table class="table table-bordered mb-5">

            <thead>
                <th>Time</th>
                <th>Jogos</th>
                <th>Vitórias</th>
                <th>Derrotas</th>
                <th>Pontos</th>
            </thead>

            <tr>
                <td>G2 Esports</td>
                <td>6</td>
                <td>6</td>
                <td>0</td>
                <td>6</td>
            </tr>

            <tr>
                <td>Ninjas in Pyjamas</td>
                <td>6</td>
                <td>4</td>
                <td>2</td>
                <td>4</td>
            </tr>

            <tr>
                <td>OpTic Gaming</td>
                <td>6</td>
                <td>2</td>
                <td>4</td>
                <td>2</td>
            </tr>

            <tr>
                <td>Selfless Gaming</td>
                <td>6</td>
                <td>0</td>
                <td>6</td>
                <td>0</td>
            </tr>

        </table >
    </div>
</body>

</html>
```

Resultado:

<img width="777" height="884" alt="image" src="https://github.com/user-attachments/assets/2426a06a-251e-4f11-8bdb-372d301061e8" />

## 💻 Tecnologias Utilizadas
- HTML5 – estrutura da página
- Bootstrap 5.3.8 – estilização e layout responsivo
- Formulários nativos do HTML – para entrada de dados



## 🚀 **Conclusão**

Tabelas são muito úteis para dados organizados, relatórios, rankings e listas. Aprender a fazer uma tabela bem estruturada com HTML5 é essencial para qualquer desenvolvedor web!
