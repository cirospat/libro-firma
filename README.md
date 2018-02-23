## Facciamo una samba con #processi della #PA, #dati, #cittadini #design e #servizidigitali?
Un report per capire un po meglio la PA nel suo cammino verso la **transizione al digitale** del Codice dell'Amministrazione Digitale

Riflessioni, appunti e input di Ciro Spataro.
<p><img class="imageLeft" style="width: 53px; height: 60px;" src="https://raw.githubusercontent.com/cirospat/la-samba-digitale-della-pa/master/imgrel/3loghi.png" alt="HTML editor tools" />
  
  ### Report navigabile online

L'elenco e i capitoli del report sono [navigabili online](http://samba-digitale-pa.readthedocs.io)

------


### Requisiti

- [Sphinx](http://www.sphinx-doc.org/en/stable/)

### Build
Dopo aver apportato le dovute modifiche in [`rst/`](./rst) esegui

```
sphinx-build -b html src docs
```

oppure

```
make html
```

**Riuso**

Ho scritto questo report creando un progetto ad hoc su **GitHub**, usando il linguaggio **Markdown** per la visualizzazione del testo su «**Read The Docs**». Ho riusato il codice inizialmente utilizzato dal Team Trasformazione Digitale per la pubblicazione della [«Relazione della Commissione Parlamentare di Inchiesta sul livello di digitalizzazione delle pubbliche amministrazioni italiane»](https://relazione-commissione-digitale.readthedocs.io/it/latest/). Vedi progetto su [Github](https://github.com/italia/relazionecommissionedigitale-docs).

Per l'integrazione dei commenti tramite il servizio di [**Diquis**](https://disqus.com/) ho riusato il progetto Read The Docs del [comune di Gioia del Colle](http://foia.readthedocs.io/en/latest/) che si trova [in questo repository](https://github.com/gioialab/foia/tree/master/source/_themes/sphinx_italia_theme).

**Licenza** 

[CC-BY 4.0 (Creative Commons Attribution)](https://creativecommons.org/licenses/by/4.0/)
