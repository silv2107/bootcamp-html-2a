# HTML Bootcamp #1

HTML er en fantastisk måde at præsentere tekst, billeder og video på.

Da Sir Tim Berners-Lee opfandt HTML i starten af 1990-erne, var det hans tanke at dette var det eneste, HTML skulle bruges til. Og hvis vi tænker lidt over det, er det så ikke netop dette en hjemmeside gør?

Som du ved, er HTML bygget op af noget vi kalder en `Document Object Model` eller `DOM`. Det vil sige, at **alt i et HTML-dokument er objekter**. Objekter i HTML er repræsenteret af `tags`.

Et tag er op bygget af et sæt markeringer, som vi kalder start- og slut-tags.

```
<>          </>
 ^           ^
 start tag   slut tag
```

Hvad der står inde i tagget bestemmer hvordan objektet, som tagget repræsenterer, opfører sig.

Skriver du for eksempel `<p> </p>`, opfører objektet sig som et tekstafsnit.

Det rå indhold vi skriver imellem et tag-sæt er det, vi kalder **det håndgribelige indhold** - eller **tangible content**.

```html
<p>Lorem ipsum dolor sit amet ...</p>
```

Et tag kan have forskellige attributter, som yderligere definerer hvordan objektet skal opføre sig. For eksempel skal HTML-dokumentet vide, hvilken adresse en bruger skal sendes til, hvis hun klikker på **det håndgribelige indhold** imellem 2 `anchor-tags`.

```html
<a href="https://duckduckgo.com">Duck it!</a>
```

Der er nogle få undtagelser til reglen om et sæt tags.

> Hvis et objekt's håndgribelige indhold udelukkende beskrives af tagget's attributter, har objektet ikke noget slut-tag.

Dette kan være et image-, link- eller meta-tag. Det håndgribelige indhold i for eksempel et image-tag er beskrevet af attributten `src`

```html
<img src="/assets/media/profile.png">
```

## Opgave
Du skal nu lave et HTML dokument, som viser, at du behersker den overordnede HTML-struktur.

* Opret en fil i dette repository, som du kalder `index.html`
* Filen skal indeholde
	* `head`-sektion
	* `body`-sektion
	* `body`-sektionen skal have mindst 20 forskellige objekter, med indhold.
* Din HTML skal valideres på https://html5.validator.nu/

Du må gerne bruge lorem ipsum, og til billeder kan du for eksempel bruge https://lorempixel.com eller https://placeholder.com.

Du skal ikke style dit dokument.

### Aflevering
Din aflevering foregår via GitHub. Du skal lave en pull-request fra dit eget repository til det repository, du har klonet fra.