# playList

#Comandi commit


##Git status
Verifica quali sono i file che sono stati modificati rispetto alla loro versione remota sul repository
<pre><code>git status</code></pre>
##Git diff
Verifica quali sono le modifiche effettuate al file "fileName"
<pre><code>git diff fileName
</code></pre>
##Git add
Addiunge il file con nome "fileName" all'index
<pre><code>git add fileName
</code></pre>

## Git commit
Aggiunge i file presenti nell'Index all' Head

<pre><code>git commit -m "Messaggio che descrive le modifiche fatte"
</code></pre>
Alternativa al precedente commit è **git commit -am**. Questo consiste in un *git add* di tutti i file seguito da un *git commit*
<pre><code>git commit -am "Messaggio che descrive le modifiche fatte"
</code></pre>

##Git push
Per salvare le modifiche sul repository remoto

##Git pull
Per caricare sul repository locale tutte le modifiche del repo remoto
