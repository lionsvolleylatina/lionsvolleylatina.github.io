## Come creare un nuovo post

- Andare sul sito: https://github.com/
- Effettuare la login con: `lionsvolleylatina`/`xxx`
- Cliccare sul progetto: ![976f5898ae111b12ce69cb9ec9e3599c.png](/tutorial/ffb355ac8bc14ada834248e6031da24f.png)
- Comparirà la seguente pagina: ![5b0c13b9927bcdfbe6b74a3837f47a36.png](/tutorial/26d20476e82c4566b3cccb9eac744099.png)
- Entrare nella cartella `_posts`
- Comparirà la lista dei post creati: ![1beb2b3739e42a44eb7de3bc77c9223d.png](/tutorial/7a8799ed339c404fa090e095fb72ae6c.png)
- Cliccare sul tasto `Add File` e poi su `Create new file`: ![426c1a7cbd7270d2c9a4d76ee3cac310.png](/tutorial/c4ead9ad733a465a9f7d0f063261b272.png)
- Nella casella del nome, inserire il nome del post rispettando il criterio: `anno-mese-giorno-titolo-separato-da-trattini.md`: ![80a3897ee6bd8d83f6bef84a626fa620.png](/tutorial/fb75a0dd84cc43c3bf22bfeb6d50726c.png)
- Aggiungere nella pagina il seguente contenuto e modificarne il testo secondo le esigenze del post che si sta scrivendo:
```yaml
--- 
layout: post
title: Il nostro primo anniversario!
image: /img/1-anniversario.jpg
author: Staff Lions
---
```
- il valore del campo `image` deve puntare ad una immagine esistente o che si creerà in un secondo momento, l'importante è che l'immagine stia nella cartella `img` e che abbia esattamente il nome assegnato (attenzione all'estensione `.jpg` che, a volte, alcuni programmi, scrivono `.jpeg`).
- Aggiungere dopo i tre trattini finali il testo del post: ![cb0e66bb458260b5edaa9a10b17b8310.png](/tutorial/e807b1d31f1140709aafd4e98da3bb48.png)
- Cliccare sul tasto verde `Commit new file` alla fine della pagina: ![613f9c7f412f621d5d35bf4849c6526b.png](/tutorial/9911d25365cc4f8f8fcc5e94ae28dbce.png)
- Se l'immagine specificata nel file non è ancora presente, aggiungerla con la seguente procedura:
	- dalla pagina principale del progetto, entrare nella cartella `img`: ![4c887b9ce01ee310ed109370ace7cf72.png](/tutorial/41d41f561524432fb9811ee7fd432138.png)
	- cliccare sul tasto `Add file` e poi su `Upload files`: ![990e018e00b5058620325d7dc72917f2.png](/tutorial/58c04cadabcd49358ba2ddf8bf985999.png)
	- Trascinare il file o usare la funzione di esplorazione per selezionarlo dal proprio computer: ![301cb008444490196c511617ec32609a.png](/tutorial/90d3eb3514ee4fddbc177618d6d33cd6.png)
	- attenzione di nuovo al nome del file
	- Cliccare sul tasto verde `Commit changes` in fondo alla pagina per confermare
- Se tutti i passi sono corretti, andando sul sito https://www.lionsvolleylatina.it/ sarà possibile entro qualche minuto vedere il nuovo post: ![a112f6c693e6e2c84600bb120f351543.png](/tutorial/7a80767b0d4e4c5caf3191a29fbe8632.png)
- Il sito usa l'ordinamento alfabetico inverso per decidere l'ordine in cui elencare i post, quindi per ordinare correttamente i post in modo che i più recenti vengano mostrati per primi, basta seguire per il nome del file la convenzione `anno-mese-giorno-titolo.md` usando sempre 4 cifre per l'anno e 2 per mese e giorno, es: `2022-08-09-esempio-di-post.md`

## Come modificare un post

Il post creato nella guida precedente viene mostrato bene nella home page del sito ma cliccando sul tasto `Vai alla notizia` non appare allo stesso modo: ![1041fc404af8bb44a6c3445284ec39ed.png](/tutorial/b40b4b218796423eb38f4ffc6c03cf5c.png)

Per aggiungere una immagine nella pagina del dettaglio della notizia bisogna aggiungere la riga `image-sec: /img/2022-08-12-1anniversario.jpg` nell'intestazione del post. Per fare questo è necessario:
- andare nella cartella `_posts`
- visualizzare il contenuto del file `2022-08-12-anniversario-lions.md`
- cliccare sul tasto con la "penna": ![f2e149c6ab2ae3b8741ee10c9fc2b657.png](/tutorial/3b82d60da1474d3a9b712f211e24267d.png)
- aggiungere la linea mancante nella intestazione del post: ![9782eed6848be5d6488d14d5c3609450.png](/tutorial/437d7295fbff4db1800d038179fa9a96.png)
- Cliccare il tasto verde `Commit changes` in fondo alla pagina
- aggiornando dopo qualche minuto la pagina https://www.lionsvolleylatina.it/2022/08/12/anniversario-lions/ sarà possibile vedere il cambiamento: ![bf0a30cd835dd054a7a2eaf1760df1f7.png](/tutorial/354685393daf4c699e0e8685b7f94f05.png)

## Aggiungere immagini o links da altri siti

&Egrave; possibile aggiungere ai post:
- immagini presenti su altri siti
- links ad altri siti
- links ad account facebook, instagram ecc

Per aggiungere il collegamento ad un sito basta racchiudere il testo da cliccare tra parentesi quadre, seguito dal link racchiuso tra parentesi tonde, es.:
```markdown
L’ultimo scambio… e poi… [LIONS…LIONS…](https://fb.watch/cEMOXFzrpM/)
```
![488525624ab097b6fc4abf6dad2186f1.png](/tutorial/ffd3f10f005d45458c5ae9fecc99bfb4.png)

Allo stesso modo è possibile aggiungere links ad account facebook, instagram ecc:

```markdown
[@lions_volley_latina](https://www.facebook.com/Lionsvolleylatina/) Vs. @sabaudiavolley
```
![b0a49243b94fee3a7e22b63da547d170.png](/tutorial/a37d3e90a7064005a46159e6b2b91dd4.png)

Per includere una immagine presente su un altro sito, supponendo che il link all'immagine sia il seguente (link ad una immagine facebook): `https://scontent.fcia2-2.fna.fbcdn.net/v/t39.30808-6/297769091_192028626502996_5597894925336043817_n.png?_nc_cat=107&ccb=1-7&_nc_sid=730e14&_nc_ohc=xKHFfMzZvDcAX8-QOgm&_nc_ht=scontent.fcia2-2.fna&oh=00_AT_h-Q4TDSlwYcHd5YipZSu-4kzXz2ASY_jiry1Cr9Oc4Q&oe=62FBD187`

il testo da includere è:

```markdown
![Vieni a giocare con noi](https://scontent.fcia2-2.fna.fbcdn.net/v/t39.30808-6/297769091_192028626502996_5597894925336043817_n.png?_nc_cat=107&ccb=1-7&_nc_sid=730e14&_nc_ohc=xKHFfMzZvDcAX8-QOgm&_nc_ht=scontent.fcia2-2.fna&oh=00_AT_h-Q4TDSlwYcHd5YipZSu-4kzXz2ASY_jiry1Cr9Oc4Q&oe=62FBD187)
```

La sintassi è come quella dell'aggiunta di un link, ma c'è un punto esclamativo all'inizio della riga; il testo tra parentesi quadre è quello che compare come "hint" passando col mouse sopra l'immagine.
