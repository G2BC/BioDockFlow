# BioDockFlow

![Docker](https://img.shields.io/badge/Docker-619AFB?style=for-the-badge&logo=docker&logoColor=white) ![Jira](https://img.shields.io/badge/Jira-blue?style=for-the-badge&logo=jira&logoColor=white)

Bem-Vindo! Este é o BioDockFlow, um processo de manutenção para aplicações web de bioinformática baseado em Docker 🚀🐋.
Modelado para atender aplicações heterogêneas. Significa que a arquitetura das aplicações não é uma limitação.

### O que você vai encontrar aqui:
A estrutura de pastas indica as versões passadas, na raiz do projeto encontra-se a versão atual do processo.

BioDockFlow/
├── v1/
├── v2/
├── Documento do processo versão atual
├── Workflow versão atual
└── README.md





### O que é necessario para execução do processo?
1. Siga o [fluxo de trabalho da versão atual](BioDockFlow%20-%20WorkFlow%20-%20v3.png). 

2. Entenda as fases do processo bem como as condições, entradas e saídas de cada atividade através do [documento do processo](/BioDockFlow%20-%20Maintenance%20Process%20-%20v3.pdf)

3. Cadastre o projeto que irá passar pelo processo na ferramenta [Jira](https://www.atlassian.com/br/software/jira)

4. Customize a ferramenta com as fases do processo e com validações nas transições para garantir o fluxo correto das atividades.

5. Customize o cadastro das QMs com campos necessários para o de acordo com a documentação.


### Como avaliar a eficácia do processo?
A métrica de avaliação definida foi a Taxa de Resolução de Questões de Manutenção (TR-QM).

$$
\text{TR-QM} = \frac{(N^\circ \ \text{QM-PA Concluídas} \times 1) + (N^\circ \ \text{QM-PM Concluídas} \times 0.5) + (N^\circ \ \text{QM-PB Concluídas} \times 0.25)}{(Total \ \text{QM-PA} \times 1) + (Total \ \text{QM-PM} \times 0.5) + (Total \ \text{QM-PB} \times 0.25)}
$$

- **QM-PA (Prioridade Alta)**: inclui todas as questões da categoria Docker, com peso atribuído de 1.

- **QM-PM (Prioridade Média)**: abrange questões das categorias Refatoração e Correção de bugs que impedem o uso do sistema, com peso atribuído de 0,5.

- **QM-PB (Prioridade Baixa)**: inclui questões das categorias Refatoração e Correção de bugs que não impedem o uso do sistema, bem como das categorias Mudança de Requisitos, Novos requisitos, Documentação, com peso atribuído de 0,25.

A priorização das QMs é baseada primeiramente no foco do processo conteinerização com Docker e em seguia prover uma versão funcional do sistema com seu(s) caso(s) de uso principal(is).

### Autor
**Pedro Victor Santana Benevides**

**Orientador - Prof. Dr. Alexandre Rafael Lenz**

**Universidade do Estado da Bahia - UNEB**

[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/pedr.vtr/)   [![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:pvsbenevides197@gmail.com)

