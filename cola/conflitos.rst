==================
Resolver conflitos
==================

Visualizar conflitos de ``merge``
---------------------------------

::

	git diff		# diff completo do conflito
  git diff --base «arquivo»			# em relação à base
  git diff --ours «arquivo»			# em relação às nossas alterações
  git diff --theirs «arquivo»		# em relação às alterações dos outros


Descartar um *patch* conflitante
--------------------------------

::

	git reset --hard
	git rebase --skip


