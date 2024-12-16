# Análise de Dados: análise de transações de cartão de crédito

## Descrição
Este projeto realiza uma análise detalhada de dados relacionados a **clientes** e **transações**, com o objetivo de identificar padrões, realizar limpeza de dados e extrair insights úteis para a tomada de decisão. As técnicas utilizadas incluem visualização de dados e estatísticas descritivas, com suporte de ferramentas como `pandas`, `matplotlib` e `seaborn`.

## Demonstração
Demonstração de dois exemplos de gráficos gerados durante a análise dos dados, facilitando a visualização dos resultados obtidos

- Gráfico representando o número de transações por sexo por estebelecimento:
![image](https://github.com/user-attachments/assets/ff1eef0a-59ee-425b-94a7-b14777cf74a6)

- Gráfico representando o ticket médio por estabelecimento:
![image](https://github.com/user-attachments/assets/40a1fe95-46b3-4dc3-848e-b8f7ce48877e)

## Tabela de Conteúdos
1. [Descrição](#descrição)
2. [Instalação](#instalação)
3. [Uso](#uso)
4. [Metodologia](#metodologia)
5. [Resultados](#resultados)
6. [Contribuindo](#contribuindo)
7. [Licença](#licença)

## Instalação

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/analise-transacoes-de-cartoes.git
   ```
2. Instale as dependências necessárias:
   ```bash
   pip install -r requirements.txt
   ```
3. Certifique-se de que as tabelas **base_clientes.csv** e **base_transacoes.csv** estejam no diretório principal do projeto.

## Uso

Para executar o projeto, basta abrir o notebook e executar as células:

```bash
jupyter notebook desafio_match.ipynb
```

Se preferir executar o código diretamente, rode:

```bash
python script_principal.py
```

## Metodologia

1. **Importação de Dados**:
   - Carregamento de bases de clientes e transações.
2. **Limpeza de Dados**:
   - Tratamento de valores ausentes e inconsistências.
3. **Exploração de Dados**:
   - Análise inicial através de visualizações.
4. **Insights**:
   - Identificação de padrões relevantes nos dados.

## Resultados
Principais insights e resultados obtidos com esta análise:

- 621 clientes na base de dados, sendo 67,7% da região Sudeste, 15,3% da região Sul, 8,7% na região Centro-Oeste e 8,4% na região Norte do país.
- Estabelecimentos com ticket médi maior, podem gerar mais receita mesmo com um número menor de vendas.
- Clientes do sexo feminino tendem a ter melhores salários dentro de seu próprio grupo de gênero.
- Com os dados analisados, não foi possível concluir e afirmar se há ou não interferência no comportamento de compras com base no gênero do cliente. Seria necessário levar em consideração alguns fatores como diferença do número de homens e mulheres na amostra, distribuição de faixa salarial e contexto geral dos dados fornecidos.

## Contribuindo

Contribuições são bem-vindas! Siga os passos abaixo para colaborar:

1. Faça um fork do repositório.
2. Crie um branch para sua feature:
   ```bash
   git checkout -b minha-feature
   ```
3. Envie um pull request.

## Licença

Este projeto está licenciado sob a Licença MIT. Consulte o arquivo `LICENSE` para mais detalhes.

