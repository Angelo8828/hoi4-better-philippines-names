### Better Philippine Names (Hearts of Iron IV Mod)

#### About

It's a simple mod written for replacing entity names (ex. countries, units, flags, ships, etc.) for the Philippines in the game, Hearts of Iron IV. Currently, this mod is only compatible with **[La Résistance](https://store.steampowered.com/app/1158100/Expansion__Hearts_of_Iron_IV_La_Rsistance)** and **[No Step Back](https://store.steampowered.com/app/1348661/Expansion__Hearts_of_Iron_IV_No_Step_Back)** DLCs.

#### Why?

The names "Ganap Philippines" and "Huk Community of the Philippines" just suck, and those names are unheard of and not existing in Philippine history.

In addition, the generic infantry division name for the Philippines, "1st Philippines Division" also sucks (really Paradox Interactive?).

HOI4 is one of the most amazing strategy games out there but Filipino names just suck in the game, though I can understand it since the Philippines is just a minor nation in the game and real life, especially in WW2.

#### Installation notes
- Download the contents of this repository and place it on your `Documents/Paradox Interactive/Hearts of Iron IV/mod`. If the mod folder is not existing, then you can create it manually.
- Then, install the mod using the launcher or you can also install it manually by inserting the mod's name on `dlc.json` file.

#### Guarantees and limitations

This mod is meant to **replace only entity names. I did not override the vanilla features/mechanics for the game.** For example, the Philippines will still be a democratic puppet of the US in the 1936 and 1939 starts of the game. I also did not change any of the ideas, techs, and equipment count of the Philippines.

It's because, for me, the game's vanilla mechanics are already enjoyable enough. It's just that the names of the Philippine entities in the game suck.

Based on my manual testing, other nations can still be played normally while the mod is active.

I also created the mod in a way that it won't break any future DLC releases for HOI4.

#### Features

##### Country, party and leader name changes
###### Democracy
- Democratic Philippines will retain its name, `Philippines`.
- `Manuel Luis Quezon` will still be the leader of the `Nacionalista Party`.

###### Fascism
- Fascist Phillipines will be called `Pilipinas`. It will have the same flag as the democratic Philippines.
- `Benigno P. Ramos` will be the leader of the `Ganap Party`, having a generic portrait

###### Communism
- Communist Philippines will be called `Bayan`. For its flag, I chose the old neutral/monarchy Philippines flag.
- `Luis M. Taruc` will be the leader of the `Partido Komunista ng Pilipinas`, having a generic portrait too

###### Neutral
- Neutral Philippines will have a new name, `Haring Bayang Katagalugan` and will have a flag based on the Katipunan Magdalo Flag.
- `Artemio Ricarte` will lead the reformed `Katipunan`, also having a generic portrait

<em>
Notes:

I chose the new names of the Philippines according to my interpretation of Philippine History before and during World War II.

Regarding the Fascist Philippines' name, the Second Philippine Republic headed by former President Jose P. Laurel in real life didn't change the country's name. Its actual official name is `Republika ng Pilipinas` but you can notice that it has no official English translation, only Japanese and Spanish ones, since it was a puppet republic by the Japanese in WW2 [(source)](https://en.wikipedia.org/wiki/Second_Philippine_Republic). It's because the Japanese discouraged the usage of the English language and promoted Nihongo instead, while the Philippines was under the Japanese occupation

`Benigno P. Ramos` will be the leader of the Fascist Philippines. In real life, he is the founder of the Sakdalistas and the Makapili [(source)](https://en.wikipedia.org/wiki/Benigno_Ramos). He is a nationalist but somewhat controversial figure in Philippine history because he is a Japanese collaborationist. He led 20,000 members of his party, the Sakdalistas in an uprising in May 1935, but was quickly crushed by the American Insular Government

I chose `Luis M. Taruc` to be the leader of "Partido Komunista ng Pilipinas". He was the leader of [(Hukbalahap)](https://en.wikipedia.org/wiki/Hukbalahap), a guerilla movement formed by Filipino communist to fight the Japanese occupiers. For the communist Philippines, I just chose `Bayan` as its name because I think the communists would choose it to be the Philippines' new name if they would be able to have a chance to rule the archipelago

For the `Haring Bayang Katagalugan` or (Sovereign Tagalog Nation), it has been proposed by Andres Bonifacio to be the name of a new independent Philippines. Aside from Emilio Aguinaldo (which is already a political advider), the only remaining alive veteran officer of the Philippine Revolutionary War of 1896 when WWII broke out is `Gen. Artemio Ricarte`. Ricarte has been living in self-exile in Japan when the war broke out, but came back to the Philippines during the war [(source)](https://en.wikipedia.org/wiki/Artemio_Ricarte)

Additional notes, **we can't use** the name `Maharlika` and the CPP-NPA-NDF flag (for the communist Philippines) because those concepts just became available after WW2.
</em>

##### Division name changes

- The default name for the Philippine infantry divisions will now be `%ordinalNumber% Infantry Division`. It's `%ordinalNumber% Philippines Division` on vanilla. For example, the first infantry division will be called **1st "Tabak" Infantry Division**.

- The default name for the Philippine armored divisions will now be `%ordinalNumber% Armored Division`. It's `%ordinalNumber% Philippines Tank Group` on vanilla. For example, the first armored division will be called **1st "Pambato" Armored Division**.

- The default name for the Philippine marine units will now be `%ordinalNumber% Marine Regiment`. It's `%ordinalNumber% Philippines Marine Div.` on vanilla. For example, the first marine unit will be called **1st Marine Regiment**.

- The default name for the Philippine mountain infantry units will now be `%ordinalNumber% Scout Ranger Regiment`. It's `%ordinalNumber% Philippines Mountain Div.` on vanilla. For example, the first mountain infantry division will be called **1st Scout Ranger Regiment**.

- The default name for the Philippine garrison infantry divisions will now be `%ordinalNumber% Infantry (Res.) Division`. It's `%ordinalNumber% Philippines Div.` on vanilla. For example, the first garrison infantry unit will be called **1st Infantry (Res.) Division**.

##### Ship name changes

- Surface ship names will now default to `RPS - Barkong Pandigma %romanNumeral%`. For example, it will be like **RPS - Barkong Pandigma I**. This rule will apply to all surface ships that will be created by the Philippines (destroyers, cruisers, battleships, and aircraft carriers).

- Submarine names will now default to `RPS - Submarino %romanNumeral%`. For example, it will be like **RPS - Submarino I**.
