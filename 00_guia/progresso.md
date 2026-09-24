# Progresso e dificuldades

Use este único registro; não precisa criar um sistema novo de acompanhamento.

## Próxima ação

- [ ] Abrir `01_python_pandas/mainCredit.ipynb`, tentar explicar o código e conferir as variáveis impressas.

## Competências

Marcar somente depois de demonstrar com uma variação. Não marcar por ter visto a aula.

- [ ] Manipular e juntar dados com pandas, conferindo o resultado.
- [ ] Resolver consultas com joins e agregações sem roteiro pronto.
- [ ] Resolver uma consulta com CTE e outra com função de janela.
- [ ] Justificar tratamentos de nulos, duplicatas e valores suspeitos.
- [ ] Produzir gráficos coerentes com a pergunta e escrever conclusões.
- [ ] Explicar amostragem, média/mediana, incerteza e pressupostos.
- [ ] Comparar um modelo simples com baseline em dados reservados.
- [ ] Evitar vazamento e usar validação adequada ao problema.
- [ ] Entregar uma análise própria que execute do início ao fim.
- [ ] Apresentar resultado e limitações em cinco minutos.

## Pendências observadas nos arquivos

Os números de células são os originais: os blocos de revisão foram acrescentados ao final.

| Prioridade | Local | O que investigar | Situação |
|---|---|---|---|
| 1 | `01_python_pandas/mainCredit.ipynb`, 12/14 | Cria `creditos3` mas mostra `creditos`; cria `s2` mas imprime `s` não definido | Aberta |
| 1 | Mesmo notebook, 5 | Saída salva não corresponde ao `head()` atual | Reexecutar |
| 1 | `04_estatistica/amostragem_sistematica_.ipynb`, 3–6 | Início 10 gera índice 150; zero nunca entra. Corrigir origem e acesso, não só trocar loc por iloc | Aberta |
| 1 | `03_preparacao_visualizacao/limpeza/main.ipynb`, 17/37 | Idade acima de cem não é impossível; numérico não implica imputar mediana | Revisar raciocínio |
| 1 | Mesmo notebook, 43/45–48 | Justificar estados trocados por RS; `2 * desvio` não é distância de dois desvios da média | Revisar raciocínio |
| 2 | `04_estatistica/amostragem_simples_.ipynb`, 4–8 | p=0.7/0.3 não são probabilidades iguais; tamanho não é fixo; seleção mantém zeros | Aberta |
| 2 | `04_estatistica/centralidade_variabilidade_.ipynb` | Explicar média de ~181 mil versus mediana de 40 mil | Sem conclusão |
| 2 | `04_estatistica/testes_de_normalidade_.ipynb` | Registrar H0/nível/decisão; não rejeitar não comprova normalidade | A aprofundar |
| 2 | `03_preparacao_visualizacao/graficos/boxplot.ipynb`, 5 | Caixas sobrepostas na mesma posição | Aberta |
| 2 | `03_preparacao_visualizacao/graficos/10.dispersao_seaborn_ATUALIZADO.ipynb`, 6 | Painel Quebec recebe base inteira, misturando grupos | Aberta |
| 2 | `05_modelagem/regressao/regressao_linear_simples.ipynb` | Contém apenas imports: completar problema, ajuste, avaliação e conclusão | Iniciado |
| 3 | `06_series_temporais/previsoes_arima.ipynb`, 2–3/7/9 | Instalação falhou em saída antiga; seleção vê toda a série antes do teste; falta baseline | Aberta; após base |

Os dois caminhos CSV do notebook seaborn foram corrigidos na reorganização. A correção de caminhos não resolve a mistura de grupos no gráfico. Demais saídas antigas continuam como registro e devem ser conferidas em uma execução limpa.

## Registro de uma sessão

Copie apenas quando útil:

| Data | Tentei fazer | Onde travei / causa | O que mudei | Como conferi | Próxima tentativa sem solução |
|---|---|---|---|---|---|
| | | | | | |

## Definição de exercício concluído

- [ ] Sei dizer qual pergunta respondi.
- [ ] Reiniciei o kernel e executei tudo na ordem.
- [ ] Conferi resultado, quantidade de linhas, chaves e gráfico conforme o caso.
- [ ] Justifiquei as decisões relevantes e escrevi uma limitação.
- [ ] Fiz uma variação sem seguir a solução completa.

Exercícios de sintaxe podem ter verificação curta; análises e modelos precisam de interpretação.
