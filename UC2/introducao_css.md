# 🧠 Aula 10 - Introdução ao CSS 🎨

## 🎯 Objetivos da Aula

Ao final dessa aula, você será capaz de:

* Entender o que é o CSS e sua função no desenvolvimento web;
* Diferenciar **Inline**, **Interno** e **Externo**;
* Utilizar **seletores**, **classes** e **IDs**;
* Aplicar as principais **propriedades básicas** do CSS.

---

## 1️⃣ O que é CSS?

CSS (Cascading Style Sheets) é a linguagem usada para **estilizar páginas HTML** — ou seja, definir cores, tamanhos, fontes, espaçamentos, alinhamentos, etc.

---

## 5️⃣ Mini Desafio 💪

Crie uma página `index.html` e um arquivo `style.css`.

* No HTML, coloque:

  * Um título (`h1`)
  * Um parágrafo (`p`)
  * Um botão (`button`)

* No CSS:

  * Faça o `h1` azul e centralizado;
  * Faça o parágrafo cinza e com tamanho 18px;
  * Faça o botão com fundo vermelho, texto branco e bordas arredondadas.

---

Código:

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        .titulo {
            text-align: center;
            color: blue;
        }

        .paragrafo {
            color: gray;
            font-size: 18px;
        }

        .botao {
            background: red;
            color: white;
            border-radius: 5px;
        }
    </style>
</head>

<body>
    <h1 class="titulo">Título</h1>

    <p class="paragrafo">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Optio asperiores iste at hic aspernatur ea mollitia eum
        voluptate temporibus! Aliquam ad modi nam ut, distinctio deserunt vero quia laboriosam consectetur.
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Placeat ipsa accusamus, quia maiores aperiam dicta
        officia, impedit, quasi exercitationem ea veritatis assumenda perspiciatis? Necessitatibus minus, nemo sit vero
        vel at?
        Laboriosam dolores repellat assumenda iure inventore possimus magni suscipit officiis obcaecati maxime saepe
        consequatur eum consequuntur, quod et necessitatibus quas nihil sint perferendis numquam, nobis autem ex, quam
        expedita. Vero?
    </p>

    <button class="botao">Clique aqui</button>

</body>

</html>
```

Resultado:

<img width="952" height="251" alt="image" src="https://github.com/user-attachments/assets/3a2868f4-2f89-402c-9537-d81e3302bb9a" />


