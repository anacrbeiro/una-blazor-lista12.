Nome: Ana Carolina Ribeiro Dos Santos
Curso: Ciências Da Computação

-----------------------------------------------
Heurísticas de Nielsen aplicadas
- Visibilidade do Status do Sistema; O contador é atualizado em tempo real a cada clique.
- Feedback do Usuário; A barra de progresso e mudança de cor indicam evolução.

-----------------------------------------------
Como executar
No terminal digite:
- dotnet restore 
- dotnet run --launch-profile https

-----------------------------------------------
Explicação Técnica:
O [Parameter] foi utilizado para tornar o componente reutilizável.

Exemplo:

[Parameter]
public int Peso { get; set; }

Assim, cada instância do componente pode ter um valor diferente de incremento.


![Print do terminal rodando o projeto](./.png)
