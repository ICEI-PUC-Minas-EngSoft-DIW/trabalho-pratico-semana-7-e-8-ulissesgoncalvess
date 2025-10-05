# Trabalho Prático 05 - Semanas 7 e 8

**Páginas de detalhes dinâmicas**

Nessa etapa, vamos evoluir o trabalho anterior, acrescentando a página de detalhes, conforme o  projeto escolhido. Imagine que a página principal (home-page) mostre um visão dos vários itens que existem no seu site. Ao clicar em um item, você é direcionado pra a página de detalhes. A página de detalhe vai mostrar todas as informações sobre o item do seu projeto. seja esse item uma notícia, filme, receita, lugar turístico ou evento.

Leia o enunciado completo no Canvas. 

**IMPORTANTE:** Assim como informado anteriormente, capriche na etapa pois você vai precisar dessa parte para as próximas semanas. 

**IMPORTANTE:** Você deve trabalhar e alterar apenas arquivos dentro da pasta **`public`,** mantendo os arquivos **`index.html`**, **`styles.css`** e **`app.js`** com estes nomes, conforme enunciado. Deixe todos os demais arquivos e pastas desse repositório inalterados. **PRESTE MUITA ATENÇÃO NISSO.**

## Informações Gerais

- Nome:Ulisses Miguel de Freitas Gonçalves
- Matricula:901839
- Proposta de projeto escolhida:A proposta escolhida foi “Lugares e Experiências”, com foco na cidade de Capitólio MG, conhecida como um dos principais destinos turísticos de Minas gerais
- Breve descrição sobre seu projeto: Irei criar um site informativo da cidade de Capitólio MG, nde mostra aluguéis de casa, eventos na cidade, alugéis de lancha, melhores preços e etc. A ideia central é criar uma home page interativa e informativa, que apresente as principais atrações, passeios e experiências disponíveis na região, servindo como um guia rápido para visitantes. A home page será organizada com uma estrutura semântica e visual agradável, contendo: Banner de destaque com chamada principal para explorar Capitólio. Seção com as principais atrações turísticas (ex.: Cânions de Furnas, Mirante dos Cânions, Cachoeiras), cada uma acompanhada de imagem título, descrição e link para mais detalhes. Formulário para inscrição em uma lista de informações e novidades. Rodapé com informações básicas sobre o site e contatos.

## Print da Home-Page

<<  COLOQUE A IMAGEM AQUI >>

## Print da página de detalhes do item

<<  COLOQUE A IMAGEM AQUI >>

## Cole aqui abaixo a estrutura JSON utilizada no app.js

```javascript
const dados = [
  {
    "id": 1,
    "titulo": "Prefeitura Lança Plano de Mobilidade Urbana",
    "descricao": "Novo plano do transporte público.",
    "conteudo": "A Prefeitura apresentou nesta segunda-feira um novo plano de mobilidade urbana.",
    "categoria": "Cidades",
    "autor": "Joana Ribeiro",
    "data": "2025-03-30",
    "imagem": "img/mobilidade.jpg"
  }
]
```