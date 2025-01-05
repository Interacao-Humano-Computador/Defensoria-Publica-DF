# **Análise de Tarefas para o Site da Defensoria Pública do Distrito Federal (DPDF)**

|    Data    | Data Prevista de Revisão | Versão |           Descrição            |                                                                                 Autor                                                                                 |                     Revisor                      |
| :--------: | :----------------------: | :----: | :----------------------------: | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :----------------------------------------------: |
| 01/12/2024 |        02/12/2024        |  1.0   |      Criação do Documento      | [João Victor C. Nobre](https://github.com/Gam13) </br></br>[Karolina Vieira](https://github.com/Karolina91)</br></br>[Paola Nascimento](https://github.com/paolaalim) |   [Lucas Sales](https://github.com/Lux-Sales)    |
| 02/12/2024 |        02/12/2024        |  1.1   | Adição do histórico de versões |                                                              [Lucas Sales](https://github.com/Lux-Sales)                                                              | [João Victor C. Nobre](https://github.com/Gam13) |
| 02/12/2024 |        02/12/2024        |  1.2   |      Adição da tarefa 04       |                                                              [Lucas Sales](https://github.com/Lux-Sales)     
| 28/12/2024 |        03/01/2025        |  1.3   | Modificação Tarefa 01 |                                                              [Karolina Vieira](https://github.com/Karolina91)                                                              | [Paola Nascimento](https://github.com/paolaalim) |
| 03/01/2025 |        03/01/2025        |  1.4   |      Adição da tarefa 05       |                                                              [Paola Nascimento](https://github.com/paolaalim)                                                         | [Karolina Vieira](https://github.com/Karolina91) |


## **Objetivos, Operadores, Métodos e Regras de Seleção (GOMS)**

A metodologia GOMS (Goals, Operators, Methods, and Selection Rules) é usada para detalhar as ações necessárias para concluir tarefas no site da DPDF. Abaixo, apresentamos a análise de tarefas realizadas no site:

---

## **Tarefa 1: Agendamento para uma consulta com um advogado (funcionalidade inexistente no site)**

**Goal 0**: Agendar uma consulta com um advogado no site da Defensoria Pública do Distrito Federal

**Method 1**: Passos para acessar e realizar o agendamento

**Goal 1**: Acessar o site da Defensoria Pública

- **OP 1.1**: Abrir o navegador, digitar www.defensoria.df.gov.br e pressionar Enter.

**Goal 2**: Localizar a área de agendamento de consultas

- **OP 2.1**: Navegar pelo menu principal.
- **OP 2.2**: Identificar e clicar na seção "Agendamento de Consultas".

**Goal 3**: Preencher as informações necessárias para o agendamento

- **OP 3.1**: Inserir as informações pessoais solicitadas (ex.: nome, CPF, telefone, e-mail).
- **OP 3.2**: Selecionar o tipo de atendimento desejado (ex.: assistência jurídica, área cível, etc.).
-**OP 3.3**: Escolher a data e o horário disponíveis para o atendimento.
- **OP 3.4**: Confirmar as informações inseridas e clicar no botão "Agendar".
**Goal 4**: Finalizar o agendamento

- **OP 4.1**: Anotar o número do protocolo ou capturar a tela - de confirmação.
- **OP 4.2**: Verificar o e-mail ou mensagens para confirmar o agendamento e receber instruções adicionais, se aplicável.

---

## **Diagrama HTA – Acompanhar a Resposta de uma Solicitação**

![Solicitação](../assets/images/HTA_agendamento.png)

---
## **Tarefa 2: Utilizar o Chatbot para Assistência**

 **Goal 0:** Utilizar o chatbot para assistência<br/>

 **Method 1:** Interagir com o chatbot para obter assistência<br/>

 **Goal 1:** Iniciar a interação com o chatbot<br/>
- **OP 1.1:** Deslocar o cursor até o ícone do chatbot.<br/>
- **OP 1.2:** Clicar no ícone para abrir a janela de chat.<br/>

 **Goal 2:** Escolher a opção desejada entre as alternativas apresentadas<br/>
- **OP 2.1:** Clicar em uma das opções apresentadas pelo chatbot.<br/>

 **Goal 3:** Navegar pelo chatbot<br/>
- **OP 3.1:** Clicar no botão "Voltar" para retornar ao menu anterior.<br/>
- **OP 3.2:** Clicar no botão "Menu Principal" para voltar às opções iniciais.<br/>

 **Goal 4:** Obter a resposta final<br/>
- **OP 4.1:** Ler as instruções fornecidas ou clicar no link redirecionado.<br/>

---

## **Diagrama HTA – Utilizar o Chatbot**

![HTA Chatbot](../assets/images/HTA-Chatbot.png)

---

## **Tarefa 3: Adquirir e Preencher o Formulário para Voluntariado**

 **Goal 0:** Participar como voluntário na DPDF<br/>

 **Method 1:** Adquirir e preencher o formulário de voluntariado<br/>

 **Goal 1:** Acessar o site<br/>
- **OP 1.1:** Verificar a conexão de internet.<br/>
- **OP 1.2:** Acessar a página principal da DPDF.<br/>

 **Goal 2:** Acessar a área correspondente para voluntariado<br/>
- **OP 2.1:** Navegar até a aba de "Estágios ou Colaboradores".<br/>
- **OP 2.2:** Selecionar "Serviços Voluntários Não Remunerados".<br/>

 **Goal 3:** Consultar os requisitos para o processo<br/>
- **OP 3.1:** Ler os documentos necessários.<br/>
- **OP 3.2:** Recolher os documentos.<br/>

 **Goal 4:** Contatar o gerente de voluntariado<br/>
- **OP 4.1:** Localizar os contatos do gerente na página.<br/>
- **OP 4.2:** Solicitar informações e orientações.<br/>

 **Goal 5:** Preencher os formulários<br/>
 **Method 1:** Assinatura Digital<br/>
- **OP 5.1.1:** Acessar e preencher os formulários online.<br/>
- **OP 5.1.2:** Assinar digitalmente.<br/>

 **Method 2:** Assinatura Física<br/>
- **OP 5.2.1:** Imprimir os formulários.<br/>
- **OP 5.2.2:** Assinar fisicamente.<br/>

**Goal 6:** Concluir o envio<br/>
- **OP 6.1:** Submeter os documentos preenchidos.<br/>
- **OP 6.2:** Aguardar a resposta.<br/>

---
## **Diagrama HTA – Adquirir e Preencher Formulário para Voluntariado**

![HTA Voluntário](../assets/images/Voluntario.drawio.png)

## Tarefa 4: Solicitar atendimento à SUAP 

**Goal 0: Solicitar atendimento à SUAP**
**Method 1:** Solicitar atendimento via internet

**OP 1.1** Acessar o site da defensoria pública <br>
**OP 1.2** Deslocar mouse até a aba “Serviços” <br>
**OP 1.3** Dentro de Serviços, clicar em “Atividade Psicossocial (SUAP)” <br>
**OP 1.4** Rolar a página para baixo, até a seção “Solicite Atendimento  aqui” <br>
**OP 1.5** Clicar em “AQUI” no texto “Acesse AQUI” <br>
**OP 1.6** Preencher formulário e clicar em próximo até chegar a uma  página de revisão dos dados<br>
**OP 1.7** Após finalizar a revisão dos dados, clicar no botão verde  escrito “ENVIAR FORMULÁRIO”<br>


## **Diagrama HTA – Solicitar atendimento à SUAP**

![HTA SUAP](../assets/images/HTA-SUAP.jpg)

---
## **Tarefa 5: Inscrever-se no Programa de Estágio da DPDF**


**Goal 0:** Buscar informações sobre o Programa de Estágio da DPDF e concluir a inscrição<br/>

**Method 1:** Navegar no site da DPDF para encontrar informações e realizar a inscrição<br/>

**Goal 1: Acessar o site da DPDF**<br/>
- **Operator 1.1:** Abrir o navegador no notebook<br/>
- **Operator 1.2:** Digitar o endereço do site da DPDF na barra de endereços<br/>

**Goal 2: Navegar até a seção de estágio**<br/>
- **Operator 2.1:** Procurar pela seção "Estágio Remunerado" no menu  <br/>
- **Operator 2.3:** Clicar na opção "Estágio Remunerado"<br/>

**Goal 3: Procurar informações sobre o processo seletivo**<br/>
- **Operator 3.1:** Ler o conteúdo da página sobre o programa de estágio<br/>
- **Operator 3.2:** Identificar e clicar em links relevantes para informações adicionais<br/>

**Goal 4: Acessar materiais relevantes**<br/>
- **Operator 4.1:** Clicar em links para visualizar portarias e materiais relacionados<br/>
- **Operator 4.2:** Baixar arquivos importantes (ex.: portarias, formulários, leis)<br/>

**Goal 5: Realizar a inscrição no estágio**<br/>
- **Operator 5.1:** Identificar o botão "Inscreva-se" na página do estágio<br/>
- **Operator 5.2:** Clicar no botão para iniciar o processo de inscrição<br/>
- **Operator 5.3:** Preencher os dados pessoais no formulário online<br/>
- **Operator 5.4:** Anexar documentação necessária<br/>
- **Operator 5.5:** Clicar no botão "Enviar Inscrição"<br/>

**Goal 6: Receber confirmação da inscrição**<br/>
- **Operator 6.1:** Verificar a mensagem de sucesso exibida na tela ("Inscrição realizada com sucesso!")<br/>
- **Operator 6.2:** Clicar no botão "Baixar Comprovante" para salvar um recibo da inscrição<br/>

---

## **Diagrama HTA – Inscrever-se no Programa de Estágio da DPDF**

![HTA Estagio](../assets/images/HTA-Estagio.png)

---

## Bibliografia 

[1] BARBOSA, S. et al. Interação Humano-Computador e Experiência do Usuário. [s.l.] Autopublicação - Leanpub, 2021.<br><br>
