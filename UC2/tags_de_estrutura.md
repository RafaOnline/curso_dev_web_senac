# 📌 Aula 7 - Introdução às Tags de Estrutura

Nessa aula tivemos introdução á estruturação de HTML e também foi prosposto um exercício prático.

## 🧠 Exercícios 

1. Crie uma seção adicional na página que inclua uma lista não ordenada de tópicos que você gostaria de aprender sobre HTML.
2. Adicione estilos personalizados à seção criada, mudando a cor de fundo e o tamanho do texto.
3. Crie um link interno que leva até essa nova seção a partir do topo da página.

Código:

```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Exercíco Aula 7</title>
</head>
<body >
    <div id="secao1" style="justify-items: center; color: white; background-color: orange; padding-top: 10px; text-align: center; height: 300px;">
        <h1 >Tópicos para aprendizagem em <span style="font-family: 'Courier New', Courier, monospace;">HTML</span></h1>
        <ul style="padding: 25px;">
            <li style="border: 1px solid white;">Mídias</li>
            <li style="border: 1px solid white;">Elementos interativos</li>
            <li style="border: 1px solid white;">TAGS</li>
        </ul>
        
        <a style="text-decoration: none; background-color: black; border: 1px solid white; color: white; padding: 15px;" href="#secao1">Ir para seção 1</a>
    </div>
</body>
</html>
```

Resultado:

<img width="940" height="322" alt="image" src="https://github.com/user-attachments/assets/7c7f0fbb-3b63-474e-b40a-0c5c4b7a2049" />

