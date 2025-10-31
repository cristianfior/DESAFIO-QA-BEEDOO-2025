# DESAFIO QA BEEDOO 2025
Repositório criado para a realização do teste relacionado a vaga de Analista de Qualidade de Software Júnior da empresa Beedoo. O objetivo é avaliar a aplicação [Beedoo QA Challenge](https://creative-sherbet-a51eac.netlify.app/), responsável por gerenciamento de cursos, e documentar suas histórias de usuário, regras de negócio, critérios de aceite, cenários e casos de teste e também reportar bugs e sugerir melhorias.
___
## 1. USER STORIES
A minha ideia ao criar as user stories foi partir de uma estória mais abrangente e depois destrinchar conforme as principais funcionalidades que o sistema apresenta. A persona escolhida é um usuário com privilégios de administrador, uma vez que o sistema se trata de um gerenciador de cursos e portanto um usuário comum não poderia ter acesso as funcionalidades. 

![alt text](https://i.imgur.com/1pyJdhd.png "Beedoo QA Tests")

    _EU_, enquanto usuário administrador do sistema  
    _GOSTARIA_, de uma plataforma de cursos  
    _PORQUE_, assim posso gerencia-los  

Regras de negócios
    
    RN1: Possuir no cabeçalho do sistema um H1 com o texto: Beedoo QA Chalenge
    RN2: Possuir no cabeçalho do sistema as opções: LISTAR CURSOS e CADASTRAR CURSO
    RN3: Possuir no corpo do sistema um H4 com o texto: Lista de cursos 

---
Funcionalidade: __CADASTRAR CURSO__
![alt text](https://i.imgur.com/SX5wurU.png "Cadastro de curso")

    EU, enquanto usuário administrador do sistema  
    GOSTARIA, de um formulário de cadastro  
    PORQUE, assim posso inserir os cursos disponíveis no sistema 
    
Regras de negócio

    RN1: Possuir os campos do tipo input alfanumérico com os placeholders: Nome do curso, Descrição do curso, Instrutor e Url da imagem de capa
    RN2: Possuir os campos do tipo data com os placeholders: Data de início e Data de fim
    RN3: Possuir um campo do tipo númerico com o placeholder: Número de vagas
    RN4: Possuir um campo do tipo select com o placeholder: Tipo de curso; e os valores: Presencial e Online
    RN4.1: Caso o valor escolhido seja Presencial, deve existir um campo do tipo input alfanumérico com o placeholder: Endereço
    RN4.2: Caso o valor escolhido seja Online, deve existir um campo do tipo input alfanumérico com o placeholder: Link de inscrição
    RN5: Possuir um botão com o texto: CADASTRAR CURSO; com ação para salvar os dados dos inputs
    RN6: Possuir um alert box com o texto: Curso cadastrado com sucesso!; 
---
Funcionalidade: __LISTAR CURSOS__
![alt text](https://i.imgur.com/OTfT0ug.png "Lista de cursos")

    EU, enquanto usuário administrador do sistema  
    GOSTARIA, de uma tela de listagem  
    PORQUE, assim posso listar todos os cursos disponíveis no sistema  
    
Regras de negócio

    RN1: Possuir um componente div que devolva todos os dados do curso previamente cadastrado
    RN2: Possuir um botão com o texto: EXCLUIR CURSO; e um ícone de lixeira, para cada curso cadastrado
    RN3: Possuir um alert box com o texto: Curso excluído com sucesso!; quando o botão de exclusão é acionado
___
## 2. PLANO DE TESTES
A planilha do plano de testes está dividida em duas conforme funcionalidades do site, respeitando o padrão de page objects. Optei por organiza-la dessa maneira pois fica mais fácil realizar o rastreamento dos cenários e casos e posteriormente para o ligamento com os bugs e defeitos encontrados.
- [ACESSAR PLANILHA DE PLANO DE TESTE](https://docs.google.com/spreadsheets/d/1EFgASfWGtaVmYqr-6rwkX3vOPco-_-GEWh6VKKe9KIY/edit?usp=sharing "PLANO DE TESTES FUNCIONAL - BEEDOO")
___
## 3. RELATÓRIO DE BUGS E MELHORIAS
A planilha está dividida em duas partes, bugs e melhorias. 
Para o relatório de bugs adotei o seguinte modelo: id para identificar o bug, ct relacionado para fazer o lastreamento com a tarefa originadora do bug, título do bug, descrição do bug, passo-a-passo para a reprodução do bug, evidência do bug em imagens, severidade e prioridade que o bug deve ser tratado e sanado. Dessa forma fica objetivo o que está acontecendo, como isso impacta o usuário e o quão urgente e rápido deve ser tratado, além de poder fazer o acompanhamento com a tarefa original.    
Para o relatório de melhorias adotei o modelo: id para identificar a melhoria, título da melhoria, descrição da melhoria, prioridade com que deve ser desenvolvida. Ficou perceptível que, mais do que bugs, a aplicação apresenta muitos problemas de estruturação, principalmente as regras de negócios que deveriam ser revistas.
- [ACESSAR PLANILHA DE BUGS E MELHORIAS](https://docs.google.com/spreadsheets/d/1mjQhCtTCNheW3SaaqDAjgpISgf_3i5BboABPXPf1B70/edit?usp=sharing "RELATÓRIO DE BUGS E MELHORIAS")
___
## 4. LINKS ÚTEIS
__PLANO DE TESTES FUNCIONAL - BEEDOO__    
- [ACESSAR PLANILHA DE PLANO DE TESTE](https://docs.google.com/spreadsheets/d/1EFgASfWGtaVmYqr-6rwkX3vOPco-_-GEWh6VKKe9KIY/edit?usp=sharing "PLANO DE TESTES FUNCIONAL - BEEDOO")

__RELATÓRIO DE BUGS E MELHORIAS - BEEDOO__
- [ACESSAR PLANILHA DE BUGS E MELHORIAS](https://docs.google.com/spreadsheets/d/1mjQhCtTCNheW3SaaqDAjgpISgf_3i5BboABPXPf1B70/edit?usp=sharing "RELATÓRIO DE BUGS E MELHORIAS")

__ARTEFATOS E EVIDÊNCIAS__
- [ACESSAR ARTEFATOS E EVIDÊNCIAS](https://drive.google.com/drive/folders/15gSPmFtJs5vsIbctVvvmczaxnvctqoGM?usp=sharing "ARTEFATOS E EVIDÊNCIAS")
