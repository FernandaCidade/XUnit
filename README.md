# 🧮 IMC - Cálculo e Classificação com xUnit
Este projeto realiza o cálculo e a classificação do IMC (Índice de Massa Corporal), com testes automatizados utilizando o framework xUnit. Desenvolvido como parte de uma atividade prática do curso de Desenvolvimento com Testes Automatizados no SENAI.

## 🛠 Tecnologias Utilizadas
 - .NET 6 ou superior
 - C#
 - xUnit
 - Visual Studio Code ou Visual Studio
   
## 📁 Estrutura do Projeto
```
atividade_imc_xunit/
├── imc.cs                # Classe principal com lógica de cálculo e classificação do IMC
├── UnitTest1.cs          # Classe de testes automatizados com xUnit
├── atividade_imc_xunit.csproj  # Arquivo de configuração do projeto .NET
```
## 🔣 Funcionalidades
- Cálculo do IMC com base em peso e altura
- Classificação do IMC conforme faixas da OMS
- Testes automatizados para:
  - Verificar o valor calculado do IMC
  - Validar todas as categorias possíveis do IMC
 
## ▶️ Executando o Projeto
1. Abra o terminal Git Bash na pasta do projeto:
```
dotnet --version
```
  Verifique se a versão instalada do .NET é 6.0 ou superior.
  
2. Abra o projeto no VS Code ou Visual Studio: 
```
code .
```
3. Restaure os pacotes do projeto:
```
dotnet restore
```
4. Compile o projeto:
```
dotnet build
```
5. Execute os testes:
```
dotnet test
```


## ✅ Exemplos de Testes
- Verificação do cálculo:
```
Assert.Equal(31.25, i.imc);
```
- Verificação de categorias:
```
Assert.Equal("Obesidade de Grau I", i.categoria);
```
## 📌 Observações
As categorias de IMC estão implementadas conforme os intervalos reconhecidos pela OMS.

- A estrutura com xUnit facilita a escrita de testes organizados e reutilizáveis.
- Pode ser expandido para entrada de dados via console, web ou integração com banco de dados.


