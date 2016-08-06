# PokemonGoStats.js
JavaScript functions used to calculate Pokemon Stats in Pokemon Go game.

For IVs part. Use this API to retrive those values https://github.com/tejado/pgoapi.

## How to use?

```HTML
<script src="PokemonGoStats.js" type="text/javascript"></script>
<script type="text/javascript">

var Vaporeon = new PokemonGoStats(134);

console.log(
  Vaporeon.calcStats(
    IV_Stamina = 15,
    IV_Attack = 15,
    IV_Defense = 15,
    CP = 2595
  )
); // {HP: 208, Atk: 152, Def: 138}

console.log(
  Vaporeon.calcLevel(
    IV_Stamina = 15,
    IV_Attack = 15,
    IV_Defense = 15,
    CP = 2595
  )
); // 34.5

console.log(
  Vaporeon.calcCP(
    IV_Stamina = 15,
    IV_Attack = 15,
    IV_Defense = 15,
    PokemonLevel = 34.5
  )
); // 2595

console.log(
  Vaporeon.calcMaxCP(
    IV_Stamina = 15,
    IV_Attack = 15,
    IV_Defense = 15,
    PlayerLevel = 40
  )
); // 2816

</script>
```

## Limitation
- Both Player level and Pokemon level max at 40
- First Generation Pokemons only (Dex 001-151)
