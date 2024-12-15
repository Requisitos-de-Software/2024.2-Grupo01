## Introdução
Os Requisitos Não-Funcionais são essenciais para garantir a qualidade e o sucesso de um sistema de software, influenciando diretamente a experiência do usuário, o desempenho e a conformidade com regulamentos. No entanto, esses requisitos muitas vezes não recebem a devida atenção durante o processo de desenvolvimento. Estudos apontam que os RNFs são frequentemente mal elicitados, especificados e gerenciados, resultando em impactos negativos na satisfação dos stakeholders e na qualidade final do produto ([(CHUNG et al., 2000)](#bibliografia); [LAUESEN, 2002](#lausen)). Além disso, a subjetividade, relatividade e interatividade inerentes aos RNFs tornam sua documentação e análise um desafio adicional [(CHUNG et al., 2000)](#bibliografia).

Para abordar essas dificuldades, o NFR Framework foi proposto como uma abordagem estruturada para modelar e analisar RNFs. Criado por Chung et al. (2000), o framework adota o conceito de softgoal — objetivos que não possuem critérios de satisfação claramente definidos. Cada softgoal representa um requisito não-funcional, como usabilidade, segurança ou desempenho, e é modelado em um grafo de interdependência de softgoals (SIG). Esses grafos permitem visualizar as relações entre os RNFs, destacando como eles podem se apoiar ou entrar em conflito entre si.

O Softgoal Interdependency Graph (SIG) pode ser de três formas no NFR Framework, como mostra a figura 1, além de possuir um tipo (determinado NFR) e um ou mais tópicos (assunto relacionado ao NFR). 

- **Softgoals NFR**: representam os Requisitos Não-Funcionais do sistema. Eles podem estar interconectados, organizados em catálogos, e dispostos de maneira hierárquica durante o desenvolvimento do projeto, ajudando a estruturar os objetivos de qualidade do sistema [(CHUNG et al., 2000)](#bibliografia).

- **Softgoals de Operacionalização**: são as soluções práticas para atender aos softgoals NFR ou a outros softgoals de operacionalização. Essas soluções incluem definições de operações, processos, estruturas de dados e restrições do sistema, permitindo que os objetivos de qualidade sejam implementados de forma eficaz no sistema em desenvolvimento [(CHUNG et al., 2000)](#bibliografia).
 
- **Softgoals de Afirmação**: refletem as características específicas do domínio, como prioridades ou carga de trabalho, e ajudam no processo de decisão. Esses softgoals justificam as escolhas feitas durante o refinamento, priorização e seleção de componentes do sistema. Eles fornecem suporte para revisão, ajustes e rastreabilidade das decisões de desenvolvimento [(CHUNG et al., 2000)](#bibliografia).

<center><p><b>Figura 1:</b> Tipos de Softgoals</p></center>  
<center><img src="../../../assets/images/NFR1.png" alt="Descrição da imagem" width="600" style="border: 1px solid"/></center>  
<p align="center"><b>Fonte:</b> <a href="#bibliografia">(CHUNG et al., 2000)</a></p>  

## Objetivo  
O objetivo deste trabalho é construir um artefato baseado no NFR Framework que permita a identificação, representação e avaliação dos requisitos não-funcionais para o aplicativo Bluesky. Especificamente, buscamos:

1.	Mapear os requisitos não-funcionais relevantes para o Bluesky.

2.	Estruturar esses requisitos em um grafo de interdependência de softgoals (SIG).

3.	Fornecer diretrizes para análise e tomada de decisão durante o desenvolvimento do aplicativo.

4.	Validar o artefato proposto por meio de revisão e aprovação dos stakeholders envolvidos.

## Metodologia  
Para uma abordagem completa, dividimos a metodologia em algimas fases, sendo elas:

- **Fase 1: Elicitação de Requisitos Não-Funcionais**:  

    A elicitação de requisitos é uma atividade essencial que visa compreender as expectativas dos stakeholders e os atributos de qualidade do sistema. Isso foi realizado no artefato [Requisitos Elicitados](../../PerfilUsuario/Tecnicas/Requisitosel.md/#requisitos-elicitados).

- **Fase 2: Construção da Taxonomia Inicial**:

    De acordo com a abordagem do NFR Framework (Chung et al., 2000), criar uma taxonomia é fundamental para organizar e categorizar os RNFs:
        •	Agrupar os RNFs por categorias como confiabilidade, desempenho, segurança e usabilidade. Utilizaremos o modelo FURPS+ como descrito no artefato [Especificação Suplementar](../../Modelagem/Especificacao.md).

- **Fase 3: Criação de Grafos de Decomposição de Softgoals**:

    Nesta etapa, a taxonomia inicial é transformada em grafos SIG (Softgoal Interdependency Graphs). Vamos decompor cada softgoals em componentes menores.


- **Fase 4: Criação de Cartões de Especificação**:

    Inspirando-se em técnicas de especificação (como as descritas no livro Requirements Engineering Fundamentals) faremos o cartão de especificação para cada decomposição:

    -	Para cada softgoal, criar cartões que detalhem:

    -	Descrição do RNF.

    -	Alternativas de implementação.

    -	Dependências e restrições.

    -	Os cartões também ajudam a capturar os trade-offs entre alternativas e priorizações.

- **Fase 5: Organização da Taxonomia de Softgoals no SIG Final**:

    Após a criação dos grafos de decomposição, a taxonomia é refinada e consolidada:

    -	Hierarquia organizada: Garantir que os softgoals estejam estruturados de forma clara, agrupados por prioridade e dependências.

    -	SIG final: Integrar todos os softgoals, suas contribuições e refinamentos no grafo final, criando uma visão abrangente dos RNFs para o sistema Bluesky.

- **Fase 6: Listagem de Correlações no SIG**:

    Conforme descrito no NFR Framework, cada relação no SIG deve ser analisada e documentada:

    -	Listar as correlações entre os softgoals, indicando as contribuições positivas e negativas.

    -	Identificar conflitos que exigem resoluções e apontar onde há suporte mútuo entre RNFs.

- **Fase 7: Avaliação e Validação**:

    Por fim, validar o artefato construído, considerando os seguintes passos:

    -	Operacionalização e priorização: Propor soluções práticas para atender os softgoals prioritários.

    -	Afirmação de design: Revisar e justificar decisões com base em softgoals de afirmação que documentem os motivos das escolhas realizadas.

    -	Seleção entre alternativas: Comparar diferentes abordagens utilizando critérios de qualidade, custos e impacto para selecionar a melhor solução.

    -	Revisão com stakeholders: Submeter o SIG final para análise dos stakeholders e ajustar conforme o feedback recebido.

## Fase 1: Elicitação de Requisitos Não-Funcionais 

## Fase 2: Construção da Taxonomia Inicial

## Bibliografia  

<a id="bibliografia"></a>  

> 1. CHUNG, L.; NIXON, B. A.; YU, E.; MYLOPOULOS, J. Non-functional requirements in software engineering. Springer Science & Business Media: [s.n.], 2000. v. 5.
<a id="lausen"></a>  

> 2. LAUESEN, S. Software requirements: styles and techniques. Pearson Education: [s.n.], 2002.

> 3. Pohl, Klaus; Rupp, Chris. Requirements Engineering Fundamentals: A Study Guide for the Certified Professional for Requirements Engineering Exam - Foundation Level. Rockynook, 2011.

## :round_pushpin: Histórico de Versão 

<div align="center">
    <table>
        <tr>
            <th>Data</th>
            <th>Versão</th>
            <th>Descrição</th>
            <th>Autor</th>
            <th>Data da Revisão</th>
            <th>Revisor</th>
        </tr>
        <tr>
            <td>15/12</td>
            <td>1.0</td>
            <td>Criação do documento (Introdução, objetivo e metodologia) </td>
            <td><a href="https://github.com/Renatinha28">Renata Quadros</a></td>
            <td>15/12</td>
            <td><a href="https://github.com/erteduarda">Eduarda Tavares</a></td>
        </tr>
    </table>
</div>