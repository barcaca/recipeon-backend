
# Recipeon Backend
Este é o backend do Recipeon, que usa o JSON Server para fornecer uma API de receitas simples e rápida. Está hospedado no Vercel, acessível no link [recipeon-backend.vercel.app/api/receitas](https://recipeon-backend.vercel.app/api/receitas) .

## Endpoints
Abaixo estão os endpoints principais disponíveis:

- GET /api/receitas: Retorna uma lista de todas as receitas.
- GET /api/receitas/{id}: Retorna uma receita específica com base no id.
- POST /api/receitas: Adiciona uma nova receita ao banco de dados.
- PUT /api/receitas/{id}: Atualiza uma receita existente.
- DELETE /api/receitas/{id}: Exclui uma receita.
## Estrutura da Receita

```json
{
  "id": "Number",
  "nome": "String",
  "imagem": "String (URL)",
  "serve": "Number",
  "tempo": "Number",
  "categoria": ["String"],
  "descricao": "String",
  "ingredientes": [
    {
      "quantidade": "String",
      "unidade": "String",
      "nome": "String"
    }
  ],
  "passos": ["String"]
}
```

## Exemplo de Receita

```json
{
  "id": 1,
  "nome": "Frango ao Curry",
  "imagem": "https://example.com/frango-curry.jpg",
  "serve": 4,
  "tempo": 40,
  "categoria": ["Jantar"],
  "descricao": "Frango cozido em um molho cremoso de curry, servido com arroz.",
  "ingredientes": [
    { "quantidade": "500", "unidade": "gramas", "nome": "Peito de frango em cubos" },
    { "quantidade": "1", "unidade": "unidade", "nome": "Cebola picada" }
  ],
  "passos": [
    "Aqueça o óleo em uma panela e refogue a cebola.",
    "Adicione o frango e cozinhe até dourar."
  ]
}

```

## 👤 Autor

- [@barcaca](https://www.github.com/barcaca)

