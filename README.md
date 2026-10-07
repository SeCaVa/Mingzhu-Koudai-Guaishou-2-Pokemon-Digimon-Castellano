# Mingzhu Koudai Guaishou 2 (Pokémon + Digimon) — Castellano

Traducción no oficial al **castellano de España** del bootleg chino de Game Boy Color
*Mingzhu Koudai Guaishou 2* (明珠口袋怪獸2), conocido como **Digimon D-4**: una mezcla de Digimon y Pokémon
con motor propio y texto en chino tradicional.

> Este repositorio **no contiene la ROM**. Solo el parche en formato BPS: necesitas tu propia copia del juego original.

## Qué está traducido

- Menús, batalla, objetos, ataques, lugares y pantalla de estado.
- Toda la historia y los diálogos de los cinco protagonistas (versión masculina y femenina de los rótulos).
- Nombres de Pokémon con su nombre oficial en español y de Digimon con el nombre usado en España.
- Fuente propia proporcional (no comercial), con tildes, `¿` `¡` y `ñ`.
- Logo del título.

## Cómo aplicar el parche

1. Consigue la ROM original (2 MB, MBC5):

   | Dato | Valor |
   |---|---|
   | Nombre | `Mingzhu Koudai Guaishou 2 (Unlicensed, Chinese) (CBA060) [Fixed-2].gbc` |
   | CRC32 | `F1F794DA` |
   | SHA-1 | `1d866a8bcab96c2a957c5ffdc4f4028cbda7827d` |

2. Aplica `Mingzhu-Koudai-Guaishou-2-Castellano.bps` con [Floating IPS](https://github.com/Alcaro/Flips), [RomPatcher.js](https://www.marcrobledo.com/RomPatcher.js/) o cualquier otra herramienta compatible con BPS.
3. El resultado es una ROM de **4 MB** (la ampliación guarda los glifos nuevos) con CRC32 `F9132EC7`.

Probado en **mGBA** y **PyBoy**. En flashcarts o emuladores muy antiguos que no soporten ROM de 4 MB con MBC5 puede no funcionar.

## Estado

Versión jugable. Revisadas: menús, selección de personaje, historia, diálogos, batalla, estado, objetos, evolución y final.
Si encuentras texto raro, cortado o con símbolos extraños, abre un *issue* con una captura.

## Cambios

**7-oct-2026 (revisión)**
- Diálogos de las bayas con los mismos nombres que los objetos (Baya Roja, Azul, Lima, Plata y Oro) y concordancia de género corregida.
- Frases corregidas o más naturales en varios diálogos, incluida una variante neutra para las protagonistas.
- DemiDevimon y Pumpkinmon con el nombre usado en España (antes Picodevimon y Pumpmon).
- Coherencia entre combate, objetos y diálogos: Tajo Ala Sombra, Arm. Prot., Montes File.
- Gráfico de victoria: «VICTORIA» en una sola línea y centrado.
- Última frase del final más fiel al original.

## Créditos

- Traducción, herramientas e ingeniería inversa del formato de texto: SeCaVa, con ayuda de Claude (Anthropic).
- Juego original: Mingzhu (bootleg sin licencia). Pokémon y Digimon son marcas de sus respectivos dueños.
