# GISA (Gestão e Inovação em Saúde) - Receitas Digitais

## &nbsp;&nbsp;&nbsp;&nbsp;Ferramenta de auxílio para o âmbito de saúde pública 🏥  
&nbsp;&nbsp;&nbsp;&nbsp;O projeto **GISA (Gestão e Inovação em Saúde)** tem como objetivo trazer uma maneira de se administrar de gestão em saúde voltado para instituições como a APAE, substituindo processos manuais (Excel, papel, WhatsApp) por uma plataforma unificada com prontuário eletrônico, agendamento inteligente, notificações automáticas e geração de relatórios para fiscalização governamental.

---

## O Problema 🚩

A APAE Sorocaba opera hoje com ferramentas fragmentadas:

| Processo | Ferramenta atual |
|---|---|
| Documentação | Word |
| Agendamento | Excel |
| Comunicação interna | WhatsApp |
| Entrada de pacientes | Site SUS (Central Reguladora de Vagas) |
| Cadastro de pacientes | Papel |

Isso gera perda de informações, baixo controle e muito retrabalho.

---

## A Solução 💡

Sistema web + mobile com:

- Prontuário eletrônico unificado (PTS diário + histórico por especialidade)
- Agendamento inteligente com múltiplas consultas por dia
- Notificações automáticas via WhatsApp (chatbot)
- Relatórios semestrais de evolução clínica (score 1–6)
- Geração de documentos oficiais com papel timbrado
- Matrícula única por paciente

---

## Requisitos de Alto Nível 📋

### Paciente / Responsável 👤
- Solicitar o Cancelar consultas
- Avaliar serviços e atendimentos
- Visualizar histórico de consultas
- Visualizar receitas, atestados e prescrições
- Solicitar renovação de receita médica
- Receber notificações e feedback de evolução clínica

### Profissional de Saúde 🧑‍⚕️
- Receitar, prescrever e atestar digitalmente
- Registrar atendimentos e PTS diário
- Gerar relatório semestral de evolução (score 1 a 6)
- Visualizar histórico unificado do paciente

### APAE (Administração / Recepção) 🚑
- Gerenciar fila de triagem (SUS / Municipal)
- Cadastrar pacientes (Saúde, Educação, Assistência)
- Agendar, remarcar e registrar faltas com atestado
- Gerenciar profissionais (PJ/CLT + CBO)
- Abrir/fechar agenda clínica
- Imprimir documentos oficiais
- Visualizar avaliações dos pacientes
- Cancelar consultas

---

[**Clique aqui para visualizar os Casos de Uso de Alto Nível.**](doc/CasoUso_2.drawio.png)

---
<!--
## Modelo de Negócios 🕴️ 
<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/91b79912-beb5-438a-922a-3717c959e096" />

-->
## Protótipo 🛠️
 
Desenvolvido no **Figma Make** — [Abrir protótipo](https://www.figma.com/make/g27uAIlfrCJjQB4AqNYJr1/Aplicativo-de-Sa%C3%BAde-APAE?node-id=0-1&p=f&fullscreen=1)
 
[Vídeo de apresentação](https://youtu.be/4ec46Yfk3Og) · [Documentação do protótipo](https://github.com/kauanzin222/GISA-Projeto/blob/ff58c548cbd0642145f7287d3cf52fab2241b3b1/doc/Documentar%20o%20Prot%C3%B3tipo%20Parcial.pdf)

## 🖼️ Demonstração das Telas

### 🔐 Painel Administrativo
> Gestão completa de usuários, relatórios e configurações do sistema.
<p align="center">
  <img src="https://github.com/user-attachments/assets/407c2177-4138-46dd-9f9a-5dd3812b6bbf" width="90%">
</p>

---

### 👨‍⚕️ Área do Profissional
> Interface otimizada para consultas, prontuários e agenda.
<p align="center">
  <img src="https://github.com/user-attachments/assets/c1f4ee49-0756-4204-857a-f73659d566d8" width="90%">
</p>

---

### 👤 Portal do Paciente
> Visualização de exames, histórico e agendamentos simplificados.
<p align="center">
  <img src="https://github.com/user-attachments/assets/147db493-9bb5-4e64-a288-eedfc4c5d772" width="90%">
</p>

---
## Tecnologias que serão usadas e seus responsáveis 🖥️
* Expo - <a href="https://github.com/JoseCBJ">**José Carlos**</a>
* Java - <a href="https://github.com/kauanzin222">**Kauã Cardoso**</a>
* Angular - <a href="https://github.com/belenuslugh">**Eduardo Proença**</a>
* AWS Cloud - <a href="https://github.com/kacrr">**Karina Corrêa**</a>
* Banco de dados - <a href="https://github.com/GabrielReis97">**Gabriel dos Reis**</a>
