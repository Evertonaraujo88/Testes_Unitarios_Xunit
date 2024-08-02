# Testes Unitários com xUnit

Este repositório contém projetos de exemplo para a criação de testes unitários em C# utilizando o framework xUnit.

## Projetos

### 1. ValidacaoEmail
Este projeto implementa testes unitários para validação de endereços de e-mail.

### 2. ConversaoTemperatura
Este projeto implementa testes unitários para funções de conversão de temperatura.

### 3. ControleInventario
Este projeto implementa testes unitários para funções de controle de inventário.

## Ferramentas e Frameworks Utilizados

- **.NET Core**: Plataforma de desenvolvimento para construir aplicativos multiplataforma.
- **xUnit**: Framework para criação de testes unitários em C#.
- **Moq**: Biblioteca para criar objetos simulados para testes unitários.
- **FluentAssertions**: Biblioteca para aumentar a legibilidade e fluência das asserções nos testes.

## Dependências

Cada projeto neste repositório utiliza as seguintes dependências:

### ValidacaoEmail

```xml
<PackageReference Include="xunit" Version="2.4.1" />
<PackageReference Include="xunit.runner.visualstudio" Version="2.4.3" />
<PackageReference Include="Moq" Version="4.16.1" />
<PackageReference Include="FluentAssertions" Version="6.1.0" />
````

### ConversaoTemperatura

```xml
<PackageReference Include="xunit" Version="2.4.1" />
<PackageReference Include="xunit.runner.visualstudio" Version="2.4.3" />
<PackageReference Include="Moq" Version="4.16.1" />
<PackageReference Include="FluentAssertions" Version="6.1.0" />
````

### ControleInventario

```xml
<PackageReference Include="xunit" Version="2.4.1" />
<PackageReference Include="xunit.runner.visualstudio" Version="2.4.3" />
<PackageReference Include="Moq" Version="4.16.1" />
<PackageReference Include="FluentAssertions" Version="6.1.0" />
````

Como Executar os Testes
Clone o repositório:

````sh
git clone https://github.com/Evertonaraujo88/Testes_Unitarios_Xunit.git
````
Navegue até a pasta do projeto desejado, por exemplo:
````sh
cd Testes_Unitarios_Xunit/ValidacaoEmail
````

Restaure as dependências:
````sh
dotnet restore
````
Execute os testes:
````sh
dotnet test
````

## Contribuições
Contribuições são bem-vindas! Sinta-se à vontade para abrir issues e pull requests.

## Licença
Este projeto está licenciado sob a licença MIT. Consulte o arquivo LICENSE para mais detalhes.

