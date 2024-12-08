## Introdução

Este documento apresenta a Especificação Suplementar do projeto, estruturada com base no modelo FURPS+<sup>[1](#ref1)</sup>(Funcionalidade, Usabilidade, Confiabilidade, Desempenho, Suporte e outros aspectos complementares). Essa especificação detalha os requisitos não funcionais e suplementares necessários para o desenvolvimento e operação do sistema.

A aplicação do modelo FURPS+ garante que o sistema atenda não apenas aos requisitos funcionais, mas também a características essenciais de qualidade e critérios de aceitação que suportem sua eficiência, segurança e usabilidade.

## Objetivo
O objetivo deste documento é especificar requisitos suplementares que complementem os requisitos funcionais descritos nos [casos de uso](.../Modelagem/Caso_de_uso.md) e na modelagem de requisitos.

## Metodologia
A elaboração deste documento segue as diretrizes do modelo FURPS+, que organiza os requisitos em seis categorias principais:

1.	Funcionalidade: Complementa os casos de uso com detalhes como regras de negócio e validações.

2.	Usabilidade: Define critérios de design, interface do usuário, acessibilidade e experiência do usuário.

3.	Confiabilidade: Especifica requisitos relacionados à segurança, tolerância a falhas e disponibilidade.

4.	Desempenho: Inclui metas de tempo de resposta, capacidade e escalabilidade.

5.	Suporte: Descreve requisitos relacionados à manutenibilidade, documentação e portabilidade.

6.	(Outros): Aborda critérios adicionais como regulamentações, restrições físicas ou de hardware, e padrões tecnológicos.


## Especificação Suplementar
### Funcionalidades
Os requisitos foram coletados por meio das técinas de elicitação:

1. [Brainstorm](../PerfilUsuario/Tecnicas/Brainstorm.md) 

2. [Introspecção](../PerfilUsuario/Tecnicas/introspeccao.md) 

3. [Observação](../PerfilUsuario/Tecnicas/Observacao.md) 

4. [Questionário](../PerfilUsuario/Tecnicas/Questionario.md) 

Os requisitos elicitados são organizados no artefato [Requisitos elicitados](../PerfilUsuario/Tecnicas/Requisitosel.md) 

### Usabilidade
A usabilidade trata da experiência do usuário ao interagir com o sistema. Foca em tornar a interface intuitiva, fácil de usar e acessível a diferentes tipos de usuários, garantindo que o sistema seja eficiente e agradável. A tabela 2 mostra os requisitos não funcionais que se encaixam em "usabilidade"

<center>
<font size="3"><b>Tabela 2:</b> Usabilidade </font>

| ID | Descrição | Rastreabilidade |
|:-----:|:-----:|:----:|
| RU01 | A interface do usuário deve ser intuitiva e fácil de usar, com opções bem definidas para buscar, salvar e visualizar postagens. O design deve ser centrado no usuário e acessível a diferentes perfis de idade. | RNF5 |
| RU02 | A interface deve ser fácil de entender para usuários frequentes de redes sociais, permitindo que se familiarizem com feeds e listas em até 15 minutos. | RNF10 |
| RU03 | O design do aplicativo deve ter uma aparência agradável e atrativa. | RNF14 |

<font size="3"><b>Autor:</b> <a href="https://github.com/Renatinha28">Renata Quadros</a></font> 
</center>

### Confiabilidade
A confiabilidade aborda a proteção dos dados e a segurança das interações do usuário.A tabela 3 mostra os requisitos não funcionais que se encaixam em "confiabilidade"

<center>
<font size="3"><b>Tabela 3:</b> Confiabilidade</font>

| ID | Descrição | Rastreabilidade |
|:-----:|:-----:|:----:|
| RC01 | Todos os dados sensíveis devem ser protegidos por criptografia, com autenticação segura e proteção contra ataques como SQL Injection e XSS. | RNF4 |
| RC02 | O sistema deve ter alta disponibilidade, operando continuamente com redundância de servidores para evitar interrupções. | RNF6 | 
| RC03 | O sistema deve proteger os usuários de conteúdos nocivos, promovendo um ambiente saudável. | RNF11 |
| RC04 | O sistema deve proteger os dados dos usuários de acordo com a LGPD (Lei Geral de Proteção de Dados).| RNF16 |

<font size="3"><b>Autor:</b> <a href="https://github.com/Renatinha28">Renata Quadros</a></font> 
</center>

### Desempenho
Desempenho está relacionado à eficiência do sistema em termos de tempo de resposta e capacidade de lidar com grandes volumes de dados sem comprometer a experiência do usuário. A tabela 3 mostra os requisitos não funcionais que se encaixam em "desempenho"

<center>
<font size="3"><b>Tabela 4:</b> Desempenho </font>

| ID | Descrição | Rastreabilidade |
|:-----:|:-----:|:----:|
| RD01 | O sistema deve processar buscas e carregar feeds rapidamente, garantindo fluidez mesmo com grandes volumes de dados | RNF2 |
| RD02 | O sistema deve ser escalável, suportando um número crescente de usuários e postagens sem comprometer o desempenho. | RNF3 | 
| RD03 |  Cada ação no aplicativo deve ter um tempo de resposta inferior a 3 segundos. | RNF9 |

<font size="3"><b>Autor:</b> <a href="https://github.com/Renatinha28">Renata Quadros</a></font> 
</center>

### Suporte
O suporte refere-se à capacidade do sistema de ser mantido e atualizado facilmente. Envolve questões como a compatibilidade com diferentes dispositivos, a facilidade de manutenção e a conformidade com normas e regulamentações externas. A tabela 5 mostra os requisitos não funcionais que se encaixam em "suporte"

<center>
<font size="3"><b>Tabela 5:</b> Suporte </font>

| ID | Descrição | Rastreabilidade |
|:-----:|:-----:|:----:|
| RS01 | O sistema deve ser compatível com dispositivos móveis modernos, oferecendo uma interface responsiva e acessível em diferentes tamanhos de tela. | RNF7 | 
| RS02 | O sistema deve ser transparente no uso de dados, permitindo que o usuário acesse os Termos de Serviço e a Política de Privacidade em até 5 cliques.  | RNF12 |
| RS03 | A plataforma deve garantir transparência nos algoritmos de recomendação, explicando claramente como as sugestões são feitas. | RNF15 | 

<font size="3"><b>Autor:</b> <a href="https://github.com/Renatinha28">Renata Quadros</a></font> 
</center>

### Restrições de Design

Restrições de Desing são padrões e boas práticas como interfacem arquitetura limpa, opção para daltonicos etc. A tabela 6 mostra os requisistos não funcionais que se encaixam em "restrições de Desing"

<center>
<font size="3"><b>Tabela 6:</b> Restrições de Desing </font>

| ID | Descrição | Rastreabilidade |
|:-----:|:-----:|:----:|
| RD01 | Deve ser possível personalizar o aplicativo (dark mode, idiomas…). | OB11 | 
| RD02 | O sistema deve ser compatível com dispositivos móveis modernos, oferecendo uma interface responsiva e acessível em diferentes tamanhos de tela. | NIS6 e BT9 | 
| RD03 | O aplicativo deve ter uma aparência agradavél ao usuário. | QT6 | 


<font size="3"><b>Autor:</b> <a href="https://github.com/Jagaima">Davi Nobre</a></font> 
</center>

### Requisitos de implementação

Requisitos de implementação é onde se especifica ou se restringe o código ou a construção do sistema<sup>[2](#ref2)</sup>. 

Segundo o próprio bluesky o desenvelvovimento é feito em react+Python.

Baseando-se no contexto em que vivemos a aplicaçãodeve estar disponível em aplicações android e IOS, especificamente em versões androide 8 e superior, e sistemas IOS 10 em diante. 

Os recursos minímos para a plicação são no mínimo 100mb de armazenamento e 2gb de ram, assim como um processador que suposte as versões dos OS litados acima. 

### Requisitos de interface

Os requisitos da interface referem-se aos requisitos não funcionais que contemplam esse ponto. Os requisitos que cobrem o tópico "Requisitos de interface" estão disponíveis na Tabela 7. 

center>
<font size="3"><b>Tabela 7:</b> Requisitos de Interface </font>

| ID | Descrição | Rastreabilidade |
|:-----:|:-----:|:----:|
| RIN01 | A interface do usuário deve ser intuitiva e fácil de usar, com opções bem definidas para buscar, salvar e visualizar postagens. O design deve ser centrado no usuário e acessível a diferentes perfis de idade.  | NIS4 |
| RIN02 | O aplicativo deve ter interface intuitiva para usuários frequentes de redes sociais, levando até 15min para que se familiarizem com feeds, listas. | NIS10, BT10 | 

<font size="3"><b>Autor:</b> <a href="https://github.com/Jagaima">Davi Nobre</a></font> 
</center>

### Requisitos físicos

OS requisitos físicos elicitados pelo time são colocados nessa tabela 8: 


<center>
<font size="3"><b>Tabela 8:</b> Requisitos Físicos </font>

| ID | Descrição | Rastreabilidade |
|:-----:|:-----:|:----:|
| RF01| O sistema deve ser compatível com dispositivos móveis modernos, oferecendo uma interface responsiva e acessível em diferentes tamanhos de tela. | NIS6 e BT9 | 

<font size="3"><b>Autor:</b> <a href="https://github.com/Jagaima">Davi Nobre</a></font> 
</center>

Onde dispositivos modernos abrangem smartphones e computadores modernos. 

## Referência Bibliografica
> 1. <a id="ref1"></a> FURPS+. QualidadeBR. 10 Jul. 2008. Disponível em: https://qualidadebr.wordpress.com/2008/07/10/furps/#:~:text=FURPS%2B%20%C3%A9%20um%20sistema%20para,Rational%20Unified%20Process%20(RUP)%3A. Acesso em: 01 nov. 2024.
> 2.  <a id="ref2"></a> Artefato: Especificações Suplementares. Centro de Informática - UFPE. Disponível em: <https://www.cin.ufpe.br/~gta/rup-vc/core.base_rup/workproducts/rup_supplementary_specification_F5ACAA22.html> Acessado em 06 de dez. 2024 ás 19:36

## Bibliográfia
> Milene Serrano e Maurício Serrano. Requisitos - Aula 13. 2017. Disponível em: https://aprender3.unb.br/pluginfile.php/2972480/mod_resource/content/1/Requisitos%20-%20Aula%20013a.pdf. Acesso em: 01 nov. 2024.

> 2023.2 Economia DF. Econimia DF, 2023. Disponível em: https://requisitos-de-software.github.io/2023.2-Economia-DF/. Acesso em: 01 dez. 2024.

> Bilheteria Digital, 2023. Disponível em:https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/. Acesso em: 01 dez. 2024.

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
            <td>01/12</td>
            <td>1.0</td>
            <td>Criação do documento e especificação suplementar </td>
            <td><a href="https://github.com/Renatinha28">Renata Quadros</a></td>
            <td>07/12</td>
            <td><a href="https://github.com/Jagaima"> Davi Nobre</a></td>
        </tr>
        <tr>
            <td>06/12</td>
            <td>1.1</td>
            <td> Adição das demais especificações </td>
            <td><a href="https://github.com/Jagaima">Davi Nobre</a></td>
            <td>08/12</td>
            <td><a href="https://github.com/Renatinha28">Renata Quadros</a></td>
        </tr>
    </table>
</div>