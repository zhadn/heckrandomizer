# Characters
Hecadecimal reference for characters operations.

## Character reference
| Character | Index  |
| --------- | ------ |
| Serge     | `00`   |
| Kid       | `01`   |
| Guile     | `02`   |
| Norris    | `03`   |
| Nikki     | `04`   |
| Viper     | `05`   |
| Riddel    | `06`   |
| Karsh     | `07`   |
| Zoah      | `08`   |
| Marcy     | `09`   |
| Korcha    | `0A`   |
| Luccia    | `0B`   |
| Poshul    | `0C`   |
| Razzly    | `0D`   |
| Zappa     | `0E`   |
| Orcha     | `0F`   |
| Radius    | `10`   |
| Fargo     | `11`   |
| Macha     | `12`   |
| Glenn     | `13`   |
| Leena     | `14`   |
| Miki      | `15`   |
| Harle     | `16`   |
| Janice    | `17`   |
| Draggy    | `18`   |
| Starky    | `19`   |
| Sprigg    | `1A`   |
| Mojo      | `1B`   |
| Turnip    | `1C`   |
| NeoFio    | `1D`   |
| Greco     | `1E`   |
| Skelly    | `1F`   |
| Funguy    | `20`   |
| Irenes    | `21`   |
| Mel       | `22`   |
| Leah      | `23`   |
| Van       | `24`   |
| Sneff     | `25`   |
| Steena    | `26`   |
| Doc       | `27`   |
| Grobyc    | `28`   |
| Pierre    | `29`   |
| Orlha     | `2A`   |
| Pip       | `2B`   |

| Slot Character  | Index  |
| --------------- | ------ |
| Party Member #1 | `FF`   |
| Party Member #2 | `FE`   |
| Party Member #3 | `FD`   |

## Examples

### Adding to the party
Add Serge to the party with the following hexadecimal operation.

```
{7B 00 80}
```

The `00` is an index that can be swapped for different characters. As an example, set `00` to `01` to add Kid to the party.

### Removing from the party
Remove Serge from the party with the following hexadecimal operation.

```
{7D 00 80}
```

The `00` is an index that can be swapped for different characters. As an example, set `00` to `02` to remove Guile from the party.

### Removing from the roster
Remove Serge from the roster with the following hexadecimal operation.

```
{97 00 80 }
```

The `00` is an index that can be swapped for different characters. As an example, set `00` to `29` to remove Pierre from the roster.