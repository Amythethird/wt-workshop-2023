# Flexbox vs. Gridgrid

## Flexbox 
```sh
body {
  min-height: 100vh;
  display: flex;
  flex-direction: column;
}

footer {
  margin-top: auto;
}

/* Optional */
main {
  margin: 0 auto;
  /* or: align-self: center */
  max-width: 80ch;
}
```

## Grid
```sh
body {
  min-height: 100vh;
  display: grid;
  grid-template-rows: auto 1fr auto;
}

/* Optional */
main {
  margin: 0 auto;
  max-width: 80ch;
}
```

# Accessible Dropdown (7)

* Animation with CSS transition and transform
* Using the :focus-within pseudo-class
* CSS grid for positioning
* dynamic centering technique 
* Accessibility considerations for dropdown menus


