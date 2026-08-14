# 📚 Anotações - Inteligência Artificial Aplicada à Saúde

---

# 📅 Semana 1

## Diferença entre Predição e Previsão

- **Previsão:** estimativa de um evento futuro baseada em análise de dados, lógica, modelos matemáticos e estatísticos.
- **Predição:** inferência de um resultado a partir de padrões encontrados nos dados por modelos de Inteligência Artificial e Aprendizado de Máquina.

> **Resumo:** ambos estimam acontecimentos futuros. Na IA, a predição normalmente utiliza modelos treinados com dados.

---

## Sistema de Reconhecimento × Sistema de Apoio à Decisão (SAD)

### Sistema de Reconhecimento

- Identifica padrões em grandes volumes de dados.
- Utiliza algoritmos de aprendizado de máquina e redes neurais.
- Exemplo: reconhecimento de imagens médicas.

### Sistema de Apoio à Decisão (SAD)

- Auxilia profissionais na tomada de decisões.
- Gera recomendações com base em conhecimento especializado e dados analisados.
- O profissional continua responsável pela decisão final.

---

## Sistema de Recomendação × Sistema de Apoio à Decisão

| Sistema de Recomendação | Sistema de Apoio à Decisão (SAD) |
|--------------------------|-----------------------------------|
| Recomenda itens, conteúdos ou ações com base no perfil e histórico do usuário. | Auxilia especialistas na tomada de decisões utilizando conhecimento e análise de dados. |
| Voltado ao usuário final. | Voltado ao apoio de profissionais. |

---

# 📅 Semana 2

## Predição e Previsão

### Fluxo das técnicas

```text
KDD (Descoberta de Conhecimento em Bases de Dados)
│
└── Data Mining (Mineração de Dados)
    │
    └── Pattern Recognition (Reconhecimento de Padrões)
        │
        ├── Sistemas de Predição
        └── Sistemas de Previsão
```

- Utilizam matemática e estatística.
- Empregam técnicas de Inteligência Artificial para reconhecer padrões.

---

# 🤖 Técnicas de Inteligência Artificial

## Redes Neurais

Utilizadas principalmente para reconhecimento de padrões e aprendizado com grandes volumes de dados.

### Características

- Base de conhecimento formada por amostras de treinamento.
- Reconhecimento de padrões.
- Raciocínio automatizado.
- Aprendizado de Máquina (Machine Learning).

---

## Processamento de Linguagem Natural (PLN)

Permite que computadores compreendam, interpretem e processem a linguagem humana.

### Exemplos

- Chatbots
- Assistentes virtuais
- Tradução automática
- Análise de textos

---

## Sistemas Multiagentes

Conjunto de agentes inteligentes que trabalham de forma cooperativa ou distribuída para resolver problemas.

### Aplicações

- Robótica
- Logística
- Saúde
- Automação

---

# 🏥 Aplicações da IA na Saúde

## Medicina, Odontologia e Psicologia

### Aplicações

- Diagnóstico
- Sistemas de recomendação
- Apoio à decisão

---

## Enfermagem

### Aplicações

- Monitoramento de pacientes
- Sensoriamento
- Automação
- Atuação baseada em sensores

---

## Farmácia, Biomedicina e Química

### Aplicações

- Predição
- Previsão
- Sistemas de recomendação

---

# ⚙️ Operações Realizadas pela IA

## Diagnóstico

Objetivo:

- Reconhecer padrões em grandes volumes de dados.

Tecnologias:

- Redes neurais
- Aprendizado de máquina
- Reconhecimento de padrões

---

## Monitoramento e Sensoriamento

Objetivo:

- Acompanhar pacientes ou processos em tempo real.

Tecnologias:

- Sensores
- Automação
- Sistemas inteligentes

---

## Predição e Previsão

Objetivo:

- Estimar eventos futuros utilizando dados históricos.

Tecnologias:

- Reconhecimento de padrões
- Mineração de dados
- Algoritmos de IA

---

## Recomendação

Objetivo:

- Sugerir ações ou tratamentos com base nos resultados obtidos por sistemas de predição e previsão.

Exemplos:

- Recomendações médicas.
- Sugestão de medicamentos.
- Apoio ao diagnóstico.

---

# 📝 Conceitos Importantes

## Sistema de Apoio à Decisão (SAD)

- Auxilia especialistas na tomada de decisões.
- Não substitui o profissional.
- Baseia-se em conhecimento, regras e análise de dados.

---

## Sistema de Recomendação

- Sugere opções ao usuário.
- Utiliza histórico, preferências e padrões encontrados nos dados.
- Muito utilizado em plataformas digitais e também na área da saúde.

---

# 📅 Semana 3

## Modelos Pré-Treinados

Modelos pré-treinados são modelos de Inteligência Artificial que já passaram por uma etapa de treinamento utilizando uma grande quantidade de dados.

Na teoria de **Redes Neurais Artificiais (RNA)**, o treinamento envolve o uso de amostras para realizar ajustes nos pesos da rede até que o modelo consiga reconhecer os padrões desejados.

---

## Treinamento de um Modelo

Para realizar o treinamento, é necessário definir:

- **Regra de negócio:** define quais atributos e informações serão avaliados.
- **Base de dados:** fonte das amostras utilizadas no treinamento.
- **Preparação dos dados:** organização e padronização dos dados antes do treinamento.
- **Tipo de problema:** definir se o objetivo é realizar **predição** ou **previsão**.

---

## Base de Dados

Os dados utilizados para treinamento podem ser obtidos de diferentes fontes:

- Bancos de dados (BD)
- Arquivos CSV
- Outras fontes de dados

### ETL

O processo de **ETL (Extração, Transformação e Carga)** é utilizado para preparar os dados antes de serem utilizados pelo modelo.

```text
ETL
│
├── Extração
│   └── Obtenção dos dados
│
├── Transformação
│   └── Limpeza e padronização
│
└── Carga
    └── Disponibilização dos dados

# 📌 Resumo Geral

```text
Inteligência Artificial
│
├── Redes Neurais
│   ├── Base de treinamento
│   ├── Reconhecimento de padrões
│   ├── Aprendizado de Máquina
│   └── Raciocínio automatizado
│
├── Processamento de Linguagem Natural (PLN)
│
└── Sistemas Multiagentes

Aplicações na Saúde
│
├── Medicina / Odontologia / Psicologia
│   ├── Diagnóstico
│   └── Recomendação
│
├── Enfermagem
│   ├── Monitoramento
│   ├── Sensoriamento
│   └── Automação
│
└── Farmácia / Biomedicina / Química
    ├── Predição
    ├── Previsão
    └── Recomendação
```
