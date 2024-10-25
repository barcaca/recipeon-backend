# Recipeon Backend

Este é o backend do Recipeon, um projeto focado em fornecer uma API para exibição de receitas. Utiliza `json-server` para simular um servidor RESTful, permitindo operações de criação, leitura, atualização e exclusão (CRUD) em receitas.

## Indice

- 🛠️ [Tecnologias](#-tecnologias)
- 🏗️ [Funcionalidades](#-funcionalidades)
- 🖼️ [Exemplo](#-exemplo)
- 🔗 [Links](#-links)
- 👤 [Autor](#-autor)

## 🛠️ Tecnologias

![json-server](https://img.shields.io/badge/json--server-%2306B6D4?style=for-the-badge&logo=json&logoColor=fff)

![Vercel](https://img.shields.io/badge/Vercel-%23000000?style=for-the-badge&logo=vercel&logoColor=white)

## 🏗️ Funcionalidades

- API RESTful simulada com `json-server`.
- CRUD completo para gerenciamento de receitas.

## 🖼️ Exemplo

```json
{
  "receitas": [
    {
      "id": 1,
      "nome": "Panquecas Simples",
      "imagem": "https://moinhoglobo.com.br/wp-content/uploads/2018/09/24-panqueca.jpg",
      "serve": 4,
      "tempo": "20 minutos",
      "categoria": ["breakfast"],
      "descricao": "Panquecas fofas e rápidas para um breakfast delicioso.",
      "ingredientes": [
        { "quantidade": "1", "unidade": "xícara", "nome": "Farinha de Trigo" },
        { "quantidade": "1", "unidade": "colher de sopa", "nome": "Açúcar" },
        { "quantidade": "1", "unidade": "colher de chá", "nome": "Fermento em pó" },
        { "quantidade": "1", "unidade": "unidade", "nome": "Ovo" },
        { "quantidade": "1", "unidade": "xícara", "nome": "Leite" },
        { "quantidade": "2", "unidade": "colheres de sopa", "nome": "Manteiga derretida" }
      ],
      "passos": [
        "Misture os ingredientes secos.",
        "Adicione o ovo, o leite e a manteiga derretida. Misture bem.",
        "Aqueça uma frigideira e despeje porções da massa.",
        "Cozinhe até surgirem bolhas e vire as panquecas. Sirva quente."
      ]
    }
  ]
}
```

## 🔗 Links

- [Live Site URL](https://recipeon-backend.vercel.app)

## 👤 Autor

- [@barcaca](https://www.github.com/barcaca)
