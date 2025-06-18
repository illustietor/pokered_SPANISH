# Pokémon Red and Blue [Spanish Translation] [![Build Status][ci-badge]][ci]

This is a translation to spanish of the game texts in the disassembly project of Pokémon Red and Blue.
The purpose of this project is to develop a disassembled version translated into Spanish with the same texts as in the original spanish release.

## Progress
<details>
  <summary>Translations</summary>
| Subjective translation tasks                                                                              | Progress    |
| --------------------------------------------------------------------------------------------------------- | ----------- |
| ~[Pokémon types](data/types/names.asm)~                                                                   | 0 / 16      |
| [Pokédex descriptions](data/pokemon/dex_text.asm)                                                         | 0 / 151     |
| [Pokédex data](data/pokemon/dex_entries.asm) (e.g. Onix = ROCK SNAKE)                                     | 0 / 151     |
| [Item names](data/items/names.asm)                                                                        | 0 / 97     |
| Move names [[1](data/moves/names.asm) ~[2](data/moves/field_move_names.asm)~]                             | 0 / 173    |
| [Place names](data/maps/names.asm)                                                                        | 0 / 53      |
| Default player names [[1](data/player_names.asm) [2](data/player_names_list.asm)]                         | 0 / 6       |

| Large files                                                                                               | Progress    |
| --------------------------------------------------------------------------------------------------------- | ----------- |
| Trainer types [[1](data/trainers/names.asm) [2](data/trainers/name_pointers.asm)] (e.g. Hiker, Youngster) | 0 / 27      |
| [Credits](data/credits/credits_text.asm)                                                                  | ✅         |
| [text_1.asm](data/text/text_1.asm)                                                                        | ✅         |
| [text_2.asm](data/text/text_2.asm)                                                                        | ✅         |
| [text_3.asm](data/text/text_3.asm)                                                                        | ✅         |
| [text_4.asm](data/text/text_4.asm)                                                                        | ✅         |
| [text_5.asm](data/text/text_5.asm)                                                                        | ✅         |
| [text_6.asm](data/text/text_6.asm)                                                                        | ✅         |
| [text_7.asm](data/text/text_7.asm)                                                                        | ✅         |

