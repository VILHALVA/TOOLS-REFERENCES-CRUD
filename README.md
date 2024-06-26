# TOOLS REFERENCES CRUD
👨‍🏫ESTE APLICATIVO É UM SISTEMA DE GERENCIAMENTO DE FERRAMENTAS E REFERÊNCIAS, DESENVOLVIDO COM PYQT5/PYSIDE6 E PEEWEE ORM E SQLITE.

<img src="./IMAGENS/FOTO_1.png" align="center" width="500"> <br>
<img src="./IMAGENS/FOTO_2.png" align="center" width="500"> <br>
<img src="./IMAGENS/FOTO_3.png" align="center" width="500"> <br>
<img src="./IMAGENS/FOTO_4.png" align="center" width="500"> <br>

## DESCRIÇÃO:
Este aplicativo é um sistema de gerenciamento de ferramentas e referências, desenvolvido com PyQt5/PySide6 e Peewee ORM para Python. Ele permite aos usuários realizar várias operações relacionadas à criação, edição, busca e visualização de informações sobre ferramentas e referências. 

## FUNCIONALIDADES:
1. **Adicionar e Buscar Ferramentas:**
   - **Adicionar Ferramenta:** Permite inserir novas ferramentas com detalhes como categoria, plataforma, tipo de licença, suporte a API, nome, descrição, versão, datas de lançamento e atualização, produtor, classificação, link para download e escolha do editor.
   - **Buscar Ferramenta:** Permite buscar ferramentas existentes com a capacidade de editar informações detalhadas sobre cada ferramenta.

2. **Adicionar e Buscar Referências:**
   - **Adicionar Referência:** Facilita a inclusão de novas referências com detalhes como nome, tipo, URL e resumo.
   - **Buscar Referência:** Oferece a capacidade de buscar referências existentes e editar suas informações.

3. **Interface de Usuário Intuitiva:**
   - **Barra de Ferramentas:** Uma barra de ferramentas na janela principal permite navegar facilmente entre as funcionalidades de adicionar e buscar ferramentas e referências.
   - **Páginas de Conteúdo:** Utiliza várias páginas (`ToolPage`, `ToolListPage`, `ReferencePage`, `ReferenceListPage`) para organizar e exibir os detalhes das ferramentas e referências de forma clara e organizada.

4. **Personalização e Estilo:**
   - **Estilização:** Utiliza um arquivo de estilo (`.qss`) para personalizar a aparência da interface gráfica, proporcionando uma experiência visual única e coerente.
   - **Configuração da Janela:** Define ícones específicos para a aplicação e configura o tamanho e posição inicial da janela para uma melhor experiência de usuário.

## EXECUTANDO O PROJETO: 
1. **Instalação:**
   - Entre no diretório `CODIGO` e execute o comando:

   ```bash
   pip install -r requirements.txt
   ```

2. **Iniciando o APP:**
   - Ainda no diretório `CODIGO` e execute o comando:

   ```bash
   python main.py
   ```

3. **Operações Básicas:**
   - **Adicionar Ferramenta:** Clique na opção "Add Tool" na barra de ferramentas para inserir uma nova ferramenta. Preencha os campos necessários na página correspondente e salve as informações.
   - **Buscar Ferramenta:** Selecione a opção "Search Tool" na barra de ferramentas para procurar e editar detalhes de ferramentas existentes.
   - **Adicionar Referência:** Clique em "Add Reference" para incluir uma nova referência. Insira os detalhes requeridos e confirme o salvamento.
   - **Buscar Referência:** Selecione "Search Reference" para encontrar e atualizar informações de referências já cadastradas.

4. **Personalização:**
   - Modifique as configurações de estilo no arquivo `.qss` para ajustar a aparência visual da aplicação conforme necessário.
   - Ajuste as enumerações (`reference_types`, `tool_categories`, `tool_platforms`, etc.) para personalizar as opções disponíveis de categorias, tipos, plataformas e outros filtros conforme as necessidades do seu projeto.

## NÃO SABE?
- Entendemos que para manipular arquivos em muitas linguagens e tecnologias, é necessário possuir conhecimento nessas áreas. Para auxiliar nesse aprendizado, oferecemos cursos gratuitos disponíveis:
* [CURSO DE PYTHON](https://github.com/VILHALVA/CURSO-DE-PYTHON)
* [CURSO DE PYSIDE](https://github.com/VILHALVA/CURSO-DE-PYSIDE)
* [CONFIRA MAIS CURSOS](https://github.com/VILHALVA?tab=repositories&q=+topic:CURSO)

## CREDITOS:
- [PROJETO CRIADO PELO "techguruCD"](https://github.com/techguruCD/tools-references-crud)
- [PROJETO EDITADO PELO VILHALVA](https://github.com/VILHALVA)
