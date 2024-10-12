# My50th
My 50th coding to be done for Christ alone is my Lord and God

"[+1 Production] from [All] tiles [in all cities]",
game5.png
size: 1024, 1024
format: RGBA8888
filter: MipMapLinearLinear, MipMapLinearLinear
repeat: none
BuildingIcons/Palengke (KO)
  rotate: false
  xy: 4, 4
  size: 700, 700
  orig: 700, 700
  offset: 0, 0
  index: -1
BuildingIcons/Palengke (Manila)
  rotate: false
  xy: 4, 4
  size: 700, 700
  orig: 700, 700
  offset: 0, 0
  index: -1
PolicyIcons/Representation
  rotate: false
  xy: 1798, 1876
  size: 50, 50
  orig: 50, 50
  offset: 0, 0
  index: -1
	{ 
		"name": "Palengke (Manila)",
		"replaces": "Market",
		"uniqueTo": "Philippines",
		"gold": 2,
		"specialistSlots": {"Merchant": 1},
		"hurryCostModifier": 23,
		"percentStatBonus": {"gold": 30},
		"uniques": [
			"Comment [[+1 Food, +1 Gold, +1 Production] from each Trade Route (doubled from the [Industrial era] onwards)]",
			"Comment [[+1 Gold, +1 Production] from [Stone] tiles; and [+1 Gold, +1 Food] from other [Bonus resource] tiles [in this city]]",
			"Comment [[+1 Production, +1 Food] from [Horses] tiles; and [+1 Production, +1 Gold] from other [Strategic resource] tiles [in this city]]",
			"[+1 Gold, +1 Production, +1 Happiness] from [Luxury resource] tiles [in this city]",
			"[+1 Food, +1 Gold, +1 Production] from each Trade Route <before the [Industrial era]> <hidden from users>",
			"[+2 Food, +2 Gold, +2 Production] from each Trade Route <starting from the [Industrial era]> <hidden from users>",
			"[+1 Food, +1 Gold] from [Bonus resource] tiles [in this city] <in tiles without [Stone]> <hidden from users>",
			"[+1 Production, +1 Gold] from [Stone] tiles [in this city] <hidden from users>",
			"[+1 Production, +1 Gold] from [Strategic resource] tiles [in this city] <in tiles without [Horses]> <hidden from users>",
			"[+1 Production, +1 Food] from [Horses] tiles [in this city] <hidden from users>"
		],
		"requiredTech": "Currency"
	},
	{ 
		"name": "Palengke (KO)",
		"replaces": "Market",
		"uniqueTo": "Kolziand",
		"gold": 2,
		"specialistSlots": {"Merchant": 1},
		"hurryCostModifier": 23,
		"percentStatBonus": {"gold": 30},
		"uniques": [
			"Comment [[+1 Food, +1 Gold, +1 Production] from each Trade Route (doubled from the [Industrial era] onwards)]",
			"Comment [[+1 Gold, +1 Production] from [Stone] tiles; and [+1 Gold, +1 Food] from other [Bonus resource] tiles [in this city]]",
			"Comment [[+1 Production, +1 Food] from [Horses] tiles; and [+1 Production, +1 Gold] from other [Strategic resource] tiles [in this city]]",
			"[+1 Gold, +1 Production, +1 Happiness] from [Luxury resource] tiles [in this city]",
			"[+1 Food, +1 Gold, +1 Production] from each Trade Route <before the [Industrial era]> <hidden from users>",
			"[+2 Food, +2 Gold, +2 Production] from each Trade Route <starting from the [Industrial era]> <hidden from users>",
			"[+1 Food, +1 Gold] from [Bonus resource] tiles [in this city] <in tiles without [Stone]> <hidden from users>",
			"[+1 Production, +1 Gold] from [Stone] tiles [in this city] <hidden from users>",
			"[+1 Production, +1 Gold] from [Strategic resource] tiles [in this city] <in tiles without [Horses]> <hidden from users>",
			"[+1 Production, +1 Food] from [Horses] tiles [in this city] <hidden from users>"
		],
		"requiredTech": "Currency"
	},

[
    {
        "name": "Scientific",
        "friendBonusUniques": [
            "[+3 Science] <before the [Medieval era]>",
            "[+6 Science] <starting from the [Medieval era]> <before the [Industrial era]>",
            "[+13 Science] <starting from the [Industrial era]>"
        ],
        "allyBonusUniques": [
            "[+6 Science] <before the [Medieval era]>",
            "[+12 Science] <starting from the [Medieval era]> <before the [Industrial era]>",
            "[+26 Science] <starting from the [Industrial era]>"
        ],
        "color": [0, 255, 255]
    },
    {
        "name": "Productive",
        "friendBonusUniques": ["[+3 Production] [in capital]"],
        "allyBonusUniques": ["[+4 Production] [in capital]", "[+2 Production] [in all cities]","Provides a unique luxury"],
        "color": [255, 128, 0]
    }
]