| Location-specific text                                                                                    | Progress    |
| --------------------------------------------------------------------------------------------------------- | ----------- |
| [AgathasRoom.asm](text/AgathasRoom.asm)                                                                   | 0 / 4       |
| [BikeShop.asm](text/BikeShop.asm)                                                                         | 0 / 11      |
| [BillsHouse.asm](text/BillsHouse.asm)                                                                     | 0 / 8       |
| [BluesHouse.asm](text/BluesHouse.asm)                                                                     | 0 / 7       |
| [BrunosRoom.asm](text/BrunosRoom.asm)                                                                     | 0 / 4       |
| [CeladonChiefHouse.asm](text/CeladonChiefHouse.asm)                                                       | 0 / 3       |
| [CeladonCity.asm](text/CeladonCity.asm)                                                                   | 0 / 20      |
| [CeladonDiner.asm](text/CeladonDiner.asm)                                                                 | 0 / 8       |
| [CeladonGym.asm](text/CeladonGym.asm)                                                                     | 0 / 28      |
| [CeladonHotel.asm](text/CeladonHotel.asm)                                                                 | 0 / 3       |
| [CeladonMansion1F.asm](text/CeladonMansion1F.asm)                                                         | 0 / 5       |
| [CeladonMansion2F.asm](text/CeladonMansion2F.asm)                                                         | 0 / 1       |
| [CeladonMansion3F.asm](text/CeladonMansion3F.asm)                                                         | 0 / 9       |
| [CeladonMansionRoof.asm](text/CeladonMansionRoof.asm)                                                     | 0 / 1       |
| [CeladonMansionRoofHouse.asm](text/CeladonMansionRoofHouse.asm)                                           | 0 / 1       |
| [CeladonMart1F.asm](text/CeladonMart1F.asm)                                                               | 0 / 3       |
| [CeladonMart2F.asm](text/CeladonMart2F.asm)                                                               | 0 / 3       |
| [CeladonMart3F.asm](text/CeladonMart3F.asm)                                                               | 0 / 15      |
| [CeladonMart4F.asm](text/CeladonMart4F.asm)                                                               | 0 / 3       |
| [CeladonMart5F.asm](text/CeladonMart5F.asm)                                                               | 0 / 3       |
| [CeladonMartRoof.asm](text/CeladonMartRoof.asm)                                                           | 0 / 21      |
| [CeladonPokecenter.asm](text/CeladonPokecenter.asm)                                                       | 0 / 2       |
| [CeruleanBadgeHouse.asm](text/CeruleanBadgeHouse.asm)                                                     | 0 / 11      |
| [CeruleanCaveB1F.asm](text/CeruleanCaveB1F.asm)                                                           | 0 / 1       |
| [CeruleanCity.asm](text/CeruleanCity.asm)                                                                 | 0 / 27      |
| [CeruleanGym.asm](text/CeruleanGym.asm)                                                                   | 0 / 14      |
| [CeruleanMart.asm](text/CeruleanMart.asm)                                                                 | 0 / 2       |
| [CeruleanPokecenter.asm](text/CeruleanPokecenter.asm)                                                     | 0 / 2       |
| [CeruleanTradeHouse.asm](text/CeruleanTradeHouse.asm)                                                     | 0 / 1       |
| [CeruleanTrashedHouse.asm](text/CeruleanTrashedHouse.asm)                                                 | 0 / 4       |
| [ChampionsRoom.asm](text/ChampionsRoom.asm)                                                               | 0 / 8       |
| [CinnabarGym.asm](text/CinnabarGym.asm)                                                                   | 0 / 30      |
| [CinnabarIsland.asm](text/CinnabarIsland.asm)                                                             | 0 / 6       |
| [CinnabarLab.asm](text/CinnabarLab.asm)                                                                   | 0 / 5       |
| [CinnabarLabFossilRoom.asm](text/CinnabarLabFossilRoom.asm)                                               | 0 / 8       |
| [CinnabarLabMetronomeRoom.asm](text/CinnabarLabMetronomeRoom.asm)                                         | 0 / 7       |
| [CinnabarLabTradeRoom.asm](text/CinnabarLabTradeRoom.asm)                                                 | 0 / 1       |
| [CinnabarMart.asm](text/CinnabarMart.asm)                                                                 | 0 / 2       |
| [CinnabarPokecenter.asm](text/CinnabarPokecenter.asm)                                                     | 0 / 2       |
| [CopycatsHouse1F.asm](text/CopycatsHouse1F.asm)                                                           | 0 / 3       |
| [CopycatsHouse2F.asm](text/CopycatsHouse2F.asm)                                                           | 0 / 11      |
| [Daycare.asm](text/Daycare.asm)                                                                           | 0 / 8       |
| [Daycare_2.asm](text/Daycare_2.asm)                                                                       | 0 / 7       |
| [DiglettsCaveRoute11.asm](text/DiglettsCaveRoute11.asm)                                                   | 0 / 1       |
| [DiglettsCaveRoute2.asm](text/DiglettsCaveRoute2.asm)                                                     | 0 / 1       |
| [FightingDojo.asm](text/FightingDojo.asm)                                                                 | 0 / 19      |
| [FuchsiaBillsGrandpasHouse.asm](text/FuchsiaBillsGrandpasHouse.asm)                                       | 0 / 3       |
| [FuchsiaCity.asm](text/FuchsiaCity.asm)                                                                   | 0 / 18      |
| [FuchsiaGoodRodHouse.asm](text/FuchsiaGoodRodHouse.asm)                                                   | 0 / 5       |
| [FuchsiaGym.asm](text/FuchsiaGym.asm)                                                                     | 0 / 2       |
| [FuchsiaGym_2.asm](text/FuchsiaGym_2.asm)                                                                 | 0 / 25      |
| [FuchsiaMart.asm](text/FuchsiaMart.asm)                                                                   | 0 / 2       |
| [FuchsiaMeetingRoom.asm](text/FuchsiaMeetingRoom.asm)                                                     | 0 / 3       |
| [FuchsiaPokecenter.asm](text/FuchsiaPokecenter.asm)                                                       | 0 / 2       |
| [GameCorner.asm](text/GameCorner.asm)                                                                     | 0 / 30      |
| [GameCornerPrizeRoom.asm](text/GameCornerPrizeRoom.asm)                                                   | 0 / 2       |
| [HallOfFame.asm](text/HallOfFame.asm)                                                                     | 0 / 1       |
| [IndigoPlateauLobby.asm](text/IndigoPlateauLobby.asm)                                                     | 0 / 2       |
| [LancesRoom.asm](text/LancesRoom.asm)                                                                     | 0 / 3       |
| [LavenderCuboneHouse.asm](text/LavenderCuboneHouse.asm)                                                   | 0 / 3       |
| [LavenderMart.asm](text/LavenderMart.asm)                                                                 | 0 / 3       |
| [LavenderPokecenter.asm](text/LavenderPokecenter.asm)                                                     | 0 / 2       |
| [LavenderTown.asm](text/LavenderTown.asm)                                                                 | 0 / 9       |
| [LoreleisRoom.asm](text/LoreleisRoom.asm)                                                                 | 0 / 4       |
| [MrFujisHouse.asm](text/MrFujisHouse.asm)                                                                 | 0 / 12      |
| [MrPsychicsHouse.asm](text/MrPsychicsHouse.asm)                                                           | 0 / 4       |
| [MtMoon1F.asm](text/MtMoon1F.asm)                                                                         | 0 / 22      |
| [MtMoonB1F.asm](text/MtMoonB1F.asm)                                                                       | 0 / 1       |
| [MtMoonB2F.asm](text/MtMoonB2F.asm)                                                                       | 0 / 21      |
| [MtMoonPokecenter.asm](text/MtMoonPokecenter.asm)                                                         | 0 / 7       |
| [Museum1F.asm](text/Museum1F.asm)                                                                         | 0 / 16      |
| [Museum2F.asm](text/Museum2F.asm)                                                                         | 0 / 7       |
| [NameRatersHouse.asm](text/NameRatersHouse.asm)                                                           | 0 / 7       |
| [OaksLab.asm](text/OaksLab.asm)                                                                           | 0 / 59      |
| [PalletTown.asm](text/PalletTown.asm)                                                                     | 0 / 8       |
| [PewterCity.asm](text/PewterCity.asm)                                                                     | 0 / 16      |
| [PewterGym.asm](text/PewterGym.asm)                                                                       | 0 / 1       |
| [PewterGym_2.asm](text/PewterGym_2.asm)                                                                   | 0 / 15      |
| [PewterMart.asm](text/PewterMart.asm)                                                                     | 0 / 2       |
| [PewterNidoranHouse.asm](text/PewterNidoranHouse.asm)                                                     | 0 / 3       |
| [PewterPokecenter.asm](text/PewterPokecenter.asm)                                                         | 0 / 2       |
| [PewterSpeechHouse.asm](text/PewterSpeechHouse.asm)                                                       | 0 / 2       |
| [PokemonFanClub.asm](text/PokemonFanClub.asm)                                                             | 0 / 16      |
| [PokemonMansion1F.asm](text/PokemonMansion1F.asm)                                                         | 0 / 6       |
| [PokemonMansion2F.asm](text/PokemonMansion2F.asm)                                                         | 0 / 8       |
| [PokemonMansion3F.asm](text/PokemonMansion3F.asm)                                                         | 0 / 7       |
| [PokemonMansionB1F.asm](text/PokemonMansionB1F.asm)                                                       | 0 / 7       |
| [PokemonTower1F.asm](text/PokemonTower1F.asm)                                                             | 0 / 5       |
| [PokemonTower2F.asm](text/PokemonTower2F.asm)                                                             | 0 / 5       |
| [PokemonTower3F.asm](text/PokemonTower3F.asm)                                                             | 0 / 9       |
| [PokemonTower4F.asm](text/PokemonTower4F.asm)                                                             | 0 / 9       |
| [PokemonTower5F.asm](text/PokemonTower5F.asm)                                                             | 0 / 14      |
| [PokemonTower6F.asm](text/PokemonTower6F.asm)                                                             | 0 / 12      |
| [PokemonTower7F.asm](text/PokemonTower7F.asm)                                                             | 0 / 10      |
| [PowerPlant.asm](text/PowerPlant.asm)                                                                     | 0 / 2       |
| [RedsHouse1F.asm](text/RedsHouse1F.asm)                                                                   | 0 / 5       |
| [RockTunnel1F.asm](text/RockTunnel1F.asm)                                                                 | 0 / 22      |
| [RockTunnelB1F.asm](text/RockTunnelB1F.asm)                                                               | 0 / 20      |
| [RockTunnelB1F_2.asm](text/RockTunnelB1F_2.asm)                                                           | 0 / 4       |
| [RockTunnelPokecenter.asm](text/RockTunnelPokecenter.asm)                                                 | 0 / 2       |
| [RocketHideoutB1F.asm](text/RocketHideoutB1F.asm)                                                         | 0 / 15      |
| [RocketHideoutB2F.asm](text/RocketHideoutB2F.asm)                                                         | 0 / 3       |
| [RocketHideoutB3F.asm](text/RocketHideoutB3F.asm)                                                         | 0 / 6       |
| [RocketHideoutB4F.asm](text/RocketHideoutB4F.asm)                                                         | 0 / 12      |
| [RocketHideoutElevator.asm](text/RocketHideoutElevator.asm)                                               | 0 / 1       |
| [Route1.asm](text/Route1.asm)                                                                             | 0 / 6       |
| [Route10.asm](text/Route10.asm)                                                                           | 0 / 21      |
| [Route11.asm](text/Route11.asm)                                                                           | 0 / 25      |
| [Route11Gate1F.asm](text/Route11Gate1F.asm)                                                               | 0 / 1       |
| [Route11Gate2F.asm](text/Route11Gate2F.asm)                                                               | 0 / 4       |
| [Route11_2.asm](text/Route11_2.asm)                                                                       | 0 / 6       |
| [Route12.asm](text/Route12.asm)                                                                           | 0 / 26      |
| [Route12Gate1F.asm](text/Route12Gate1F.asm)                                                               | 0 / 1       |
| [Route12Gate2F.asm](text/Route12Gate2F.asm)                                                               | 0 / 6       |
| [Route12SuperRodHouse.asm](text/Route12SuperRodHouse.asm)                                                 | 0 / 6       |
| [Route13.asm](text/Route13.asm)                                                                           | 0 / 33      |
| [Route14.asm](text/Route14.asm)                                                                           | 0 / 31      |
| [Route15.asm](text/Route15.asm)                                                                           | 0 / 31      |
| [Route15Gate1F.asm](text/Route15Gate1F.asm)                                                               | 0 / 1       |
| [Route15Gate2F.asm](text/Route15Gate2F.asm)                                                               | 0 / 2       |
| [Route16.asm](text/Route16.asm)                                                                           | 0 / 23      |
| [Route16FlyHouse.asm](text/Route16FlyHouse.asm)                                                           | 0 / 5       |
| [Route16Gate1F.asm](text/Route16Gate1F.asm)                                                               | 0 / 4       |
| [Route16Gate2F.asm](text/Route16Gate2F.asm)                                                               | 0 / 4       |
| [Route17.asm](text/Route17.asm)                                                                           | 0 / 36      |
| [Route18.asm](text/Route18.asm)                                                                           | 0 / 11      |
| [Route18Gate1F.asm](text/Route18Gate1F.asm)                                                               | 0 / 3       |
| [Route18Gate2F.asm](text/Route18Gate2F.asm)                                                               | 0 / 2       |
| [Route19.asm](text/Route19.asm)                                                                           | 0 / 31      |
| [Route2.asm](text/Route2.asm)                                                                             | 0 / 2       |
| [Route20.asm](text/Route20.asm)                                                                           | 0 / 32      |
| [Route21.asm](text/Route21.asm)                                                                           | 0 / 27      |
| [Route22.asm](text/Route22.asm)                                                                           | 0 / 9       |
| [Route22Gate.asm](text/Route22Gate.asm)                                                                   | 0 / 3       |
| [Route23.asm](text/Route23.asm)                                                                           | 0 / 4       |
| [Route24.asm](text/Route24.asm)                                                                           | 0 / 8       |
| [Route24_2.asm](text/Route24_2.asm)                                                                       | 0 / 17      |
| [Route25.asm](text/Route25.asm)                                                                           | 0 / 28      |
| [Route2Gate.asm](text/Route2Gate.asm)                                                                     | 0 / 2       |
| [Route2TradeHouse.asm](text/Route2TradeHouse.asm)                                                         | 0 / 1       |
| [Route3.asm](text/Route3.asm)                                                                             | 0 / 26      |
| [Route4.asm](text/Route4.asm)                                                                             | 0 / 6       |
| [Route5.asm](text/Route5.asm)                                                                             | 0 / 1       |
| [Route6.asm](text/Route6.asm)                                                                             | 0 / 18      |
| [Route7.asm](text/Route7.asm)                                                                             | 0 / 1       |
| [Route8.asm](text/Route8.asm)                                                                             | 0 / 28      |
| [Route9.asm](text/Route9.asm)                                                                             | 0 / 28      |
| [SSAnne1F.asm](text/SSAnne1F.asm)                                                                         | 0 / 2       |
| [SSAnne1FRooms.asm](text/SSAnne1FRooms.asm)                                                               | 0 / 18      |
| [SSAnne2F.asm](text/SSAnne2F.asm)                                                                         | 0 / 5       |
| [SSAnne2FRooms.asm](text/SSAnne2FRooms.asm)                                                               | 0 / 19      |
| [SSAnne3F.asm](text/SSAnne3F.asm)                                                                         | 0 / 1       |
| [SSAnneB1FRooms.asm](text/SSAnneB1FRooms.asm)                                                             | 0 / 20      |
| [SSAnneBow.asm](text/SSAnneBow.asm)                                                                       | 0 / 9       |
| [SSAnneCaptainsRoom.asm](text/SSAnneCaptainsRoom.asm)                                                     | 0 / 7       |
| [SSAnneKitchen.asm](text/SSAnneKitchen.asm)                                                               | 0 / 10      |
| [SafariZoneCenter.asm](text/SafariZoneCenter.asm)                                                         | 0 / 2       |
| [SafariZoneCenterRestHouse.asm](text/SafariZoneCenterRestHouse.asm)                                       | 0 / 2       |
| [SafariZoneEast.asm](text/SafariZoneEast.asm)                                                             | 0 / 3       |
| [SafariZoneEastRestHouse.asm](text/SafariZoneEastRestHouse.asm)                                           | 0 / 3       |
| [SafariZoneGate.asm](text/SafariZoneGate.asm)                                                             | 0 / 13      |
| [SafariZoneNorth.asm](text/SafariZoneNorth.asm)                                                           | 0 / 5       |
| [SafariZoneNorthRestHouse.asm](text/SafariZoneNorthRestHouse.asm)                                         | 0 / 3       |
| [SafariZoneSecretHouse.asm](text/SafariZoneSecretHouse.asm)                                               | 0 / 4       |
| [SafariZoneWest.asm](text/SafariZoneWest.asm)                                                             | 0 / 4       |
| [SafariZoneWestRestHouse.asm](text/SafariZoneWestRestHouse.asm)                                           | 0 / 3       |
| [SaffronCity.asm](text/SaffronCity.asm)                                                                   | 0 / 23      |
| [SaffronGates.asm](text/SaffronGates.asm)                                                                 | 0 / 4       |
| [SaffronGym.asm](text/SaffronGym.asm)                                                                     | 0 / 30      |
| [SaffronMart.asm](text/SaffronMart.asm)                                                                   | 0 / 2       |
| [SaffronPidgeyHouse.asm](text/SaffronPidgeyHouse.asm)                                                     | 0 / 4       |
| [SaffronPokecenter.asm](text/SaffronPokecenter.asm)                                                       | 0 / 2       |
| [SeafoamIslandsB4F.asm](text/SeafoamIslandsB4F.asm)                                                       | 0 / 3       |
| [SilphCo10F.asm](text/SilphCo10F.asm)                                                                     | 0 / 8       |
| [SilphCo11F.asm](text/SilphCo11F.asm)                                                                     | 0 / 15      |
| [SilphCo1F.asm](text/SilphCo1F.asm)                                                                       | 0 / 1       |
| [SilphCo2F.asm](text/SilphCo2F.asm)                                                                       | 0 / 16      |
| [SilphCo3F.asm](text/SilphCo3F.asm)                                                                       | 0 / 8       |
| [SilphCo4F.asm](text/SilphCo4F.asm)                                                                       | 0 / 11      |
| [SilphCo5F.asm](text/SilphCo5F.asm)                                                                       | 0 / 9       |
| [SilphCo5F_2.asm](text/SilphCo5F_2.asm)                                                                   | 0 / 8       |
| [SilphCo6F.asm](text/SilphCo6F.asm)                                                                       | 0 / 19      |
| [SilphCo7F.asm](text/SilphCo7F.asm)                                                                       | 0 / 27      |
| [SilphCo8F.asm](text/SilphCo8F.asm)                                                                       | 0 / 11      |
| [SilphCo9F.asm](text/SilphCo9F.asm)                                                                       | 0 / 12      |
| [UndergroundPathRoute6.asm](text/UndergroundPathRoute6.asm)                                               | 0 / 1       |
| [UndergroundPathRoute7.asm](text/UndergroundPathRoute7.asm)                                               | 0 / 1       |
| [UndergroundPathRoute7Copy.asm](text/UndergroundPathRoute7Copy.asm)                                       | 0 / 4       |
| [UndergroundPathRoute8.asm](text/UndergroundPathRoute8.asm)                                               | 0 / 1       |
| [VermilionCity.asm](text/VermilionCity.asm)                                                               | 0 / 17      |
| [VermilionDock.asm](text/VermilionDock.asm)                                                               | 0 / 1       |
| [VermilionGym.asm](text/VermilionGym.asm)                                                                 | 0 / 1       |
| [VermilionGym_2.asm](text/VermilionGym_2.asm)                                                             | 0 / 17      |
| [VermilionMart.asm](text/VermilionMart.asm)                                                               | 0 / 2       |
| [VermilionOldRodHouse.asm](text/VermilionOldRodHouse.asm)                                                 | 0 / 6       |
| [VermilionPidgeyHouse.asm](text/VermilionPidgeyHouse.asm)                                                 | 0 / 3       |
| [VermilionPokecenter.asm](text/VermilionPokecenter.asm)                                                   | 0 / 2       |
| [VictoryRoad1F.asm](text/VictoryRoad1F.asm)                                                               | 0 / 6       |
| [VictoryRoad2F.asm](text/VictoryRoad2F.asm)                                                               | 0 / 16      |
| [VictoryRoad3F.asm](text/VictoryRoad3F.asm)                                                               | 0 / 12      |
| [ViridianCity.asm](text/ViridianCity.asm)                                                                 | 0 / 22      |
| [ViridianForest.asm](text/ViridianForest.asm)                                                             | 0 / 17      |
| [ViridianForestNorthGate.asm](text/ViridianForestNorthGate.asm)                                           | 0 / 2       |
| [ViridianForestSouthGate.asm](text/ViridianForestSouthGate.asm)                                           | 0 / 2       |
| [ViridianGym.asm](text/ViridianGym.asm)                                                                   | 0 / 33      |
| [ViridianMart.asm](text/ViridianMart.asm)                                                                 | 0 / 5       |
| [ViridianNicknameHouse.asm](text/ViridianNicknameHouse.asm)                                               | 0 / 4       |
| [ViridianPokecenter.asm](text/ViridianPokecenter.asm)                                                     | 0 / 2       |
| [ViridianSchoolHouse.asm](text/ViridianSchoolHouse.asm)                                                   | 0 / 2       |
| [WardensHouse.asm](text/WardensHouse.asm)                                                                 | 0 / 11      |

