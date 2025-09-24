# 🧩 Aula 2 – Levantamento de Requisitos e Protótipos

## 🎯 Objetivos da Aula

- Compreender profundamente a diferença entre requisitos funcionais e não funcionais
- Aprender a transformar necessidades do usuário em histórias bem estruturadas
- Desenvolver habilidades para criar protótipos que facilitem o desenvolvimento
- Estabelecer uma base sólida para o planejamento do projeto

## Parte 1 - Requisitos
O levantamento de requisitos foi feito com base no projeto da aula 1
(https://github.com/RafaQATester/cursodevwebsenac/blob/main/UC1/aula_planejamento_projeto.md)

**Requisitos Funcionais:**

| Tipo | Categoria | Exemplo | Por que é importante? | Complexidade |
|:----:|:---------:|:-------:|:--------------------------:|:---------------------:|
| **RF001** | Atendimento | "Sistema deve permitir escolher o modo de atendimento com IA ou acesso direto ao catálogo" | Facilita o modo de atendimento | Alta |
| **RF002** | Entrega | "Sistema deve permitir escolher a forma de entrega ou retirada" | Permite ser felxivel o modo de retirada do produto | Média |
| **RF003** | Produto | "Sistema deve sugerir produtos que combinam no uso" | Melhora a descoberta | Média |
| **RF004** | Carrinho | "Sistema deve permitir o usuário salvar seus produtos favoritos" | Aumenta fidelidade dos clientes | Média |
| **RF005** | Assinatura | "Sistema deve permitir o usuário escolher entrega mensal de produtos" | Mais compras do mesmo usuário | Baixa |

**Requisitos Não Funcionais:**

| Tipo | Categoria | Exemplo | Por que é importante? | Complexidade |
|:----:|:---------:|:-------:|:--------------------------:|:---------------------:|
| **RNF001** | Atendimento | "O atendimento humanizado com a IA deve saber o histórico de atendimento de cada cliente" | Facilita o modo de atendimento | Alta |
| **RNF002** | Desempenho | "Após 3 minutos sem interação com a IA o sistema encerra o antendimento" | Melhora o desempenho do site | Média |
| **RNF003** | Produto | "Itens indisponiveis não são exibidos" | Evita erros nas compras | Alta |

## Parte 2 - Histórias de Usuário


```
Como Cliente idoso, 
quero atendimento humanizado
para ter mais facilidade nas compras online

Critérios de Aceitação:

- Dado que estou no chat com atendimento IA, quando solicitar um item por escrito, então a IA deve listar produtos disponíveis
- Os itens serão exibidos na tela com valores e botão de compra
- Pode ser possível adicionar quantidade e maneira de entrega do produto

```

```
Como Idoso que tem dificuldade com tecnologia, 
quero ajuda de um agente IA na finalização de pagamento
para entender claramento cada etapa de pagamento sem gerar erros ou frustação para o cliente

Critérios de Aceitação:

- Dado que o usuário escolheu o método de entrega, quando adicionar no carrinho para compra o produto, então
  o agente IA auxilia no pagamento
- IA deve monitorar as ações do usuário e deve oferer a ajuda quando for concluir uma compra.
- O sistema deve deixar claro quando o pagamento for concluido e a maneira de entrega escolhida
- O usuário pode alterar alguma opção do pedido antes de concluir
```

```
Como Idoso com dificuldade de encontrar um produto, 
quero produtos separardos por categora, nome, tipo de pet, tamanho e com maximo de detalhes para fácil busca do produto
para encontrar qualquer produto sem confusão ou dificuldade

Critérios de Aceitação:

- Dado que estja na página inicial, quando filtrar produtos, então deve ser encontrado o que deseja comprar
- Produtos devem ter detalhes para qual Pet é destinado o tipo de produto
- Letras dos titulos do produto são maiores doque o normal para melhor visualização
- Deve ser de forma clara e destacado o botão de compra 
```

## Parte 3 - Prototipagem

Realizei uma prototipagem de baixa fidelide (Lo-fi) para inicio de projeto

<img width="1360" height="627" alt="image" src="https://github.com/user-attachments/assets/59902b89-87c8-47fb-a919-e7c7b846f4b9" />

