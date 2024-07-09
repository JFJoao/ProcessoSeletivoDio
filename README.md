# Projeto de Processo Seletivo

Este projeto Java simula um processo seletivo onde uma lista de candidatos é contatada para possíveis oportunidades de emprego. O projeto inclui funcionalidades para contato com candidatos, análise de pretensões salariais e seleção final de candidatos.

## Funcionalidades

1. **Contato com Candidatos**
   - Tenta entrar em contato com cada candidato até três vezes.
   - Registra se o contato foi bem-sucedido ou não.

2. **Impressão de Candidatos Selecionados**
   - Imprime uma lista dos candidatos selecionados, informando o índice de cada um.

3. **Seleção de Candidatos**
   - Seleciona candidatos baseados em suas pretensões salariais.
   - Compara a pretensão salarial com um salário base definido.

4. **Análise de Candidatos**
   - Analisa se um candidato deve ser contatado com base em sua pretensão salarial comparada ao salário base.

## Estrutura do Código

### Classe `ProcessoSeletivo`

- **Método `main`**
  - Inicializa a lista de candidatos e chama o método `entrandoEmContato` para cada candidato.

- **Método `entrandoEmContato`**
  - Tenta entrar em contato com um candidato até três vezes.
  - Utiliza o método auxiliar `atender` para simular se o candidato atendeu ou não.

- **Método `atender`**
  - Simula a resposta do candidato de forma aleatória.

- **Método `imprimirSelecionados`**
  - Imprime uma lista de candidatos selecionados utilizando dois tipos de laço: `for` e `for-each`.

- **Método `selecaoCanditatos`**
  - Seleciona candidatos com base em suas pretensões salariais.
  - Utiliza o método `valorPretendido` para obter a pretensão salarial de forma aleatória.

- **Método `valorPretendido`**
  - Gera uma pretensão salarial aleatória entre 1800 e 2200.

- **Método `analisarCanditato`**
  - Analisa a pretensão salarial de um candidato e decide se deve contatá-lo, fazer uma contra-proposta ou aguardar outros candidatos.

## Exemplo de Uso

O programa principal (`main`) inicializa uma lista de candidatos e tenta entrar em contato com cada um deles. Ele imprime se o contato foi realizado com sucesso ou se o número máximo de tentativas foi atingido. Adicionalmente, o programa pode imprimir a lista de candidatos selecionados e analisar as pretensões salariais para a seleção final.