| Small files                                                                                               | Progress    |
| --------------------------------------------------------------------------------------------------------- | ----------- |
| [constants/item_constants.asm](constants/item_constants.asm)                                              | 0 / 4       |
| [data/battle/stat_names.asm](data/battle/stat_names.asm)                                                  | 0 / 6       |
| [data/events/prizes.asm](data/events/prizes.asm)                                                          | ✅         |
| [data/events/trades.asm](data/events/trades.asm)                                                          | ✅         |
| [data/moves/tmhm_moves.asm](data/moves/tmhm_moves.asm)                                                    | 0 / 4       |
| [data/text_boxes.asm](data/text_boxes.asm)                                                                | ✅         |
| [data/yes_no_menu_strings.asm](data/yes_no_menu_strings.asm)                                              | ✅         |
| [engine/battle/core.asm](engine/battle/core.asm)                                                          | 0 / 5       |
| [engine/battle/end_of_battle.asm](engine/battle/end_of_battle.asm)                                        | 0 / 3       |
| [engine/debug/debug_menu.asm](engine/debug/debug_menu.asm)                                                | 0 / 4       |
| [engine/events/diploma.asm](engine/events/diploma.asm)                                                    | ✅         |
| [engine/events/evolve_trade.asm](engine/events/evolve_trade.asm)                                          | 0 / 1       |
| [engine/events/hidden_objects/bills_house_pc.asm](engine/events/hidden_objects/bills_house_pc.asm)        | 0 / 5       |
| [engine/events/hidden_objects/school_blackboard.asm](engine/events/hidden_objects/school_blackboard.asm)  | 0 / 10      |
| [engine/events/prize_menu.asm](engine/events/prize_menu.asm)                                              | ✅         |
| [engine/events/vending_machine.asm](engine/events/vending_machine.asm)                                    | ✅         |
| [engine/items/item_effects.asm](engine/items/item_effects.asm)                                            | 0 / 17      |
| [engine/items/town_map.asm](engine/items/town_map.asm)                                                    | ✅         |
| [engine/link/cable_club.asm](engine/link/cable_club.asm)                                                  | ✅         |
| [engine/link/print_waiting_text.asm](engine/link/print_waiting_text.asm)                                  | ✅         |
| [engine/menus/draw_start_menu.asm](engine/menus/draw_start_menu.asm)                                      | ✅         |
| [engine/menus/league_pc.asm](engine/menus/league_pc.asm)                                                  | ✅         |
| [engine/menus/main_menu.asm](engine/menus/main_menu.asm)                                                  | ✅         |
| [engine/menus/naming_screen.asm](engine/menus/naming_screen.asm)                                          | ✅         |
| [engine/menus/party_menu.asm](engine/menus/party_menu.asm)                                                | ✅         |
| [engine/menus/players_pc.asm](engine/menus/players_pc.asm)                                                | ✅         |
| [engine/menus/pokedex.asm](engine/menus/pokedex.asm)                                                      | ✅         |
| [engine/menus/save.asm](engine/menus/save.asm)                                                            | ✅         |
| [engine/menus/start_sub_menus.asm](engine/menus/start_sub_menus.asm)                                      | ✅         |
| [engine/menus/text_box.asm](engine/menus/text_box.asm)                                                    | ✅         |
| [engine/movie/hall_of_fame.asm](engine/movie/hall_of_fame.asm)                                            | ✅         |
| [engine/movie/oak_speech/oak_speech2.asm](engine/movie/oak_speech/oak_speech2.asm)                        | ✅         |
| [engine/movie/title.asm](engine/movie/title.asm)                                                          | ✅         |
| [engine/movie/trade2.asm](engine/movie/trade2.asm)                                                        | 0 / 1       |
| [engine/overworld/player_state.asm](engine/overworld/player_state.asm)                                    | 0 / 1       |
| [engine/pokemon/bills_pc.asm](engine/pokemon/bills_pc.asm)                                                | ✅         |
| [engine/pokemon/status_ailments.asm](engine/pokemon/status_ailments.asm)                                  | ✅         |
| [engine/pokemon/status_screen.asm](engine/pokemon/status_screen.asm)                                      | ✅         |
| [home/list_menu.asm](home/list_menu.asm)                                                                  | ✅         |
| [home/names.asm](home/names.asm)                                                                          | ✅         |
| [home/pokemon.asm](home/pokemon.asm)                                                                      | 0 / 1       |
| [home/text.asm](home/text.asm)                                                                            | ✅         |
| [scripts/BikeShop.asm](scripts/BikeShop.asm)                                                              | ✅         |
| [scripts/CeladonGym.asm](scripts/CeladonGym.asm)                                                          | ✅         |
| [scripts/CeruleanGym.asm](scripts/CeruleanGym.asm)                                                        | ✅         |
| [scripts/CinnabarGym.asm](scripts/CinnabarGym.asm)                                                        | ✅         |
| [scripts/FuchsiaGym.asm](scripts/FuchsiaGym.asm)                                                          | ✅         |
| [scripts/GameCorner.asm](scripts/GameCorner.asm)                                                          | ✅         |
| [scripts/PewterGym.asm](scripts/PewterGym.asm)                                                            | ✅         |
| [scripts/Route23.asm](scripts/Route23.asm)                                                                | ✅         |
| [scripts/SaffronGym.asm](scripts/SaffronGym.asm)                                                          | ✅         |
| [scripts/VermilionGym.asm](scripts/VermilionGym.asm)                                                      | ✅         |
| [scripts/ViridianGym.asm](scripts/ViridianGym.asm)                                                        | ✅         |
</details

To set up the repository, see [**INSTALL.md**](INSTALL.md).

## See also

- [**Wiki**][wiki] (includes [tutorials][tutorials])
- [**Symbols**][symbols]
- [**Tools**][tools]

You can find us on [Discord (pret, #pokered)](https://discord.gg/d5dubZ3).

For other pret projects, see [pret.github.io](https://pret.github.io/).

[wiki]: https://github.com/pret/pokered/wiki
[tutorials]: https://github.com/pret/pokered/wiki/Tutorials
[symbols]: https://github.com/pret/pokered/tree/symbols
[tools]: https://github.com/pret/gb-asm-tools
[ci]: https://github.com/pret/pokered/actions
[ci-badge]: https://github.com/pret/pokered/actions/workflows/main.yml/badge.svg