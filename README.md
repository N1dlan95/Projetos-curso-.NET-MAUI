# Repositório para os app criados no curso de .NET MAUI 
Repositório criado com os objetivos de:
1. Praticar o meu conhecimento em git e github;
2. Praticar a comandos do terminal (tudo que possível ser criado no terminal);
3. Guardar os projetos criados;
4. Acompanhar a minha constância nos estudos.

### Esclarecimentos
1. Foi criado apenas uma solução para todos os aplicativos criados;
2. Todos os aplicativos estarão separados por pastas e na ordem que forem criados;

## Passo a passo para a criação(Lembrete meu).
1. Crie a solução em uma pasta
``` powershell
dotnet new sln -n "NomeDaSolução"
```
2. Cria cada projeto(MAUI) separadamente
``` powershell
dotnet new maui -n "NomeDoProjeto"
```
3. Adiciona o projeto a solução
``` powershell
dotnet sln add "NomeDoProjeto/"NomeDoProjeto".csproj
```
Este é o passo crucial! Você precisa "avisar" a solução que esse novo projeto faz parte dela.
**Obs:** O projeto deverá ser manipulado no **Solution Explorer** do Vs Code
### Caso deseje criar direto pelo Visual studio Code
1. 
