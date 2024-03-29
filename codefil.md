{
		"name": "Settling Stone",
		"replaces": "Monument",
		"uniqueTo": "Yanzerhan",
		"culture": 3,
		"faith": 3,
		"cost": 60,
		"hurryCostModifier": 40,
		"maintenance": 2,
		"uniques": ["Destroyed when the city is captured"] //"Hidden when religion is disabled"
	},
  {
		"name": "Seowon",
		"replaces": "University",
		"uniqueTo": "Salveo",
		"maintenance": 3
		"hurryCostModifier": 15,
		"percentStatBonus": {"science": 33},
		"specialistSlots": {"Scientist": 2},
		"culture": 3,
		"requiredBuilding": "Library",
		"uniques": ["[+35]% [Science] [in this city]"],
		"requiredTech": "Education"
	},
	{
		"name": "Queexame",
		"replaces": "Observatory",
		"uniqueTo": "Magroonaguio",
		"maintenance": 0,
		"hurryCostModifier": 15,
		"percentStatBonus": {"science": 50},
		"requiredBuilding": "Library",
		"uniques": ["Must be next to [Mountain]", "Must be next to [Hill]", "[+1] Sight <for [{Military} {Water}] units>"],
		"requiredTech": "Astronomy"
	}
[
  {
        "name": "Order",
        "era": "Industrial era",
        "priorities": {
            "Neutral": 50,
            "Cultural": 40,
            "Diplomatic": 50,
            "Domination": 40,
            "Scientific": 50
        },
        "uniques": [
            "[+2 Happiness] [in all cities]"
        ],
        "policies": [
            {
                "name": "United Front",
                "uniques": [
                    "Militaristic City-States grant units [3] times as fast when you are at war with a common nation"
                ],
                "row": 1,
                "column": 1
            },
            {
                "name": "Planned Economy",
                "uniques": [
                    "[+25]% [Science] from every [Factory]",
                    "[+100]% Production when constructing [Factory] buildings [in all cities]"
                ],
                "row": 1,
                "column": 3
            },
            {
                "name": "Nationalism",
                "uniques": [
                    "[+15]% Strength <for [All] units> <when fighting in [Friendly Land] tiles>"
                ],
                "row": 1,
                "column": 5
            },
            {
                "name": "Socialism",
                "requires": ["Planned Economy"],
                "uniques": ["May buy [B17] units with [Gold] for [3] times their normal Production cost",
                    "[-15]% maintenance cost for buildings [in all cities]"
                ],
                "row": 2,
                "column": 3
            },
            {
                "name": "Communism",
                "requires": ["Socialism"],
                "uniques": ["May buy [Panzer] units with [Gold] for [3] times their normal Production cost",
                    "[+2 Production] [in all cities]",
                    "[+1 Production] from every [Mine]",
                    "[+1 Production] from every [Quarry]"
                ],
                "row": 3,
                "column": 3
            },
            {
                "name": "Order Complete",
                "uniques": ["[1] free [Stealth Bomber] units appear",
                    "[+2 Food, +2 Production, +2 Science, +2 Gold, +2 Culture] [in all cities]",
                    "May buy [Great Engineer] units for [1000] [Faith] [in all cities in which the majority religion is a major religion] at an increasing price ([500]) <starting from the [Industrial era]>"
                ]
            }
        ]
    }
  ]
[
  {
		"name": "Supreme Emperor",
		"baseHappiness": 9,
		"extraHappinessPerLuxury": 0,
		"researchCostModifier": 1,
		"unitCostModifier": 1,
		"unitSupplyBase": 5,
		"unitSupplyPerCity": 2,
		"buildingCostModifier": 1,
		"policyCostModifier": 1,
		"unhappinessModifier": 1,
		"barbarianBonus": 0.2,
		"barbarianSpawnDelay": 0,
		"playerBonusStartingUnits": [],
		"aiCityGrowthModifier": 0.85,
		"aiUnitCostModifier": 0.8,
		"aiBuildingCostModifier": 0.8,
		"aiWonderCostModifier": 1,
		"aiBuildingMaintenanceModifier": 0.8,
		"aiUnitMaintenanceModifier": 0.75,
		"aiUnitSupplyModifier": 0.3,
		"aiFreeTechs": ["Pottery","Animal Husbandry"],
		"aiMajorCivBonusStartingUnits": ["Era Starting Unit", "Settler", "Scout"],
		"aiCityStateBonusStartingUnits": [],
		"aiUnhappinessModifier": 0.85,
		"aisExchangeTechs": true,
		"turnBarbariansCanEnterPlayerTiles": 0,
		"clearBarbarianCampReward": 25
	},
	{
		"name": "Harvest Bin",
		"replaces": "Granary",
		"uniqueTo": "Dicesun",
		"food": 3,
		"maintenance": 2,
		"hurryCostModifier": 25,
		"uniques": ["[+1 Food] from [Deer] tiles [in this city]",
			"[+1 Food] from [Bananas] tiles [in this city]",
			"[+1 Food] from [Wheat] tiles [in this city]"],
		"requiredTech": "Pottery"
	},
	{
		"name": "Basalt Builds",
		"replaces": "Stone Works",
		"uniqueTo": "Skiuma",
		"happiness": 1,
		"culture": 1,
		"production": 2,
		"requiredNearbyImprovedResources": ["Marble", "Stone"],
		"maintenance": 1,
		"hurryCostModifier": 0,
		"uniques": ["Must not be on [Plains]",
			"[+1 Production] from [Stone] tiles [in this city]",
			"[+1 Production] from [Marble] tiles [in this city]"],
		"requiredTech": "Calendar"
	},
	{
		"name": "Hotel",
		"uniqueTo": "Skiuma",
		"gold": 5,
		"cost": 440,
		"maintenance": 3,
		"hurryCostModifier": 25,
		"uniques": ["[+50]% [Culture] [in all cities]"],
		"requiredTech": "Refrigeration"
	},
	{
		"name": "Zoo",
		"uniqueTo": "Dicesun",
		"happiness": 2,
		"cost": 320,
		"maintenance": 2,
		"hurryCostModifier": 25,
		"requiredBuilding": "Colosseum",
		"requiredTech": "Printing Press"
	}
]
