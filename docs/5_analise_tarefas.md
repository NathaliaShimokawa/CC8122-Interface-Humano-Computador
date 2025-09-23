# Análise de Tarefas

> **_NOTE:_**: A equipe deve descrever as funcionalidades mais importantes da interface/produto. A equipe deve modelar pelo menos 1 HTA, 1 GOMS e 1 CTT (de pelo menos 4 funcionalidades diferentes). Cada diagrama deve ter um texto explicando a funcionalidade.

1. HTA
2. GOMS
3. CTT

<details>
<summary><h3> 2. GOMS – Registrar Imagens</h3></summary>

## GOAL 0: Registrar imagens

---

## GOAL 1: Adicionar imagem 

### METHOD 1.A: Upload manual da imagem  
*(SEL. RULE: a imagem está no dispositivo do usuário)*  
- **OP. 1.A.1:** clicar no botão “Adicionar Imagem”  
- **OP. 1.A.2:** selecionar arquivo de imagem no explorador do sistema  
- **OP. 1.A.3:** confirmar upload  

### METHOD 1.B: Importar imagem do banco de dados do sistema  
*(SEL. RULE: imagem já disponível no sistema)*  
- **OP. 1.B.1:** clicar em “Imagens disponíveis”  
- **OP. 1.B.2:** navegar até a pasta desejada  
- **OP. 1.B.3:** selecionar imagem  
- **OP. 1.B.4:** confirmar importação  

---

## GOAL 2: Associar tags à imagem

### METHOD 2.A: Inserir tags manualmente  
*(SEL. RULE: poucas tags específicas conhecidas pelo usuário)*  
- **OP. 2.A.1:** clicar no campo “Tags”  
- **OP. 2.A.2:** digitar tags  
- **OP. 2.A.3:** confirmar inserção das tags  

### METHOD 2.B: Selecionar tags pré-cadastradas  
*(SEL. RULE: tags já padronizadas no sistema)*  
- **OP. 2.B.1:** clicar em “Selecionar Tags”  
- **OP. 2.B.2:** marcar checkboxes correspondentes  
- **OP. 2.B.3:** confirmar seleção  

---

## GOAL 3: Salvar imagem e tags no banco de dados

- **OP. 3.1:** clicar no botão “Salvar”  
- **OP. 3.2:** visualizar mensagem de confirmação  

</details>

