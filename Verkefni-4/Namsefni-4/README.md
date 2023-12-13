# Svegjanleg hönnun

### Viðmið (_Breakpoints_) - "_Mobile up_"

```CSS

/* Fyrst koma stílar sem gilda í öllum skjástærðum ss. leturgerð og litir */
body {
  background-color: lightblue;
  font-family: sans-serif;
  color: white;
}

@media only screen and (min-width: 600px) {  /* skjáir (screen) sem eru stærri en 600px */
  body {
    background-color: blue;
  }
}

@media only screen and (min-width: 768px) {  /* skjáir (screen) sem eru stærri en 768px */
  body {
    background-color: green;
  }
}

@media only screen and (min-width: 960px) {  /* skjáir (screen) sem eru stærri en 960px */
  body {
    background-color: red;
	  max-width: 60em;
	  margin: 0 auto;
	  border: 2px solid yellow;
  }
}

``` 


