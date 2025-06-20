# Pokémon Red and Blue [Spanish Translation] [![Build Status][ci-badge]][ci]

This is a translation to spanish of the game texts in the disassembly project of Pokémon Red and Blue.
The purpose of this project is to develop a disassembled version translated into Spanish with the same texts as in the original spanish release.

## Progress
<details>
<summary>Translations</summary>

| Subjective translation tasks                                                                              | Progress    |
| --------------------------------------------------------------------------------------------------------- | ----------- |
| ~[Pokémon types](data/types/names.asm)~                                                                   | ✅         |
| [Pokédex descriptions](data/pokemon/dex_text.asm)                                                         | ✅         |
| [Pokédex data](data/pokemon/dex_entries.asm) (e.g. Onix = ROCK SNAKE)                                     | ✅         |
| [Item names](data/items/names.asm)                                                                        | ✅         |
| Move names [[1](data/moves/names.asm) ~[2](data/moves/field_move_names.asm)~]                             | ✅         |
| [Place names](data/maps/names.asm)                                                                        | ✅         |
| Default player names [[1](data/player_names.asm) [2](data/player_names_list.asm)]                         | ✅         |

| Large files                                                                                               | Progress    |
| --------------------------------------------------------------------------------------------------------- | ----------- |
| Trainer types [[1](data/trainers/names.asm) [2](data/trainers/name_pointers.asm)] (e.g. Hiker, Youngster) | ✅         |
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
| [AgathasRoom.asm](text/AgathasRoom.asm)                                                                   | ✅       |
| [BikeShop.asm](text/BikeShop.asm)                                                                         | ✅      |
| [BillsHouse.asm](text/BillsHouse.asm)                                                                     | ✅       |
| [BluesHouse.asm](text/BluesHouse.asm)                                                                     | ✅       |
| [BrunosRoom.asm](text/BrunosRoom.asm)                                                                     | ✅       |
| [CeladonChiefHouse.asm](text/CeladonChiefHouse.asm)                                                       | ✅       |
| [CeladonCity.asm](text/CeladonCity.asm)                                                                   | ✅     |
| [CeladonDiner.asm](text/CeladonDiner.asm)                                                                 | ✅       |
| [CeladonGym.asm](text/CeladonGym.asm)                                                                     | ✅      |
| [CeladonHotel.asm](text/CeladonHotel.asm)                                                                 | ✅       |
| [CeladonMansion1F.asm](text/CeladonMansion1F.asm)                                                         | ✅       |
| [CeladonMansion2F.asm](text/CeladonMansion2F.asm)                                                         | ✅       |
| [CeladonMansion3F.asm](text/CeladonMansion3F.asm)                                                         | ✅       |
| [CeladonMansionRoof.asm](text/CeladonMansionRoof.asm)                                                     | ✅       |
| [CeladonMansionRoofHouse.asm](text/CeladonMansionRoofHouse.asm)                                           | ✅       |
| [CeladonMart1F.asm](text/CeladonMart1F.asm)                                                               | ✅       |
| [CeladonMart2F.asm](text/CeladonMart2F.asm)                                                               | ✅       |
| [CeladonMart3F.asm](text/CeladonMart3F.asm)                                                               | ✅      |
| [CeladonMart4F.asm](text/CeladonMart4F.asm)                                                               | ✅       |
| [CeladonMart5F.asm](text/CeladonMart5F.asm)                                                               | ✅       |
| [CeladonMartRoof.asm](text/CeladonMartRoof.asm)                                                           | ✅      |
| [CeladonPokecenter.asm](text/CeladonPokecenter.asm)                                                       | ✅ |
| [CeruleanBadgeHouse.asm](text/CeruleanBadgeHouse.asm)                                                     | ✅ |
| [CeruleanCaveB1F.asm](text/CeruleanCaveB1F.asm)                                                           | ✅ |
| [CeruleanCity.asm](text/CeruleanCity.asm)                                                                 | ✅ |
| [CeruleanGym.asm](text/CeruleanGym.asm)                                                                   | ✅ |
| [CeruleanMart.asm](text/CeruleanMart.asm)                                                                 | ✅ |
| [CeruleanPokecenter.asm](text/CeruleanPokecenter.asm)                                                     | ✅ |
| [CeruleanTradeHouse.asm](text/CeruleanTradeHouse.asm)                                                     | ✅ |
| [CeruleanTrashedHouse.asm](text/CeruleanTrashedHouse.asm)                                                 | ✅ |
| [ChampionsRoom.asm](text/ChampionsRoom.asm)                                                               | ✅ |
| [CinnabarGym.asm](text/CinnabarGym.asm)                                                                   | ✅ |
| [CinnabarIsland.asm](text/CinnabarIsland.asm)                                                             | ✅ |
| [CinnabarLab.asm](text/CinnabarLab.asm)                                                                   | ✅ |
| [CinnabarLabFossilRoom.asm](text/CinnabarLabFossilRoom.asm)                                               | ✅ |
| [CinnabarLabMetronomeRoom.asm](text/CinnabarLabMetronomeRoom.asm)                                         | ✅ |
| [CinnabarLabTradeRoom.asm](text/CinnabarLabTradeRoom.asm)                                                 | ✅ |
| [CinnabarMart.asm](text/CinnabarMart.asm)                                                                 | ✅ |
| [CinnabarPokecenter.asm](text/CinnabarPokecenter.asm)                                                     | ✅ |
| [CopycatsHouse1F.asm](text/CopycatsHouse1F.asm)                                                           | ✅ |
| [CopycatsHouse2F.asm](text/CopycatsHouse2F.asm)                                                           | ✅ |
| [Daycare.asm](text/Daycare.asm)                                                                           | ✅ |
| [Daycare_2.asm](text/Daycare_2.asm)                                                                       | ✅ |
| [DiglettsCaveRoute11.asm](text/DiglettsCaveRoute11.asm)                                                   | ✅ |
| [DiglettsCaveRoute2.asm](text/DiglettsCaveRoute2.asm)                                                     | ✅ |
| [FightingDojo.asm](text/FightingDojo.asm)                                                                 | ✅ |
| [FuchsiaBillsGrandpasHouse.asm](text/FuchsiaBillsGrandpasHouse.asm)                                       | ✅ |
| [FuchsiaCity.asm](text/FuchsiaCity.asm)                                                                   | ✅ |
| [FuchsiaGoodRodHouse.asm](text/FuchsiaGoodRodHouse.asm)                                                   | ✅ |
| [FuchsiaGym.asm](text/FuchsiaGym.asm)                                                                     | ✅ |
| [FuchsiaGym_2.asm](text/FuchsiaGym_2.asm)                                                                 | ✅ |
| [FuchsiaMart.asm](text/FuchsiaMart.asm)                                                                   | ✅ |
| [FuchsiaMeetingRoom.asm](text/FuchsiaMeetingRoom.asm)                                                     | ✅ |
| [FuchsiaPokecenter.asm](text/FuchsiaPokecenter.asm)                                                       | ✅ |
| [GameCorner.asm](text/GameCorner.asm)                                                                     | ✅ |
| [GameCornerPrizeRoom.asm](text/GameCornerPrizeRoom.asm)                                                   | ✅ |
| [HallOfFame.asm](text/HallOfFame.asm)                                                                     | ✅ |
| [IndigoPlateauLobby.asm](text/IndigoPlateauLobby.asm)                                                     | ✅ |
| [LancesRoom.asm](text/LancesRoom.asm)                                                                     | ✅ |
| [LavenderCuboneHouse.asm](text/LavenderCuboneHouse.asm)                                                   | ✅ |
| [LavenderMart.asm](text/LavenderMart.asm)                                                                 | ✅ |
| [LavenderPokecenter.asm](text/LavenderPokecenter.asm)                                                     | ✅ |
| [LavenderTown.asm](text/LavenderTown.asm)                                                                 | ✅ |
| [LoreleisRoom.asm](text/LoreleisRoom.asm)                                                                 | ✅ |
| [MrFujisHouse.asm](text/MrFujisHouse.asm)                                                                 | ✅ |
| [MrPsychicsHouse.asm](text/MrPsychicsHouse.asm)                                                           | ✅ |
| [MtMoon1F.asm](text/MtMoon1F.asm)                                                                         | ✅ |
| [MtMoonB1F.asm](text/MtMoonB1F.asm)                                                                       | ✅ |
| [MtMoonB2F.asm](text/MtMoonB2F.asm)                                                                       | ✅ |
| [MtMoonPokecenter.asm](text/MtMoonPokecenter.asm)                                                         | ✅ |
| [Museum1F.asm](text/Museum1F.asm)                                                                         | ✅ |
| [Museum2F.asm](text/Museum2F.asm)                                                                         | ✅ |
| [NameRatersHouse.asm](text/NameRatersHouse.asm)                                                           | ✅ |
| [OaksLab.asm](text/OaksLab.asm)                                                                           | ✅ |
| [PalletTown.asm](text/PalletTown.asm)                                                                     | ✅ |
| [PewterCity.asm](text/PewterCity.asm)                                                                     | ✅ |
| [PewterGym.asm](text/PewterGym.asm)                                                                       | ✅ |
| [PewterGym_2.asm](text/PewterGym_2.asm)                                                                   | ✅ |
| [PewterMart.asm](text/PewterMart.asm)                                                                     | ✅ |
| [PewterNidoranHouse.asm](text/PewterNidoranHouse.asm)                                                     | ✅ |
| [PewterPokecenter.asm](text/PewterPokecenter.asm)                                                         | ✅ |
| [PewterSpeechHouse.asm](text/PewterSpeechHouse.asm)                                                       | ✅ |
| [PokemonFanClub.asm](text/PokemonFanClub.asm)                                                             | ✅ |
| [PokemonMansion1F.asm](text/PokemonMansion1F.asm)                                                         | ✅ |
| [PokemonMansion2F.asm](text/PokemonMansion2F.asm)                                                         | ✅ |
| [PokemonMansion3F.asm](text/PokemonMansion3F.asm)                                                         | ✅ |
| [PokemonMansionB1F.asm](text/PokemonMansionB1F.asm)                                                       | ✅ |
| [PokemonTower1F.asm](text/PokemonTower1F.asm)                                                             | ✅ |
| [PokemonTower2F.asm](text/PokemonTower2F.asm)                                                             | ✅ |
| [PokemonTower3F.asm](text/PokemonTower3F.asm)                                                             | ✅ |
| [PokemonTower4F.asm](text/PokemonTower4F.asm)                                                             | ✅ |
| [PokemonTower5F.asm](text/PokemonTower5F.asm)                                                             | ✅ |
| [PokemonTower6F.asm](text/PokemonTower6F.asm)                                                             | ✅ |
| [PokemonTower7F.asm](text/PokemonTower7F.asm)                                                             | ✅ |
| [PowerPlant.asm](text/PowerPlant.asm)                                                                     | ✅ |
| [RedsHouse1F.asm](text/RedsHouse1F.asm)                                                                   | ✅ |
| [RockTunnel1F.asm](text/RockTunnel1F.asm)                                                                 | ✅ |
| [RockTunnelB1F.asm](text/RockTunnelB1F.asm)                                                               | ✅ |
| [RockTunnelB1F_2.asm](text/RockTunnelB1F_2.asm)                                                           | ✅ |
| [RockTunnelPokecenter.asm](text/RockTunnelPokecenter.asm)                                                 | ✅ |
| [RocketHideoutB1F.asm](text/RocketHideoutB1F.asm)                                                         | ✅ |
| [RocketHideoutB2F.asm](text/RocketHideoutB2F.asm)                                                         | ✅ |
| [RocketHideoutB3F.asm](text/RocketHideoutB3F.asm)                                                         | ✅ |
| [RocketHideoutB4F.asm](text/RocketHideoutB4F.asm)                                                         | ✅ |
| [RocketHideoutElevator.asm](text/RocketHideoutElevator.asm)                                               | ✅ |
| [Route1.asm](text/Route1.asm)                                                                             | ✅ |
| [Route10.asm](text/Route10.asm)                                                                           | ✅ |
| [Route11.asm](text/Route11.asm)                                                                           | ✅ |
| [Route11Gate1F.asm](text/Route11Gate1F.asm)                                                               | ✅ |
| [Route11Gate2F.asm](text/Route11Gate2F.asm)                                                               | ✅ |
| [Route11_2.asm](text/Route11_2.asm)                                                                       | ✅ |
| [Route12.asm](text/Route12.asm)                                                                           | ✅ |
| [Route12Gate1F.asm](text/Route12Gate1F.asm)                                                               | ✅ |
| [Route12Gate2F.asm](text/Route12Gate2F.asm)                                                               | ✅ |
| [Route12SuperRodHouse.asm](text/Route12SuperRodHouse.asm)                                                 | ✅ |
| [Route13.asm](text/Route13.asm)                                                                           | ✅ |
| [Route14.asm](text/Route14.asm)                                                                           | ✅ |
| [Route15.asm](text/Route15.asm)                                                                           | ✅ |
| [Route15Gate1F.asm](text/Route15Gate1F.asm)                                                               | ✅ |
| [Route15Gate2F.asm](text/Route15Gate2F.asm)                                                               | ✅ |
| [Route16.asm](text/Route16.asm)                                                                           | ✅ |
| [Route16FlyHouse.asm](text/Route16FlyHouse.asm)                                                           | ✅ |
| [Route16Gate1F.asm](text/Route16Gate1F.asm)                                                               | ✅ |
| [Route16Gate2F.asm](text/Route16Gate2F.asm)                                                               | ✅ |
| [Route17.asm](text/Route17.asm)                                                                           | ✅ |
| [Route18.asm](text/Route18.asm)                                                                           | ✅ |
| [Route18Gate1F.asm](text/Route18Gate1F.asm)                                                               | ✅ |
| [Route18Gate2F.asm](text/Route18Gate2F.asm)                                                               | ✅ |
| [Route19.asm](text/Route19.asm)                                                                           | ✅ |
| [Route2.asm](text/Route2.asm)                                                                             | ✅ |
| [Route20.asm](text/Route20.asm)                                                                           | ✅ |
| [Route21.asm](text/Route21.asm)                                                                           | ✅ |
| [Route22.asm](text/Route22.asm)                                                                           | ✅ |
| [Route22Gate.asm](text/Route22Gate.asm)                                                                   | ✅ |
| [Route23.asm](text/Route23.asm)                                                                           | ✅ |
| [Route24.asm](text/Route24.asm)                                                                           | ✅ |
| [Route24_2.asm](text/Route24_2.asm)                                                                       | ✅ |
| [Route25.asm](text/Route25.asm)                                                                           | ✅ |
| [Route2Gate.asm](text/Route2Gate.asm)                                                                     | ✅ |
| [Route2TradeHouse.asm](text/Route2TradeHouse.asm)                                                         | ✅ |
| [Route3.asm](text/Route3.asm)                                                                             | ✅ |
| [Route4.asm](text/Route4.asm)                                                                             | ✅ |
| [Route5.asm](text/Route5.asm)                                                                             | ✅ |
| [Route6.asm](text/Route6.asm)                                                                             | ✅ |
| [Route7.asm](text/Route7.asm)                                                                             | ✅ |
| [Route8.asm](text/Route8.asm)                                                                             | ✅ |
| [Route9.asm](text/Route9.asm)                                                                             | ✅ |
| [SSAnne1F.asm](text/SSAnne1F.asm)                                                                         | ✅ |
| [SSAnne1FRooms.asm](text/SSAnne1FRooms.asm)                                                               | ✅ |
| [SSAnne2F.asm](text/SSAnne2F.asm)                                                                         | ✅ |
| [SSAnne2FRooms.asm](text/SSAnne2FRooms.asm)                                                               | ✅ |
| [SSAnne3F.asm](text/SSAnne3F.asm)                                                                         | ✅ |
| [SSAnneB1FRooms.asm](text/SSAnneB1FRooms.asm)                                                             | ✅ |
| [SSAnneBow.asm](text/SSAnneBow.asm)                                                                       | ✅ |
| [SSAnneCaptainsRoom.asm](text/SSAnneCaptainsRoom.asm)                                                     | ✅ |
| [SSAnneKitchen.asm](text/SSAnneKitchen.asm)                                                               | ✅ |
| [SafariZoneCenter.asm](text/SafariZoneCenter.asm)                                                         | ✅ |
| [SafariZoneCenterRestHouse.asm](text/SafariZoneCenterRestHouse.asm)                                       | ✅ |
| [SafariZoneEast.asm](text/SafariZoneEast.asm)                                                             | ✅ |
| [SafariZoneEastRestHouse.asm](text/SafariZoneEastRestHouse.asm)                                           | ✅ |
| [SafariZoneGate.asm](text/SafariZoneGate.asm)                                                             | ✅ |
| [SafariZoneNorth.asm](text/SafariZoneNorth.asm)                                                           | ✅ |
| [SafariZoneNorthRestHouse.asm](text/SafariZoneNorthRestHouse.asm)                                         | ✅ |
| [SafariZoneSecretHouse.asm](text/SafariZoneSecretHouse.asm)                                               | ✅ |
| [SafariZoneWest.asm](text/SafariZoneWest.asm)                                                             | ✅ |
| [SafariZoneWestRestHouse.asm](text/SafariZoneWestRestHouse.asm)                                           | ✅ |
| [SaffronCity.asm](text/SaffronCity.asm)                                                                   | ✅ |
| [SaffronGates.asm](text/SaffronGates.asm)                                                                 | ✅ |
| [SaffronGym.asm](text/SaffronGym.asm)                                                                     | ✅ |
| [SaffronMart.asm](text/SaffronMart.asm)                                                                   | ✅ |
| [SaffronPidgeyHouse.asm](text/SaffronPidgeyHouse.asm)                                                     | ✅ |
| [SaffronPokecenter.asm](text/SaffronPokecenter.asm)                                                       | ✅ |
| [SeafoamIslandsB4F.asm](text/SeafoamIslandsB4F.asm)                                                       | ✅ |
| [SilphCo10F.asm](text/SilphCo10F.asm)                                                                     | ✅ |
| [SilphCo11F.asm](text/SilphCo11F.asm)                                                                     | ✅ |
| [SilphCo1F.asm](text/SilphCo1F.asm)                                                                       | ✅ |
| [SilphCo2F.asm](text/SilphCo2F.asm)                                                                       | ✅ |
| [SilphCo3F.asm](text/SilphCo3F.asm)                                                                       | ✅ |
| [SilphCo4F.asm](text/SilphCo4F.asm)                                                                       | ✅ |
| [SilphCo5F.asm](text/SilphCo5F.asm)                                                                       | ✅ |
| [SilphCo5F_2.asm](text/SilphCo5F_2.asm)                                                                   | ✅ |
| [SilphCo6F.asm](text/SilphCo6F.asm)                                                                       | ✅ |
| [SilphCo7F.asm](text/SilphCo7F.asm)                                                                       | ✅ |
| [SilphCo8F.asm](text/SilphCo8F.asm)                                                                       | ✅ |
| [SilphCo9F.asm](text/SilphCo9F.asm)                                                                       | ✅ |
| [UndergroundPathRoute6.asm](text/UndergroundPathRoute6.asm)                                               | ✅ |
| [UndergroundPathRoute7.asm](text/UndergroundPathRoute7.asm)                                               | ✅ |
| [UndergroundPathRoute7Copy.asm](text/UndergroundPathRoute7Copy.asm)                                       | ✅ |
| [UndergroundPathRoute8.asm](text/UndergroundPathRoute8.asm)                                               | ✅ |
| [VermilionCity.asm](text/VermilionCity.asm)                                                               | ✅ |
| [VermilionDock.asm](text/VermilionDock.asm)                                                               | ✅ |
| [VermilionGym.asm](text/VermilionGym.asm)                                                                 | ✅ |
| [VermilionGym_2.asm](text/VermilionGym_2.asm)                                                             | ✅ |
| [VermilionMart.asm](text/VermilionMart.asm)                                                               | ✅ |
| [VermilionOldRodHouse.asm](text/VermilionOldRodHouse.asm)                                                 | ✅ |
| [VermilionPidgeyHouse.asm](text/VermilionPidgeyHouse.asm)                                                 | ✅ |
| [VermilionPokecenter.asm](text/VermilionPokecenter.asm)                                                   | ✅ |
| [VictoryRoad1F.asm](text/VictoryRoad1F.asm)                                                               | ✅ |
| [VictoryRoad2F.asm](text/VictoryRoad2F.asm)                                                               | ✅ |
| [VictoryRoad3F.asm](text/VictoryRoad3F.asm)                                                               | ✅ |
| [ViridianCity.asm](text/ViridianCity.asm)                                                                 | ✅ |
| [ViridianForest.asm](text/ViridianForest.asm)                                                             | ✅ |
| [ViridianForestNorthGate.asm](text/ViridianForestNorthGate.asm)                                           | ✅ |
| [ViridianForestSouthGate.asm](text/ViridianForestSouthGate.asm)                                           | ✅ |
| [ViridianGym.asm](text/ViridianGym.asm)                                                                   | ✅ |
| [ViridianMart.asm](text/ViridianMart.asm)                                                                 | ✅ |
| [ViridianNicknameHouse.asm](text/ViridianNicknameHouse.asm)                                               | ✅ |
| [ViridianPokecenter.asm](text/ViridianPokecenter.asm)                                                     | ✅ |
| [ViridianSchoolHouse.asm](text/ViridianSchoolHouse.asm)                                                   | ✅ |
| [WardensHouse.asm](text/WardensHouse.asm)                                                                 | ✅ |

