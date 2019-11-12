# Tillgänglighet

Exempel på hur vi kan göra vår sida tillgänglig för så många som möjligt

---

## Vad finns det för funktionsvariationer som påverkar möjligheten att använda en webbsida?

* Visuell
* Auditiv
* Mobilitet
* Kognitiv

---

## Visuell
* Dålig eller ingen syn
* Färgblindhet
* Semantiska taggar hjälper
* Skärmläsare kan användas

---

## Auditiv
* Inte jättestor applikation på webben.
* Textalternativ till ljud och undertext

---

## Mobilitet
* Svårighet att använda tangentbord/mus
* Ålderdom och datorvana
---

## Kognitiv
* Dyslexi, ADHD, Autism
* Generellt goda designprinciper hjälper

---

## Generella designprinciper
* Konsekvent layout och navigation
* Minimera distraktioner (tex animationer)
* Fokusera och förenkla innehållet

---

## Resurser för Tillgänglighet

* [a11y project](https://a11yproject.com/checklist/)
* [MND docs: Accessibility](https://developer.mozilla.org/en-US/docs/Web/Accessibility)

---

## Var är länken i denna text?

>Craving a happy medium between full-length tutorials and crawling the docs? Here’s a cookbook of guiding recipes on how to build things, Gatsby style.

---

## Där är dem!

>Craving a happy medium between <a href="#">full-length tutorials</a> and crawling the <a href="#">docs</a>? Here’s a cookbook of guiding recipes on how to build things, Gatsby style.

---

## Kan vi göra det lite bättre?

>Craving a happy medium between <a class="underline" href="#">full-length tutorials</a> and crawling the <a class="underline" href="#">docs</a>? Here’s a cookbook of guiding recipes on how to build things, Gatsby style.

---

## Nu funkar det även fast vi inte har färg

>Craving a happy medium between <span class="underline">full-length tutorials</span> and crawling the <span class="underline">docs</span>? Here’s a cookbook of guiding recipes on how to build things, Gatsby style.

---

## Låt oss kolla in koden

```html
Craving a happy medium between
<span class="underline">full-length tutorials</span>
and crawling the <span class="underline">docs</span>?
Here’s a cookbook of guiding recipes on how to build things,
Gatsby style.
```

---

## Bättre

```html
Craving a happy medium between
<a href="link-to-actual-resource">full-length tutorials</a>
and crawling the <a href="link-to-actual-resource2">docs</a>?
Here’s a cookbook of guiding recipes on how to build things,
Gatsby style.
```

---

## Vilken knapp är viktigast?

<button class="gray">Confirm</button>
<button class="gray">Cancel</button>

---

## Vilken knapp är egentligen viktigast?

<button class="gray">Confirm</button>
<button>Cancel</button>

---

## Vad är det på bilden?

```
<img src="1_2_1_185.jpeg">
```

---

<img src="1_2_1_185.jpeg">

---

## Tillgängligt:

```
<img src="1_2_1_185.jpeg" alt="sexy gnome">
```