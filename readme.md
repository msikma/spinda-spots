This is a proof of concept for displaying Spinda's spots on its box sprite.

View the [PokéSprite Spinda Painter](https://msikma.github.io/spinda-spots/) to give it a try.

Spinda is a Pokémon with four spots on its face, whose coordinates are determined by its "personality value", a hidden number inside its data. In the game itself, each Spinda has the same generic box sprite (its custom spots are only visible in battle), but by using a blank sprite and a masked overlay sprite we're able to show its spots on its box sprite as well.

The following sprites are used:

<table>
  <tr>
    <th colspan="2">Sprites</th>
    <th>Form</th>
    <th>Description</th>
  </tr>
  <tr>
    <td><img src="docs/regular/spinda.png" width="68" height="56" alt="Spinda default form sprite - regular"></td>
    <td><img src="docs/shiny/spinda.png" width="68" height="56" alt="Spinda default form sprite - shiny"></td>
    <td>–</td>
    <td>Regular form sprite displayed in the original games</td>
  </tr>
  <tr>
    <td><img src="docs/regular/spinda-blank.png" width="68" height="56" alt="Spinda blank form sprite - regular"></td>
    <td><img src="docs/shiny/spinda-blank.png" width="68" height="56" alt="Spinda blank form sprite - shiny"></td>
    <td>blank</td>
    <td>Blank sprite with no spots</td>
  </tr>
  <tr>
    <td><img src="docs/regular/spinda-filled.png" width="68" height="56" alt="Spinda filled form sprite - regular"></td>
    <td><img src="docs/shiny/spinda-filled.png" width="68" height="56" alt="Spinda filled form sprite - shiny"></td>
    <td>filled</td>
    <td>Spot coloration overlay sprite</td>
  </tr>
</table>

See [PokéSprite](https://github.com/msikma/pokesprite) for more details.

## Related links

* **[PokéSprite](https://github.com/msikma/pokesprite)** – Pokémon sprite database
* [Thundaga Spinda Painter](http://pokemon.thundaga.com/spinda/Spinda%20Painter.htm) – The original Spinda painter that this is based on

## License

The sprite images are © Nintendo/Creatures Inc./GAME FREAK Inc.

Everything else falls under the [MIT license](http://opensource.org/licenses/MIT).
