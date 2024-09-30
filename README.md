# Sistema de Avaliação de Financiamento

Este projeto é um sistema simples em Java que avalia se uma pessoa pode obter um financiamento com base em quatro perguntas. O sistema utiliza a entrada do usuário para determinar se ele atende aos critérios necessários para financiamento.

## Funcionalidades

O programa faz as seguintes perguntas ao usuário:

1. **Tem emprego?** (Responda "sim" ou "não")
2. **Tem empresa?** (Responda "sim" ou "não")
3. **Tem o nome no Serasa?** (Responda "sim" ou "não")
4. **Digite o valor do 'bem' a ser adquirido.** (Ex 20.000)
5. **Digite a porcentagem da entrada "%" ou valor da entrada.** (20%) ou (20.000)
6. **Digite a taxa de juros mensal.**  (Ex: 1.8)
7. **Digite o número de meses para o financiamento.** (Ex 48)

Com base nas respostas, o sistema determina se a pessoa pode financiar ou não, utilizando a seguinte lógica:

- Pode financiar se:
  - O usuário tiver emprego **ou** empresa,
  - **E** não tiver o nome no Serasa,
  - **E** Se tem entrada para o financiamento.
  - **E** Se o usuario aceita o porcentual de juro,
  - **E** Se o valor cobrado estra dentro do que ele quer.

## Como Executar

1. Certifique-se de ter o JDK instalado em seu sistema.
2. Clone este repositório:
```bash
git clone <URL do repositório>
```
3. Navegue até o diretório do projeto:
```bash
cd <diretório do projeto>
```
4 .Compile o programa:
```bash
javac Main.java
```
5 .Execute o programa:
```bash
java Main
```
- Contribuições:
  Sinta-se à vontade para contribuir com melhorias ou correções. Faça um fork deste repositório, faça suas alterações e envie um pull request.
