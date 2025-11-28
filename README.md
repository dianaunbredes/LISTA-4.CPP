# Sistema de Gerenciamento de Alunos e Notas

Projeto desenvolvido para a disciplina de Programação Estruturada em C++.

## Integrantes
- Grazielle Montinegro dos Santos — Matrícula 251008956  
- Olivia Helena Gomes Martins — Matrícula 242004027  
- Diana Xavier Vieira do Nascimento — Matrícula 251036280  

## Estrutura do Projeto
LISTA4.CPP
│
├── aluno.cpp
├── gerenciamento_de_notas.cpp
├── main.cpp
│
├── alunos.csv
└── notas.csv



## Funcionalidades dos Arquivos

### aluno.cpp
- cadastrar aluno  
- atualizar aluno  
- apagar aluno  
- listar todos os alunos  
- listar aluno específico  

### gerenciamento_de_notas.cpp
- incluir nota  
- alterar nota  
- apagar nota  
- listar notas e médias  
- listar um aluno com suas notas  
- validações de matrícula, referência e média  

### main.cpp
- exibir o menu principal  
- carregar dados dos CSV  
- salvar alterações automaticamente  
- integrar todas as funções do sistema  

---

## Formato dos Arquivos CSV

### alunos.csv
matricula,nome
202500123,Maria
202500998,Joao
202501556,Ana
202502334,Luiz
202503778,Pedro


### notas.csv
matricula;referencia;valor
11111;P1A;8.5
11111;P1B;7.0
11111;P2A;9.3
12345;P1A;5.4
12345;P1B;7.9
22334;P1A;0.5


---

## Como Compilar
g++ main.cpp aluno.cpp gerenciamento_de_notas.cpp -o sistema


---

## Funcionalidades do Sistema
- Cadastrar aluno  
- Atualizar aluno  
- Apagar aluno  
- Listar alunos  
- Listar aluno específico  
- Incluir nota  
- Alterar nota  
- Apagar nota  
- Listar alunos com notas e médias  
- Consultar notas de um único aluno  
- Validação de matrícula duplicada  
- Validação de referência duplicada  
- Cálculo automático de média  

---

## Observações
- O sistema lê automaticamente os CSV ao iniciar.  
- Toda alteração é salva automaticamente.  
- Os arquivos devem manter o formato original.  

