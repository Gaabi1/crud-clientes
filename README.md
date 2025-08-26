# CRUD de Clientes

Projeto de **CRUD (Create, Read, Update, Delete)** de cadastro de clientes feito em **HTML, CSS e JavaScript**, utilizando o **LocalStorage** do navegador para armazenamento de dados.

---

## Funcionalidades

1. **Cadastrar clientes**
   - Permite inserir nome, e-mail, celular e cidade.
   - Os dados são validados com campos obrigatórios antes de salvar.

2. **Listar clientes**
   - Exibe todos os clientes cadastrados em uma tabela dinâmica.

3. **Editar clientes**
   - Permite alterar os dados de um cliente já cadastrado.

4. **Excluir clientes**
   - Permite remover clientes da tabela e do LocalStorage.

5. **Buscar clientes**
   - Campo de busca que filtra clientes por nome, e-mail, celular ou cidade em tempo real.

---

## Tecnologias utilizadas

- **HTML5** – Estrutura do formulário e tabela.
- **CSS3** – Estilização do layout e modal.
- **JavaScript (ES6)** – Lógica de CRUD, manipulação do DOM, LocalStorage e eventos.
- **LocalStorage** – Armazenamento persistente dos dados no navegador.

---

## O que aprendi com esse projeto

1. **Manipulação de arrays e objetos em JavaScript**
   - Uso de `push`, `splice`, `filter` e `forEach`.
   - Criação e atualização de objetos com propriedades de clientes.

2. **DOM e eventos**
   - Uso de `document.getElementById`, `querySelector` e `querySelectorAll`.
   - Criação dinâmica de elementos com `createElement` e `appendChild`.
   - Manipulação de eventos (`click`, `input`) para interatividade.

3. **Funções modernas (Arrow Functions)**
   - Simplificação da sintaxe de funções anônimas.

4. **Validação de formulários**
   - Uso do `reportValidity()` para validar campos obrigatórios antes de salvar.

5. **LocalStorage**
   - Armazenamento e leitura de dados persistentes no navegador usando `JSON.stringify` e `JSON.parse`.

6. **Modais**
   - Criação de janelas modais para cadastrar e editar clientes.

7. **Filtros e buscas**
   - Filtragem de arrays com `filter()` para criar busca dinâmica na tabela.

## Como testar

1. Abra o arquivo `index.html` em um navegador moderno (Chrome, Edge, Firefox).  
2. Clique em **"Cadastrar Cliente"** para abrir o modal.  
3. Preencha os campos e clique em **Salvar**.  
4. Use os botões **Editar** e **Excluir** para manipular os clientes.  
5. Utilize o campo de **Busca** para filtrar clientes por nome, e-mail, celular ou cidade.
