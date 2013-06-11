=====
Criar
=====

Criar a partir de um repositório existente
-------------------------------------------

::

	git clone ~/existente/repo ~/novo/repo
	git clone git://host.org/projeto.git
	git clone ssh://your@host.org/projeto.git

Exibir (Show)
-------------

Arquivos alterados em um diretorio de trabalho
++++++++++++++++++++++++++++++++++++++++++++++

::

	git status

Mudanças em arquivos versionados
++++++++++++++++++++++++++++++++

::

	git diff

O que mudou entre $ID1 and $ID2
+++++++++++++++++++++++++++++++

::

	git diff $id1 $id2
	
Historico de mudanças
+++++++++++++++++++++

::

	git log

Historico de mudança para arquivo com diffs
+++++++++++++++++++++++++++++++++++++++++++

::

	git log -p $file $dir/ec/tory/

Quem mudou o que e quando em um arquivo
+++++++++++++++++++++++++++++++++++++++

::

	git blame $file

Um commit identificado por $ID
++++++++++++++++++++++++++++++

::

	git show $id

Um arquivo especifico de um $ID especifico
++++++++++++++++++++++++++++++++++++++++++

::

	git show $id:$file

Todos os branches locais
++++++++++++++++++++++++

::

	git branch
