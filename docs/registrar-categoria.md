# Categoria


## Exemplo para cadastrar uma nova categoria de produto:

 `POST` - `/cadastro-categoria` - Rota para cadastrar categoria

    {
        "nomeCategoria": "nome", # Nome da categoria do produto
        "descricao": "descrição do produto", # Descricao do produto
        "categoriaProduto": "categoria", # Categoria do produto
    }

## Exemplo para listar categorias dos produtos:

`GET` - `/listar-categoria` - Rota para listar categoria

    {
        "nomeCategoria": "nome",
        "descricao": "descrição do produto",
        "categoriaProduto": "categoria",
    }