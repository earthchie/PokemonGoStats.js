# PoGo-MaxCP
Javscript functions used to calculate Pokemon's Max CP in Pokemon Go game.
You need to know Pokemon's IVs and Player Level in order to calculate Max CP.

For IVs part. Use this API to retrive those values https://github.com/tejado/pgoapi.

## How to use?

```HTML
<script src="PoGo-MaxCP.js" type="text/javascript"></script>
<script type="text/javascript">
console.log(
  maxCP(
    DexId = 133, // Dex Number (133 = Eevee)
    IVSta = 15, // Individual Stamina Value
    IVAtk = 15, // Individual Attack Value
    IVDef = 15, // Individual Defense Value
    PlayerLevel = 40 // Player's Current Level
  )
);
</script>
```

## Supoort
First Generation Pokemons (Dex 001-151)
