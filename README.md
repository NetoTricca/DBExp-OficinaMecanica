![image](https://user-images.githubusercontent.com/68438464/190281482-c45e7ae0-3466-4298-8dba-393f8f8f3d25.png)


# DBExp-OficinaMecanica

## Database Experience - Projeto de BD de Oficina Mecânica com MySQL Workbench

## Objetivo:
Criar o esquema conceitual para o contexto de oficina com base na narrativa fornecida

### Narrativa:
- Sistema de controle e gerenciamento de execução de OS em uma oficina mecânica
- Clientes levam veículos à oficina mecânica para serem consertados ou para passarem por revisões  periódicas
- Cada veículo é designado a uma equipe de mecânicos que identifica os serviços a serem executados e preenche uma OS com data de entrega
- A partir da OS, calcula-se o valor de cada serviço, consultando-se uma tabela de referência de mão-de-obra (e peças)
- O valor de cada peça também irá compor a OS (veririar mesma tabela de referẽncia)
- Cliente autoriza a execução dos serviços (status)
- A mesma equipe avalia e executa os serviços
- Os mecânicos possuem código, nome, endereço e especialidade
- Cada OS possui: n°, data de emissão, um valor, status e uma data para conclusão dos trabalhos.