| Small files                                                                                               | Progress    |
| --------------------------------------------------------------------------------------------------------- | ----------- |
| [constants/item_constants.asm](constants/item_constants.asm)                                              | 0 / 4 ?     |
| [data/battle/stat_names.asm](data/battle/stat_names.asm)                                                  | ✅         |
| [data/events/prizes.asm](data/events/prizes.asm)                                                          | ✅         |
| [data/events/trades.asm](data/events/trades.asm)                                                          | ✅         |
| [data/moves/tmhm_moves.asm](data/moves/tmhm_moves.asm)                                                    | 0 / 4 ?     |
| [data/text_boxes.asm](data/text_boxes.asm)                                                                | ✅         |
| [data/yes_no_menu_strings.asm](data/yes_no_menu_strings.asm)                                              | ✅         |
| [engine/battle/core.asm](engine/battle/core.asm)                                                          | ✅         |
| [engine/battle/end_of_battle.asm](engine/battle/end_of_battle.asm)                                        | ✅         |
| [engine/debug/debug_menu.asm](engine/debug/debug_menu.asm)                                                | 0 / 4 ?      |
| [engine/events/diploma.asm](engine/events/diploma.asm)                                                    | ✅         |
| [engine/events/evolve_trade.asm](engine/events/evolve_trade.asm)                                          | 0 / 1 ?     |
| [engine/events/hidden_objects/bills_house_pc.asm](engine/events/hidden_objects/bills_house_pc.asm)        | ✅          |
| [engine/events/hidden_objects/school_blackboard.asm](engine/events/hidden_objects/school_blackboard.asm)  | ✅         |
| [engine/events/prize_menu.asm](engine/events/prize_menu.asm)                                              | ✅         |
| [engine/events/vending_machine.asm](engine/events/vending_machine.asm)                                    | ✅         |
| [engine/items/item_effects.asm](engine/items/item_effects.asm)                                            | ✅         |
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
| [engine/movie/trade2.asm](engine/movie/trade2.asm)                                                        | ✅         |
| [engine/overworld/player_state.asm](engine/overworld/player_state.asm)                                    | ✅         |
| [engine/pokemon/bills_pc.asm](engine/pokemon/bills_pc.asm)                                                | ✅         |
| [engine/pokemon/status_ailments.asm](engine/pokemon/status_ailments.asm)                                  | ✅         |
| [engine/pokemon/status_screen.asm](engine/pokemon/status_screen.asm)                                      | ✅         |
| [home/list_menu.asm](home/list_menu.asm)                                                                  | ✅         |
| [home/names.asm](home/names.asm)                                                                          | ✅         |
| [home/pokemon.asm](home/pokemon.asm)                                                                      | 0 / 1 ?     |
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