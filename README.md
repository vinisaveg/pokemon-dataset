<div align="center">
   <img src=".github/snorlax.gif" width="auto"/>
</div>

<div align="center">
   <h1>pokemon-dataset</h1>
   <p>A pokemon data gathering including sprites, moves, items and stats.</p>
</div>

## About

This dataset is a combination of **Project Pokemon** assets, and **PokeAPI** data.

The current dataset has almost every item and move of pokemon.

For the Pokemon data and assets, it currently has the first generation to the seventh generation.

## Resources

- [PokeAPI](https://pokeapi.co/)
- [Project Pokemon](https://projectpokemon.org/)

## Usage

### Assets

You can find the assets for every pokemon and item inside the **/assets** folder.

Following this pattern should lead you to any asset you want:

      https://raw.githubusercontent.com/vinisaveg/pokemon-dataset/main/assets/items/master-ball.png

OR

      https://raw.githubusercontent.com/vinisaveg/pokemon-dataset/main/assets/pokemon/normal-front/gen1/vileplume.gif

### Data

For the pokemon, items and moves data you will find them inside the **data** folder.

- Fetching a pokemon data

```

   curl https://raw.githubusercontent.com/vinisaveg/pokemon-dataset/main/data/pokemon/17.json

```

- Fetching a item data

```

   curl https://raw.githubusercontent.com/vinisaveg/pokemon-dataset/main/data/items/bicycle.json

```

- Fetching a move data

```

   curl https://raw.githubusercontent.com/vinisaveg/pokemon-dataset/main/data/moves/agility.json

```

## Contribution

Please report any issue and feel free to help the dataset with it´s missing data. :hugs:
