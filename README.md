# frontprojecttemplate

A ideia desse projeto eh servir como template para qualquer projeto inicial de front.

Esse projeto fara uso do bower e node (grunt).

Pesquisar se eh possivel gerar meu proprio yeoman para gerar essa estrutura que esta sendo criada aqui.

settings: Possui o js que aponta para uma api mockada ou oficial

A ideia eh o bower gerar uma pasta libs

A compilacao do projeto deve ter seu resultado dentro da pasta dist

templates- Essa pasta possuira ao menos 3 templates:
= docs_template.html: template utilizado pela pagina de documentacao. O processo de build devera importar todos os scripts utilizados para documentacao. Serao colocados dentro do espaco delimitado nesse template.
- index_template.htmj: template utilizado pela aplicacao. O processo de build devera importar todos os scripts necessarios. A ideia eh poder importar todos os script isolado, apenas os scripts minificados (simulando producao) e talvez outros (importar os scripts concatenados, mas nao minificados)
- icons_template.css - template de webfonts modificado pelo teles. Esse cara ira gerar o template de fonts para compilar junto com o sass.

O gruntfile.js deve ser pequeno e suas tasks ficarao dentro da pasta grunt-tasks.

Outra ideia eh verificar a possibilidade de uso do vagrant para configuracao da maquina, instalar todos os pacotes necessarios para o projeto.