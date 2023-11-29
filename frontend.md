Olá!
===================
	
Estamos ansiosos para ver o que você consegue construir. Acreditamos em pessoas e criar coisas incríveis, se você está lendo esse texto é porque você se identifica com isso. Antes de entrar em detalhes sobre seu desafio, temos algumas considerações. 

> **Vá com calma e observe cada detalhe:**

> - Vamos analisar a qualidade do seu código, então **se preocupe em fazer um código limpo e de fácil entendimento**, utilize design patterns quando necessário e evite fazer códigos que só você entende. 
> - Buscamos pessoas com perfil diferenciado, **não se limite ao escopo do projeto**. Se você for além em coisas simples como o teste, com certeza irá além na hora de criar soluções para o mercado.
> - Temos os requisitos mínimos do projeto que precisam ser entregues. Tudo que for adicional, sendo bem feito, será contado. Qualquer dúvida entre em contato com a gente.


O Problema
-------------------

Imagine que um cliente peça para você desenvolver uma aplicação web, responsiva de uma determinada imobiliária chamada Finpass Imóveis. Ele gostaria de ter uma área para listar imóveis, outra para adicionar um novo imóvel e também ver os detalhes de um imóvel selecionado. Como requisito ele quer uma garantia de que os dados vão ser enviados corretamente para o banco de dados. Ele quer que a aplicação tenha um layout agradável e simples e está delegando para você essa atividade. 

Requisitos
-------------------

O gerente de tecnologia tem essas premissas como base:
> - AngularJS - Angular - React - Vue (modularizado)
> - Layout Responsivo
> - SASS ou LESS (modularizado)
> - Tarefas de build automatizadas (Grunt, Gulp, Webpack, etc)
> - Testes unitários (parcialmente)

Instruções
---------------------

O projeto **deve ser entregue em um repositório GIT** com instruções de como rodá-lo (garanta que essas instruções estejam corretas e claras). 

O backend já está pronto, ou seja, os endpoints das APIs estão disponíveis. 
* https://api.sheety.co/20e6e67423392ddd3f7dc9eaf5caed47/api/imovel (GET) e (POST)

Exemplo de requisição POST para cadastro de um imóvel:

```json
{
  "imovel": {
    "titulo": "Apartamento com 2 Quartos à venda, 74m² - Brooklin\n",
    "descricao": "Casa bacana",
    "fotoCapa": "https://resizedimgs.zapimoveis.com.br/fit-in/800x360/named.images.sp/49f05d370fac3373fab5e87107bde961/apartamento-com-2-quartos-a-venda-74m-no-brooklin-sao-paulo.jpg",
    "cep": "",
    "rua": "Rua Nicolau Barreto",
    "bairro": "Brooklin",
    "cidade": "São Paulo",
    "estado": "SP",
    "numero": 614,
    "valorAlguel": "",
    "valorCompra": 1325000,
    "id": 2
  }
}
```

> **Importante:** Ao concluir, envie o link do repositório para o email [ti@finpass.com.br](ti@finpass.com.br) e entraremos em contato assim que possível, obrigado e boa diversão!
