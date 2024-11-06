CREATE TABLE _ProdutoTeste (
	Produto_Id INT NOT NULL PRIMARY KEY,
	Produto VARCHAR(255) NOT NULL,
	Preco DECIMAL(10,2) NOT NULL,
	Marca VARCHAR(50) NOT NULL,
	SKU VARCHAR(60) NOT NULL,
	Condicao VARCHAR(50) NOT NULL,
	dtCadastro datetime DEFAULT getdate() NOT NULL,
);

INSERT INTO _ProdutoTeste (
	Produto_Id,
	Produto,
	Preco,
	Marca,
	SKU,
	Condicao,
	dtCadastro
) VALUES (
	1,
	'Microondas',
	150,
	'Eletrolux',
	'2550-XXX',
	'Otimo',
	'06-11-2024'
);

SELECT * FROM _ProdutoTeste
