# Leveling

Heroes can increase their stats by leveling up. To level up, a hero must first have accumulated enough experience from their adventures. Once they have done that, they visit the **meditation circle** (coming soon!), and spend a certain number of runes (may be different types) and JEWELs based on their level. They also have the option to use an attunement crystal while leveling up, which will increase the success rate for certain stat increases.

![Hero in summoning circle (work in progress)](https://dfk-hv.b-cdn.net/art-assets/meditation.gif)

Each set of 10 levels has a focus rune associated with it. For levels 1 through 10, that rune is the **Shvās rune**. 

![Shvās rune](https://dfk-hv.b-cdn.net/art-assets/rune.gif)

After reaching level 10, the hero will need an additional rune type (Moksha) to level up further. However, as the hero progresses from level 11 to 20, their Shvās rune cost will decrease as the Moksha cost increases. The Shvās rune cost will stop decreasing once it reaches 1 (meaning a hero will always pay at least 1 rune of a type they have used before). This pattern continues with new rune types every ten levels.

The JEWEL cost of leveling up is 0.1*currentLevel.

The benefit of leveling up is an increase to a hero’s stats. Excluding HP, MP, and Stamina, the game will roll twice for each stat to see if they increase. The first roll will be based on the hero’s **Primary Stat Growth** percentage, which is primarily based on the hero’s class. The second roll is based on the hero’s **Secondary Stat Growth** percentage, which is primarily based on the hero’s subclass. For each successful roll, the stat receives +1 to its value. 

Primary Stat Growth and Secondary Stat Growth are important factors that the player can modify through the use of enhancement stones and summoner bonuses from spending additional Gaia’s Tears during the summoning process (more on this later).

In addition to these two rolls per stat, the player will be given a choice of one stat to grant an extra +1 bonus. But that is not all, players also have a chance to seek Gaia’s blessing for two other stats. Gaia’s blessing has a 50% chance of increasing each of the selected stats.

Stamina has a fixed growth rate for all heroes. It increases by 1 every even level.

Lastly, HP and MP increases are calculated after other stat bonuses are applied. Each class has its own chances for small, regular, or large increases in HP and MP. For example, a Wizard has higher chances for large MP increases, but lower chances for large HP increases.
