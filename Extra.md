game6.png
size: 2048, 2048
format: RGBA8888
filter: MipMapLinearLinear, MipMapLinearLinear
repeat: none
ImprovementIcons/Colossal Head
  rotate: false
  xy: 620, 1804
  size: 200, 200
  orig: 200, 200
  offset: 0, 0
  index: -1
ImprovementIcons/Dam
  rotate: false
  xy: 4, 980
  size: 200, 200
  orig: 200, 200
  offset: 0, 0
  index: -1
ImprovementIcons/Holy Place
  rotate: false
  xy: 212, 1188
  size: 200, 200
  orig: 200, 200
  offset: 0, 0
  index: -1
ImprovementIcons/Kurgan
  rotate: false
  xy: 212, 356
  size: 200, 200
  orig: 200, 200
  offset: 0, 0
  index: -1
ImprovementIcons/Seaside Stall
  rotate: false
  xy: 420, 764
  size: 200, 200
  orig: 200, 200
  offset: 0, 0
  index: -1

game5.png
size: 2048, 1024
format: RGBA8888
filter: MipMapLinearLinear, MipMapLinearLinear
repeat: none
ImprovementIcons/Sacred altar
  rotate: false
  xy: 1252, 808
  size: 200, 200
  orig: 200, 200
  offset: 0, 0
  index: -1

{
		"name": "Seaside Stall",
		"food": 1,
		"gold": 2,
		"terrainsCanBeBuiltOn": ["Land"],
		"turnsToBuild": 8,
		"techRequired": "Currency",
		"uniques": ["Can be built outside your borders","Can only be built on [Coastal] tiles","[+1 Food] for each adjacent [Fishing Boats]","[+1 Production] <after discovering [Navigation]>"]
	},
		{
		"name": "Colossal Head",
		"terrainsCanBeBuiltOn": ["Jungle","Forest"],
		"faith": 2,
		"science": 2,
		"turnsToBuild": 6,
		"techRequired": "Calendar",
		"uniques": ["Can be built outside your borders","Cannot be built on [Land] tiles <with [1] to [4] neighboring [Colossal Head] tiles>","[+1 Culture] <after discovering [Archaeology]>","[+1 Science] for each adjacent [Great Improvement]","[+1 Science] for each adjacent [Great Improvement] <after discovering [Astronomy]>"]
	},
			{
		"name": "Kurgan",
		"terrainsCanBeBuiltOn": ["Plains"],
		"culture": 2,
		"faith": 1,
		"turnsToBuild": 8,
		"techRequired": "Masonry",
		"uniques": ["Can be built outside your borders","[+1 Culture] <after discovering [Archaeology]>","Cannot be built on [Land] tiles <with [1] to [4] neighboring [Kurgan] tiles>","Pillaging this improvement yields approximately [+50 Gold]"]
	},
	{
		"name": "Holy Place",
		"terrainsCanBeBuiltOn": ["Land"],
		"turnsToBuild": 8,
		"happiness": 2,
		"faith": 1,
		"techRequired": "Pottery",
		"uniques": ["Can be built outside your borders","Cannot be built on [Land] tiles <with [1] to [4] neighboring [Holy Place] tiles>","Gives a defensive bonus of [50]%"]
	},
	{
		"name": "Sacred altar",
		"terrainsCanBeBuiltOn": ["Land"],
		"faith": 2,
		"uniques": ["Can be built outside your borders","Cannot be built on [Land] tiles <with [1] to [4] neighboring [Sacred altar] tiles>","Tile provides yield without assigned population"]
	},
 //Special
	
	{
		"name": "Chateau",
		"uniqueTo": "France",
		"terrainsCanBeBuiltOn": ["Land"],
		"gold": 1,
		"culture": 2,
		"turnsToBuild":7,
		"techRequired": "Chivalry",
		"uniques": ["Can be built outside your borders","Can only be built on [Land] tiles <with [1] to [6] neighboring [Luxury resource] tiles>","Cannot be built on [Land] tiles <with [1] to [4] neighboring [Chateau] tiles>","Gives a defensive bonus of [50]%","[+2 Gold, +1 Culture] <after discovering [Flight]>"]
	},
	{
		"name": "Brazilwood Camp",
		"uniqueTo": "Brazil",
		"terrainsCanBeBuiltOn": ["Jungle"],
		"gold": 2,
		"turnsToBuild": 7,
		"techRequired": "Machinery",
		"uniques": ["Can be built outside your borders","[+2 Culture] <after discovering [Acoustics]>"]
	},
		{
		"name": "Feitoria",
		"uniqueTo": "Portugal",
		"terrainsCanBeBuiltOn": ["Land"],
		"turnsToBuild": 7,
		"gold": 1,
		"happiness": 1,
		"techRequired": "Navigation",
		"uniques": ["Can be built outside your borders","Gives a defensive bonus of [50]%","Can only be built on [Coastal] tiles"]
	},
	{
		"name": "Kasbah",
		"uniqueTo": "Morocco",
		"terrainsCanBeBuiltOn": ["Desert","Flood plains"],
		"food": 1,
		"production": 1,
		"gold": 1,
		"turnsToBuild": 7,
		"techRequired": "Chivalry",
		"uniques": ["Can be built outside your borders","Gives a defensive bonus of [50]%"]
	},
