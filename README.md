# Certificação Bootstrap Módulo 3
# Atividade Prática

Elabore um boilerplate que será o ambiente básico para desenvolver um projeto escalável. Segue a estrutura de pastas e arquivos que o projeto deve conter.

--- dist
--- source
------ scss
------------ base.scss
------------ layout.scss
------------ style.scss
------ index.html

Ou seja na raiz do projeto teremos a pasta dist e source, dentro de source teremos o index.html e a pasta scss com seus arquivos (base, layout e style).

Sua responsabilidade é criar tarefas que vão compilar e minificar os arquivos da pasta scss e enviar para a pasta (css) que ficará dentro da pasta dist.

Além disso você deve criar outra tarefa responsável por minificar o html da pasta source e enviar para dist.

Sendo assim você terá que pesquisar plugins no site oficial do GulpJS para encontrar soluções para resolver o problema em questão.

Um ponto importante é que: todos os arquivos da pasta source deve conter um watch para monitorar alterações (salvar o arquivo) e invocar suas respectivas tarefas. 
