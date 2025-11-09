# passo 0: Controllare di avere java installato

premere il tasto win (tasto in basso a sinistra tra il ctrl e Alt, dovrebbe avere il simbolo ti windows o avere scritto direttamente Win)

digitare cmd e selezionare il "prompt dei comandi" e premere invio
![[Pasted image 20251109011108.png]]

all'interno del prompt scrivere "java --version" e controllare l'output.
se non è come quello riportato nell'immagine sottostante (java x.x.x) bisogna scaricare java
![[Pasted image 20251109011314.png]]

# passo 0.1: installare java
andare al link https://www.oracle.com/java/technologies/downloads/#jdk21-windows e installare il file x64 MSI installer cliccando il link (evidenziato nella foto sottostante)
![[Pasted image 20251109011619.png]]

fare doppio click sul file installato. dare gli accessi e procedere all'installazione. apparirà una finestra come questa: ![[Pasted image 20251109011909.png]]significa che siete pronti all'installazione, cliccare next. scegliere il percorso di installazione (va bene lasciare quello di default) e cliccare nuovamente next. dare i permessi e infine cliccare chiudi alla fine dell'installazione

# passo 1: installare fabric
andare su questo link: https://fabricmc.net/use/installer e cliccare su "Download Universal jar" (evidenziato nell'immagine)
![[Pasted image 20251109012324.png]]
verrà scaricato un file con nome fabric-installer-1.1.0.jar
fare tasto destro sul file e fare "apri con java"
![[Pasted image 20251109012509.png]]uscirà questa schermata:
![[Pasted image 20251109012546.png]]
selezionare la versione di minecraft interessata (nel nostro caso specifico 1.21.10) e cliccare il bottone "installa" 

RICORDA DI AVER MINECRAFT COMPLETAMENTE CHIUSO, ALTRIMENTI NON VERRA' INSTALLATO!!!

![[Pasted image 20251109012843.png]]
YAAAYYY!!!!
ora nel launcher dovreste avere l'opzione di startarlo con fabric
![[Pasted image 20251109013137.png]]
# passo 2: installazione fabricAPI (base per tutte le mod)

la mod base che tutte utilizzano la bisogna scaricare a questo link https://modrinth.com/mod/fabric-api?version=1.21.10 cliccare download > selezionare la versione desiderata (nel nostro caso specifico la 1.21.10) > cliccare download![[Pasted image 20251109013841.png]]![[Pasted image 20251109014039.png]]
ora bisogna metterlo nella cartella giusta, aprire il launcher e andare su "installazioni"
![[Pasted image 20251109014211.png]]e cliccare il simbolo della cartella andandoci sopra con il mouse
![[Pasted image 20251109014309.png]]
se non presente creare una cartella "mods"
![[Pasted image 20251109014514.png]]all'interno di questa cartella mettere il file fabric-api