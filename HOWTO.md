<img src="https://github.com/italia/spid-graphics/blob/master/spid-logos/spid-logo-b-lb.png" alt="SPID" data-canonical-src="https://github.com/italia/spid-graphics/blob/master/spid-logos/spid-logo-b-lb.png" width="500" height="98" />

## Come inserire una richiesta di supporto o segnalazione

### Accesso o registrazione
Per inserire una richiesta di supporto o segnalazione è necessario accedere o registrarsi a GitHub collegandosi alla pagina [https://github.com/join?source=login](https://github.com/join?source=login).<br>
<img src="https://github.com/italia/spid/blob/master/assets/images/howto/spid-howto-img01.png" alt="" data-canonical-src="https://github.com/italia/spid/blob/master/assets/images/howto/spid-howto-img01.png" width="90%" />

### Visualizzazione e inserimento di una richiesta di supporto o segnalazione
Per visualizzare o inserire una richiesta di supporto o segnalazione collegarsi alla pagina [https://github.com/italia/spid/issues](https://github.com/italia/spid/issues).<br>
<img src="https://github.com/italia/spid/blob/master/assets/images/howto/spid-howto-img02.png" alt="" data-canonical-src="https://github.com/italia/spid/blob/master/assets/images/howto/spid-howto-img02.png" width="90%" />

#### Visualizzazione e ricerca
Per cercare una richiesta di supporto o segnalazione possono essere utilizzati i filtri e il campo di ricerca; in maniera predefinita vengono mostrate solo quelle aperte, per vederle tutte basta digitare, nel campo di ricerca, "is:issue is:closed is:open"<br>
<img src="https://github.com/italia/spid/blob/master/assets/images/howto/spid-howto-img03.png" alt="" data-canonical-src="https://github.com/italia/spid/blob/master/assets/images/howto/spid-howto-img03.png" width="90%" />

**Altri esempi di ricerca**

Issue che contengono una stringa (spid) nel titolo<br>
[is:issue is:open is:closed "spid" in:title](https://github.com/italia/spid/issues?utf8=%E2%9C%93&q=is:issue%20is:open%20is:closed%20%E2%80%9Cspid%E2%80%9D%20in:title)

Issue che sono state commentate da un utente (umbros)<br>
[q=is:issue is:open is:closed commenter:umbros](https://github.com/italia/spid/issues?utf8=✓&q=is:issue%20is:open%20is:closed%20is:closed%20commenter:umbros)

Issue che sono state modificate ad una data specifica (formato data: YYYY-MM-DD)<br>
[q=is:issue is:open is:closed updated:2018-02-22](https://github.com/italia/spid/issues?utf8=%E2%9C%93&q=is:issue%20is:open%20is:closed%20updated:2018-02-22)

Issue che sono state modificate negli ultimi giorni (formato data: YYYY-MM-DD)<br>
[is:issue is:open updated:>=2018-02-01](https://github.com/italia/spid/issues?utf8=%E2%9C%93&q=is:issue%20is:open%20is:closed%20updated:%3E=2018-02-01)

#### Inserimento
Per inserire una richiesta di supporto o segnalazione, cliccare sul pulsante verde "[New issue](https://github.com/italia/spid/issues/new)";<br>
<img src="https://github.com/italia/spid/blob/master/assets/images/howto/spid-howto-img04.png" alt="" data-canonical-src="https://github.com/italia/spid/blob/master/assets/images/howto/spid-howto-img04.png" width="90%" />

si aprirà il modulo di inserimento richieste di supporto e segnalazioni dove dovranno essere rispettate le istruzioni di caricamento issue che compaiono nel campo di inserimento dettagli (cancellare il testo che viene precaricato):<br>
* la pubblica amministrazione o soggetto privato per cui si richiede il supporto;
* la label (categoria) per categorizzare la segnalazione;
* se la segnalazione è tecnica inserire una descrizione accurata del comportamento o dell'errore;
* se la segnalazione è tecnica indicare se si riscontra in ambiente di test o con tutti o parte degli IDP in produzione (specificando quali).<br>
<img src="https://github.com/italia/spid/blob/master/assets/images/howto/spid-howto-img05.png" alt="" data-canonical-src="https://github.com/italia/spid/blob/master/assets/images/howto/spid-howto-img05.png" width="90%" />

Importante specificare la categoria (Label) della richiesta di supporto o segnalazione scegliendo tra:
* info roadmap componenti
* info roadmap funzionalità
* segnalazione anomalie
* suggerimenti e feedback
* supporto - openid connect
* supporto - saml
* supporto amministrativo
* supporto attribute authority

a queste categorie è possibile aggiungere la label **richiesta urgente** se dovesse verificarsi una situazione d'urgenza (lo staff sarà libero di valutarne la reale priorità).

Se si volesse menzionare un utente utilizzare il simbolo @ seguito dal nickname; esempio: @umbros

#### Soggetti titolati a fornire risposte ufficiali per conto di AgID
AgID è il soggetto gestore della federazione SPID, le risposte che vengono date dalle seguenti persone:
<table>
	<tr>
		<td><img src="https://avatars0.githubusercontent.com/u/23704006?s=64&v=4" alt="Stefano Arbia" data-canonical-src="https://avatars0.githubusercontent.com/u/23704006?s=64&v=4" /></td>
		<td><b>Stefano Arbia (<i>arbiastefano</i>)</b><br>Responsabile progetto SPID<br>email: arbia@agid.gov.it<br>Agenzia per l'Italia Digitale</td>
	</tr>
	<tr>
		<td><img src="https://avatars2.githubusercontent.com/u/4085151?s=64&v=4" alt="Umberto Rosini" data-canonical-src="https://avatars2.githubusercontent.com/u/4085151?s=64&v=4" /></td>
		<td><b>Umberto Rosini (<i>umbros</i>)</b><br>Responsabile tecnico progetto SPID<br>email: rosini@agid.gov.it<br>Agenzia per l'Italia Digitale</td>
	</tr>
	<tr>
		<td><img src="https://avatars1.githubusercontent.com/u/3876198?s=64&v=4" alt="Antonio Giovanni Schiavone" data-canonical-src="https://avatars1.githubusercontent.com/u/3876198?s=64&v=4" /></td>
		<td><b>Antonio Giovanni Schiavone (<i>antoniogiovannischiavone</i>)</b><br>email: antoniogiovanni.schiavone@agid.gov.it<br>Collaboratore Agenzia per l'Italia Digitale</td>
	</tr>
	<tr>
		<td><img src="https://avatars2.githubusercontent.com/u/31276401?s=64&v=4" alt="Michele D'Amico" data-canonical-src="https://avatars2.githubusercontent.com/u/31276401?s=64&v=4" /></td>
		<td><b>Michele D'Amico (<i>damikael</i>)</b><br>email: michele.damico@agid.gov.it<br>Collaboratore Agenzia per l'Italia Digitale</td>
	</tr>
</table>

hanno carattere di ufficialità; qualora un altro soggetto appartenente alla community dovesse rispondere correttamente e risolvere la richiesta di supporto o segnalazione pervenuta, una o più persone, tra quelle sopra citate, apporrà un "pollice in alto (like - thumbs up emoji)" per confermarne la validità e procederà a chiudere la issue.
<br>
<img src="https://github.com/italia/spid/blob/master/assets/images/howto/spid-howto-img06.png" alt="" data-canonical-src="https://github.com/italia/spid/blob/master/assets/images/howto/spid-howto-img06.png" width="90%" />
