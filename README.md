# Análise Bayesiana da Proporção de Hipertensão em Pacientes Diabéticos

Projeto desenvolvido na disciplina ME705 — Inferência Bayesiana, da Universidade Estadual de Campinas (UNICAMP), com o objetivo de estimar a proporção de indivíduos hipertensos entre participantes classificados como diabéticos, utilizando métodos de inferência Bayesiana.

## Objetivo

Estimar a proporção de hipertensão entre indivíduos diabéticos e avaliar a incerteza associada a essa estimativa. O estudo também investiga a influência da escolha da distribuição a priori, avalia a convergência do algoritmo MCMC e realiza análises preditivas.


A base de dados [diabetes.csv](diabetes.csv) foi obtida no [Vanderbilt Biostatistics Datasets](https://hbiostat.org/data/). Os dados são provenientes de uma pesquisa epidemiológica realizada na região central da Virgínia, Estados Unidos, envolvendo indivíduos afro-americanos avaliados quanto à presença de diabetes, obesidade e fatores de risco cardiovascular.
Para o estudo, a amostra analisada foi composta por 60 indivíduos, com hemoglobina glicada (HbA1c) superior a 7,0%, utilizando a pressão arterial sistólica para classificar a presença de hipertensão.

## Metodologia

- Modelo Binomial com distribuição a priori Beta.
  
- Inferência posterior por meio do algoritmo Metropolis-Hastings (MCMC).

- Diagnósticos de convergência e estudo de sensibilidade.

- Teste de hipóteses e análise preditiva.

## Ferramentas e métodos

- **Linguagem:** R

- **Distribuições de probabilidade:** distribuições Beta e Binomial

- **Simulação:** Monte Carlo via cadeias de Markov (MCMC)

- **Algoritmo:** Metropolis-Hastings

- **Visualização:** gráficos de distribuição posterior, trace plots e funções de autocorrelação (ACF)

## Arquivos

- [diabetes.csv](diabetes.csv): base de dados utilizada na análise.
  
- [ME705_TF_original_Parte1.pdf](ME705_TF_original_Parte1.pdf): descrição do problema, dos dados e da metodologia.
  
- [ME705_TrabalhoFinal_Parte2.pdf](ME705_TrabalhoFinal_Parte2.pdf): análise exploratória, inferência posterior, diagnósticos de convergência e análises complementares.
  
## Autores

- Nicole de Barros Silva

- Gustavo Coimbra de Souza Teixeira
