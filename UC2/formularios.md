# 🧑‍🏫 Aula 8 - **Formulários em HTML5**

### 🎯 **Objetivos de Aprendizagem**

* Compreender a função e estrutura de um formulário HTML.
* Utilizar corretamente os principais elementos de formulário (`<form>`, `<input>`, `<textarea>`, `<select>`, etc).
* Aplicar novos tipos de inputs do HTML5 (como `email`, `number`, `date`, `color`, etc).
* Usar atributos de validação e acessibilidade (`required`, `placeholder`, `pattern`, `aria-*`).
* Criar um formulário funcional e semântico para uma aplicação web.

---

### 🧠 **Atividade Prática**

Crie um formulário de **cadastro de usuário** contendo:

* Nome completo
* E-mail
* Senha
* Data de nascimento
* Gênero (radio)
* Interesses (checkbox)
* Campo de texto para “Sobre você”
* Botão “Enviar”

💡 *Desafio extra:* adicionar validações com `pattern`, `required`, `min`, `max`, e estilizar o formulário com CSS.

---

## 💻 Tecnologias Utilizadas
- HTML5 – estrutura da página
- Bootstrap 5.3.8 – estilização e layout responsivo
- Formulários nativos do HTML – para entrada de dados

Código:
```html
<!DOCTYPE html>
<html lang="pt-BR">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Exercício aula 8 - Formulário</title>

    <!-- Importando o framework CSS Bootstrap 5 para estilização responsiva -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-sRIl4kxILFvY47J16cr9ZwB07vP4J8+LH7qKQnuqkuIAvNWLzeN8tE5YBujZqJLB" crossorigin="anonymous">
</head>

<body>
    <!-- Container principal com largura reduzida e espaçamento -->
    <div class="container-sm w-75 mt-5 mb-5 mx-auto">
        <h1 class="text-center">Formulário para inscrição</h1>

        <!-- Início do formulário -->
        <form action="/cadastro" method="post">
            <!-- Campo: Nome e Sobrenome, organizados lado a lado -->
            <div class="row mb-3">
                <div class="col">
                    <label for="nome_completo" class="form-label">Nome: </label>
                    <input class="form-control" type="text" name="nome_completo" id="nome_completo"
                        placeholder="Digite seu primeiro nome" required>
                </div>

                <div class="col">
                    <label for="sobrenome_completo" class="form-label">Sobrenome: </label>
                    <input class="form-control" type="text" name="sobrenome_completo" id="sobrenome_completo"
                        placeholder="Digite seu sobrenome" required>
                </div>
            </div>

            <!-- Campo: E-mail -->
            <div class="mb-3">
                <label for="email_usuario" class="form-label">E-mail: </label>
                <input class="form-control" type="email" name="email_usuario" id="email_usuario"
                    placeholder="Digite seu e-mail" required>
            </div>

            <!-- Campo: Senha -->
            <div class="mb-3">
                <label for="senha_usuario" class="form-label">Senha: </label>
                <input class="form-control" type="password" name="senha_usuario" id="senha_usuario"
                    placeholder="Digite sua senha" required>
            </div>

            <!-- Campo: Data de nascimento -->
            <div class="mb-3 w-50">
                <label for="data_nascimento_usuario" class="form-label">Data de nascimento: </label>
                <input class="form-control" type="date" name="data_nascimento_usuario" id="data_nascimento_usuario"
                    required>
            </div>

            <!-- Campo: Gênero (radio buttons - seleção única) -->
            <legend>Gênero</legend>
            <div class="form-check mb-3">
                <div>
                    <input class="form-check-input" type="radio" name="genero_usuario" id="genero_feminino"
                        value="feminino" required>
                    <label class="form-check-label" for="genero_feminino">Feminino</label>
                </div>

                <div>
                    <input class="form-check-input" type="radio" name="genero_usuario" id="genero_masculino"
                        value="masculino" required>
                    <label class="form-check-label" for="genero_masculino">Masculino</label>
                </div>
            </div>

            <!-- Campo: Interesses (checkboxes - múltipla seleção) -->
            <legend>Interesses</legend>
            <div class="form-check mb-3">
                <div>
                    <input class="form-check-input" type="checkbox" name="interesses[]" id="jogar_game">
                    <label class="form-check-label" for="jogar_game">Jogar videogame</label>
                </div>

                <div>
                    <input class="form-check-input" type="checkbox" name="interesses[]" id="ler_livro">
                    <label class="form-check-label" for="ler_livro">Ler livros</label>
                </div>

                <div>
                    <input class="form-check-input" type="checkbox" name="interesses[]" id="estudar">
                    <label class="form-check-label" for="estudar">Estudar</label>
                </div>
            </div>

            <!-- Campo: Texto livre sobre o usuário -->
            <div class="mb-3">
                <label for="sobre_voce" class="form-label">Sobre você</label>
                <textarea class="form-control" name="sobre_voce" id="sobre_voce" placeholder="Digite aqui"
                    required></textarea>
            </div>

            <!-- Botão de envio do formulário -->
            <div>
                <button class="btn btn-primary" type="submit">Enviar</button>
            </div>
        </form>
        <!-- Fim do formulário -->

    </div>
</body>

</html>

```

Resultado:

<img width="700" height="866" alt="image" src="https://github.com/user-attachments/assets/58fc6dbc-f0ab-4f3f-880f-6d09fd3bab1d" />


