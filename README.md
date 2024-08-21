# Distribuição Binomial na Análise da Eficácia de Vacinas

### Visão Geral
Este projeto explora a aplicação da Distribuição Binomial para avaliar a eficácia de uma nova vacina em um cenário **simulado**. O estudo envolve uma amostra de 100 pacientes que receberam a vacina, e a análise foca na quantidade de pacientes que permaneceram não infectados pela doença após um determinado período.

### Contexto do Estudo
Na análise, modelamos o número de pacientes que não foram infectados (indicando a eficácia da vacina) como uma **variável aleatória binomial**. Para o estudo, consideramos:

- **n** (Número de Tentativas): O número de pacientes vacinados, que é 100.
- **p** (Probabilidade de Sucesso): A probabilidade de um paciente vacinado não ser infectado. Supondo que a vacina tem uma eficácia de 95%, então p=0,95.
- **X** (Variável Aleatória): O número de pacientes na amostra que não foram infectados.

A Distribuição Binomial permite calcular a probabilidade de um determinado número de pacientes não serem infectados e estimar intervalos de confiança para a eficácia da vacina.

**Aplicação Prática**
A modelagem binomial é útil para inferir a eficácia da vacina em uma população maior. Com esta análise, é possível estimar a probabilidade de, por exemplo, pelo menos 90% dos pacientes em uma amostra maior também não serem infectados. 
Além disso, a análise pode ser usada para comparar a eficácia desta nova vacina com outras já disponíveis no mercado.

**Cálculos e Resultados**
Para calcular a probabilidade de um certo número de sucessos em uma distribuição binomial, utilizamos a função **binom.pmf (Probability Mass Function) da biblioteca scipy.stats.** No exemplo fornecido, calculamos a probabilidade de exatamente 90 pacientes (de 100) serem não infectados, assumindo uma eficácia da vacina de 95%.

Logo, foi  calculada a probabilidade de exatamente 90 pacientes (de 100) de serem infectados pela doença, assumindo que a eficácia da vacina é de 95%. 
E o resultado obtido da probabilidade de 90 pacientes serem infectados foi: **0.0167.**

Ao calcular a probabilidade de pelo menos 90 pacientes não serem infectados, foi somado as probabilidades para todos os valores de 90 até 100. E o resultado foi 








### Contribuições
Sinta-se à vontade para contribuir com o projeto, adicionar novas funcionalidades ou sugerir melhorias. Se encontrar algum problema ou tiver dúvidas, não hesite em abrir uma issue.

### Licença
Este projeto é licenciado sob a Licença MIT.

