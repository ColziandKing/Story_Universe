[
    {
        "name": "Tradition",
        "era": "Ancient era",
        "priorities": {
            "Neutral": 5,
            "Cultural": 5,
            "Diplomatic": 5,
            "Domination": 5,
            "Scientific": 5
        },
        "uniques": [
            "[-30 Culture] [in capital]",
            "[+25]% Culture cost of natural border growth [in all cities]"
        ],
        "policies": [
            {
                "name": "Aristocracy",
                "uniques": [
                    "[-15]% Production when constructing [All] wonders [in all cities]",
                    "[-1 Happiness] per [10] population [in all cities]"
                ],
                "row": 1,
                "column": 1
            },
            {
                "name": "Legalism",
                "uniques": [
                    "Provides the cheapest [Culture] building in your first [2] cities for free"
                ],
                "row": 1,
                "column": 3
            },
            {
                "name": "Oligarchy",
                "uniques": [
                    "Units in cities cost no Maintenance",
                    "[-50]% Strength for cities <with a garrison> <when attacking>"
                ],
                "row": 1,
                "column": 5
            },
            {
                "name": "Landed Elite",
                "uniques": [
                    "[-10]% growth [in capital]",
                    "[-2 Food] [in capital]"
                ],
                "requires": ["Legalism"],
                "row": 2,
                "column": 2
            },
            {
                "name": "Monarchy",
                "uniques": [
                    "[-1 Gold, -1 Happiness] per [2] population [in capital]"
                ],
                "requires": ["Legalism"],
                "row": 2,
                "column": 4
            },
            {
                "name": "Tradition Complete",
                "uniques": [
                    "[-15]% growth [in all cities]",
                    "Provides a [Aqueduct] in your first [2] cities for free"
                ]
            }
        ]
    },
    {
        "name": "Liberty",
        "era": "Ancient era",
        "priorities": {
            "Neutral": 10,
            "Cultural": 10,
            "Diplomatic": 10,
            "Domination": 10,
            "Scientific": 10
        },
        "uniques": ["[-10 Culture] [in all cities]"],
        "policies": [
            {
                "name": "Republic",
                "uniques": [
                    "[-1 Production] [in all cities]",
                    "[-5]% Production when constructing [All] buildings [in all cities]",
                ],
                "row": 1,
                "column": 1
            },
            {
                "name": "Citizenship",
                "uniques": [
                    "[+25]% construction time for [All] improvements",
                    "Free [Worker] appears"
                ],
                "row": 1,
                "column": 4
            },
            {
                "name": "Collective Rule",
                "uniques": [
                    "[-50]% Production when constructing [Settler] units [in capital]",
                    "Free [Settler] appears"
                ],
                "requires": ["Republic"],
                "row": 2,
                "column": 1
            },
            {
                "name": "Representation",
                "uniques": [
                    "Each city founded increases culture cost of policies [3]% less than normal",
                    "Empire enters golden age"
                ],
                "requires": ["Citizenship"],
                "row": 2,
                "column": 3
            },
            {
                "name": "Meritocracy",
                "uniques": [
                    "[-1 Happiness] [in all cities connected to capital]",
                    "[+10000]% Unhappiness from [Population] [in all non-occupied cities]"
                ],
                "requires": ["Citizenship"],
                "row": 2,
                "column": 5
            },
            {
                "name": "Liberty Complete",
                "uniques": ["Free Great Person"]
            }
        ]
    },
    {
        "name": "Honor",
        "era": "Ancient era",
        "priorities": {
            "Neutral": 5,
            "Cultural": 5,
            "Diplomatic": 5,
            "Domination": 5,
            "Scientific": 5
        },
        "uniques": [
            "[-33]% Strength <vs [Barbarian] units>",
            "Earn [1]% of killed [Barbarian] unit's [Strength] as [Culture]",
            "Notified of new Barbarian encampments"
        ],
        "policies": [
            {
                "name": "Warrior Code",
                "uniques": [
                    "[-15]% Production when constructing [Melee] units [in all cities]",
                    "Free [Great General] appears"
                ],
                "row": 1,
                "column": 2
            },
            {
                "name": "Discipline",
                "uniques": [
                    "[-15]% Strength <for [Melee] units> <when adjacent to a [Melee] unit>"
                ],
                "row": 1,
                "column": 4
            },
            {
                "name": "Military Tradition",
                "uniques": [
                    "[-50]% XP gained from combat <for [Military] units>"
                ],
                "requires": ["Warrior Code"],
                "row": 2,
                "column": 2
            },
            {
                "name": "Military Caste",
                "uniques": [
                    "[-1 Happiness, -2 Culture] [in all cities with a garrison]"
                ],
                "requires": ["Discipline"],
                "row": 2,
                "column": 4
            },
            {
                "name": "Professional Army",
                "uniques": [
                    "[+33]% Gold cost of upgrading <for [Military] units>",
                    "[-1 Happiness] from every [Walls]",
                    "[-1 Happiness] from every [Castle]",
                    "[-1 Happiness] from every [Arsenal]",
                    "[-1 Happiness] from every [Military Base]"
                ],
                "requires": ["Military Caste"],
                "row": 3,
                "column": 4
            },
            {
                "name": "Honor Complete",
                "uniques": [
                    "Earn [1]% of killed [Military] unit's [Cost] as [Gold]"
                ]
            }
        ]
    },
    {
        "name": "Piety",
        "era": "Classical era",
        "priorities": {
            "Neutral": 5,
            "Cultural": 5,
            "Diplomatic": 5,
            "Domination": 5,
            "Scientific": 5
        },
        "uniques": [
            "[-100]% Production when constructing [Shrine] buildings [in all cities]",
            "[-100]% Production when constructing [Temple] buildings [in all cities]"
        ],
        "policies": [
            {
                "name": "Organized Religion",
                "uniques": [
                    "[-1 Faith] from every [Shrine]",
                    "[-1 Faith] from every [Temple]"
                ],
                "row": 1,
                "column": 2
            },
            {
                "name": "Mandate Of Heaven",
                "uniques": ["[5]% of excess happiness converted to [Culture]"],
                "row": 1,
                "column": 5
            },
            {
                "name": "Theocracy",
                "uniques": ["[-10]% [Gold] from every [Temple]"],
                "requires": ["Organized Religion"],
                "row": 2,
                "column": 1
            },
            {
                "name": "Reformation",
                "uniques": [
                    "[-33]% [Culture] [in all cities with a world wonder]",
                    "Empire enters golden age"
                ],
                "requires": ["Organized Religion"],
                "row": 2,
                "column": 3
            },
            {
                "name": "Free Religion",
                "uniques": ["[+10]% Culture cost of adopting new Policies"],
                "requires": ["Mandate Of Heaven", "Reformation"],
                "row": 3,
                "column": 4
            },
            {
                "name": "Piety Complete",
                "uniques": [
                    "[Faith] cost of purchasing items in cities [+20]%",
                    "[-3 Gold, -3 Culture] from every [Holy site]"
                ]
            }
        ]
    },
    {
        "name": "Patronage",
        "era": "Medieval era",
        "priorities": {
            "Neutral": 5,
            "Cultural": 5,
            "Diplomatic": 10,
            "Domination": 5,
            "Scientific": 5
        },
        "uniques": ["[+25]% City-State Influence degradation"],
        "policies": [
            {
                "name": "Philantropy",
                "uniques": [
                    "Gifts of Gold to City-States generate [2]% more Influence"
                ],
                "row": 1,
                "column": 2
            },
            {
                "name": "Aesthetics",
                "uniques": [
                    "Resting point for Influence with City-States is increased by [2]"
                ],
                "row": 1,
                "column": 4
            },
            {
                "name": "Scholasticism",
                "uniques": [
                    "Allied City-States provide [Science] equal to [2]% of what they produce for themselves"
                ],
                "requires": ["Philantropy"],
                "row": 2,
                "column": 2
            },
            {
                "name": "Cultural Diplomacy",
                "uniques": [
                    "[-100]% resources gifted by City-States",
                    "[-50]% Happiness from luxury resources gifted by City-States"
                ],
                "requires": ["Scholasticism"],
                "row": 3,
                "column": 2
            },
            {
                "name": "Educated Elite",
                "requires": ["Scholasticism", "Aesthetics"],
                "uniques": [
                    "Allied City-States will occasionally gift Great People"
                ],
                "row": 3,
                "column": 4
            },
            {
                "name": "Patronage Complete",
                "uniques": [
                    "Influence of all other civilizations with all city-states degrades [3]% faster",
                    "Triggers the following global alert: [Our influence with City-States has started dropping faster!]"
                ]
            }
        ]
    },
    {
        "name": "Commerce",
        "era": "Renaissance era",
        "priorities": {
            "Neutral": 5,
            "Cultural": 5,
            "Diplomatic": 5,
            "Domination": 5,
            "Scientific": 5
        },
        "uniques": ["[-25]% [Gold] [in capital]"],
        "policies": [
            {
                "name": "Naval Tradition",
                "uniques": [
                    "[-1] Movement <for [{Military} {Water}] units>",
                    "[-1] Sight <for [{Military} {Water}] units>",
                    "Free [Great General] appears"
                    // "[+2] Movement <for [Great Admiral] units>"
                    // ToDo: Should be "Free [Great Admiral] appears"
                ],
                "row": 1,
                "column": 2
            },
            {
                "name": "Trade Unions",
                "uniques": [
                    "[+33]% maintenance on road & railroads",
                    "[-1 Gold] from every [Harbor]",
                    "[-1 Gold] from every [Seaport]"
                ],
                "row": 1,
                "column": 4
            },
            {
                "name": "Merchant Navy",
                "uniques": ["[-3 Production] [in all coastal cities]"],
                "requires": ["Naval Tradition"],
                "row": 2,
                "column": 2
            },
            {
                "name": "Mercantilism",
                "uniques": [
                    "[Gold] cost of purchasing items in cities [+25]%",
                    "[-1 Science] from every [Mint]",
                    "[-1 Science] from every [Market]",
                    "[-1 Science] from every [Bank]",
                    "[-1 Science] from every [Stock Exchange]"
                ],
                "requires": ["Trade Unions"],
                "row": 2,
                "column": 4
            },
            {
                "name": "Protectionism",
                "uniques": ["[-2] Happiness from each type of luxury resource"],
                "requires": ["Mercantilism"],
                "row": 3,
                "column": 4
            },
            {
                "name": "Commerce Complete",
                "uniques": [
                    "[-1 Gold] from every [Trading post]",
                    "[-100]% Gold from Great Merchant trade missions",
                    "May buy [Great Merchant] units for [1000] [Faith] [in all cities in which the majority religion is a major religion] at an increasing price ([500]) <starting from the [Industrial era]>"
                ]
            }
        ]
    },
    {
        "name": "Rationalism",
        "era": "Industrial era",
        "priorities": {
            "Neutral": 10,
            "Cultural": 10,
            "Diplomatic": 10,
            "Domination": 10,
            "Scientific": 10
        },
        "uniques": [
            "[-15]% [Science] <while the empire is happy>",
          "Only available <before adopting [Autocracy]>", "Only available <before adopting [Order]>"
        ],
        "policies": [
            {
                "name": "Secularism",
                "uniques": [
                    "[-2 Science] from every specialist [in all cities]"
                ],
                "row": 1,
                "column": 2
            },
            {
                "name": "Humanism",
                "uniques": [
                    "[-1 Happiness] from every [University]",
                    "[-1 Happiness] from every [Observatory]",
                    "[-1 Happiness] from every [Public School]"
                ],
                "row": 1,
                "column": 4
            },
            {
                "name": "Free Thought",
                "uniques": [
                    "[-1 Science] from every [Trading post]",
                    "[-17]% [Science] from every [University]"
                ],
                "requires": ["Secularism"],
                "row": 2,
                "column": 2
            },
            {
                "name": "Sovereignty",
                "uniques": ["[-1 Gold] from all [Science] buildings"],
                "requires": ["Humanism"],
                "row": 2,
                "column": 4
            },
            {
                "name": "Scientific Revolution",
                "uniques": ["Science gained from research agreements [-50]%"],
                "requires": ["Free Thought"],
                "row": 3,
                "column": 2
            },
            {
                "name": "Rationalism Complete",
                "uniques": [
                    "[1] Free Technologies",
                    "May buy [Great Scientist] units for [1000] [Faith] [in all cities in which the majority religion is a major religion] at an increasing price ([500]) <starting from the [Industrial era]>"
                ]
            }
        ]
    },
    {
        "name": "Freedom",
        "era": "Industrial era",
        "priorities": {
            "Neutral": 5,
            "Cultural": 10,
            "Diplomatic": 5,
            "Domination": 5,
            "Scientific": 10
        },
        "uniques": [
            "[-25]% Great Person generation [in all cities]",
            "Only available <before adopting [Autocracy]>",
            "Only available <before adopting [Order]>"
        ],
        "policies": [
            {
                "name": "Constitution",
                "uniques": ["[-2 Culture] from every [Wonder]"],
                "row": 1,
                "column": 1
            },
            {
                "name": "Universal Suffrage",
                "uniques": ["[-33]% Strength for cities <when defending>"],
                "row": 1,
                "column": 3
            },
            {
                "name": "Civil Society",
                "uniques": [
                    "[+50]% Food consumption by specialists [in all cities]"
                ],
                "row": 1,
                "column": 5
            },
            {
                "name": "Free Speech",
                "uniques": ["[2] units cost no maintenance"],
                "requires": ["Constitution"],
                "row": 2,
                "column": 1
            },
            {
                "name": "Democracy",
                "uniques": [
                    "[+50]% Unhappiness from [Specialists] [in all cities]"
                ],
                "requires": ["Civil Society"],
                "row": 2,
                "column": 5
            },
            {
                "name": "Freedom Complete",
                "uniques": [
                    "[-100]% Yield from every [Great Improvement]",
                    "[-50]% Golden Age length",
                    "May buy [Great Artist] units for [1000] [Faith] [in all cities in which the majority religion is a major religion] at an increasing price ([500]) <starting from the [Industrial era]>"
                ]
            }
        ]
    },
    {
        "name": "Autocracy",
        "era": "Industrial era",
        "priorities": {
            "Neutral": 5,
            "Cultural": 5,
            "Diplomatic": 5,
            "Domination": 10,
            "Scientific": 5
        },
        "uniques": [
            "[+33]% maintenance costs <for [All] units>",
            "Upon capturing a city, receive [1] times its [Culture] production as [Culture] immediately",
            "Only available <before adopting [Rationalism]>",
            "Only available <before adopting [Order]>",
            "Only available <before adopting [Freedom]>"
        ],
        "policies": [
            {
                "name": "Populism",
                "uniques": ["[-25]% Strength <for [Wounded] units>"],
                "row": 1,
                "column": 2
            },
            {
                "name": "Militarism",
                "uniques": ["[Gold] cost of purchasing [All] units [+33]%"],
                "row": 1,
                "column": 4
            },
            {
                "name": "Fascism",
                "uniques": [
                    "Quantity of strategic resources produced by the empire +[1]%",
                    "[-2] Movement <for [Great General] units>"
                ],
                "requires": ["Populism", "Militarism"],
                "row": 2,
                "column": 2
            },
            {
                "name": "Police State",
                "uniques": [
                    "[-3 Happiness] from every [Courthouse]",
                    "[-100]% Production when constructing [Courthouse] buildings [in all cities]",
                    "[+25]% enemy spy effectiveness [in all cities]"
                ],
                "requires": ["Militarism"],
                "row": 2,
                "column": 4
            },
            {
                "name": "Total War",
                "uniques": [
                    "[-25]% Production when constructing [Military] units [in all cities]",
                    "New [Military] units start with [1] Experience [in all cities]"
                ],
                "requires": ["Police State", "Fascism"],
                "row": 3,
                "column": 3
            },
            {
                "name": "Autocracy Complete",
                "uniques": [
                    "[-25]% Strength <when attacking> <for [Military] units> <for [50] turns>",
                    "May buy [Great General] units for [1000] [Faith] [in all cities in which the majority religion is a major religion] at an increasing price ([500]) <starting from the [Industrial era]>",
                ]
            }
        ]
    },
    {
        "name": "Order",
        "era": "Industrial era",
        "priorities": {
            "Neutral": 10,
            "Cultural": 5,
            "Diplomatic": 10,
            "Domination": 5,
            "Scientific": 5
        },
        "uniques": [
            "[-1 Happiness] [in all cities]",
            "Only available <before adopting [Rationalism]>",
            "Only available <before adopting [Autocracy]>",
            "Only available <before adopting [Freedom]>"
        ],
        "policies": [
            {
                "name": "United Front",
                "uniques": [
                    "Militaristic City-States grant units [2] times as fast when you are at war with a common nation"
                ],
                "row": 1,
                "column": 1
            },
            {
                "name": "Planned Economy",
                "uniques": [
                    "[-25]% [Science] from every [Factory]",
                    "[-100]% Production when constructing [Factory] buildings [in all cities]"
                ],
                "row": 1,
                "column": 3
            },
            {
                "name": "Nationalism",
                "uniques": [
                    "[-15]% Strength <for [All] units> <when fighting in [Friendly Land] tiles>"
                ],
                "row": 1,
                "column": 5
            },
            {
                "name": "Socialism",
                "requires": ["Planned Economy"],
                "uniques": [
                    "[+15]% maintenance cost for buildings [in all cities]"
                ],
                "row": 2,
                "column": 3
            },
            {
                "name": "Communism",
                "requires": ["Socialism"],
                "uniques": [
                    "[-2 Production] [in all cities]",
                    "[-1 Production] from every [Mine]",
                    "[-1 Production] from every [Quarry]"
                ],
                "row": 3,
                "column": 3
            },
            {
                "name": "Order Complete",
                "uniques": [
                    "[-2 Food, -2 Production, -2 Science, -2 Gold, -2 Culture] [in all cities]",
                    "May buy [Great Engineer] units for [1000] [Faith] [in all cities in which the majority religion is a major religion] at an increasing price ([500]) <starting from the [Industrial era]>"
                ]
            }
        ]
    }
]