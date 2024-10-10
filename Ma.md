PolicyBranchIcons/Singularity
  rotate: false
  xy: 120, 148
  size: 50, 50
  orig: 50, 50
  offset: 0, 0
  index: -1

			"Gain a free [Stone Works] [in all cities]"


{
		"name": "Naturalism",
		"era": "Atomic era",
		"uniques": [
			"[+1 Food, +1 Culture] [in all cities]",
			"Only available <before adopting [Bionics]>"
		],
		"policies": [
			{
				"name": "Emissions Standards",
				"uniques": [
					"[+10]% [Food] from every [Coal Plant]",
					"[-15]% [Production] from every [Coal Plant]",
					"[+1 Happiness] from every [Recycling Plant]",
					"[+1 Happiness] from every [Solar Plant]"
				],
				"row": 1,
				"column": 3
			},
			{
				"name": "Entrepreneurship",
				"uniques": [
					"[Great Merchant] is earned [20]% faster",
					"[+1 Science] from every [Market]",
					"[+1 Science] from every [Factory]",
					"[+1 Science] from every [Public School]"
				],
				"requires": ["Emissions Standards"],
				"row": 2,
				"column": 2
			},
			{
				"name": "Ecodefense",
				"requires": ["Emissions Standards"],
				"uniques": [
					"[+15]% Strength <for [All] units> <when fighting in [Plains] tiles>",
					"[+15]% Strength <for [All] units> <when fighting in [Jungle] tiles>",
					"[+15]% Strength <for [All] units> <when fighting in [Hill] tiles>",
					"[+15]% Strength <for [All] units> <when fighting in [Forest] tiles>",
					"[+15]% Strength <for [All] units> <when fighting in [Grassland] tiles>"
				],
				"row": 2,
				"column": 4
			},
			{
				"name": "Harmony",
				"requires": ["Entrepreneurship"],
				"uniques": [
					"[+1 Happiness, +1 Food, +1 Faith, +1 Culture, -3 Production] <in cities with at least [7] [Population]>",
					"Resting point for Influence with City-States is increased by [15]",
					"[-25]% City-State Influence degradation"
				],
				"row": 3,
				"column": 1
			},
			{
				"name": "Conservation",
				"requires": ["Entrepreneurship"],
				"uniques": [
					"[+1 Gold] from every [Worker]",
					"[+1 Gold] from [Fresh water] tiles [in all cities]",
					"[+1 Gold] from every [Polder]"
				],
				"row": 3,
				"column": 3
			},
			{
				"name": "Naturalism Complete",
				"uniques": [
					"Empire enters golden age",
					"[50]% Golden Age length",
					"May buy [Great Artist] units for [1000] [Faith] [in all cities in which the majority religion is a major religion] at an increasing price ([500]) <starting from the [Industrial era]>"
				]
			}
		]
	},
	{
		"name": "Bionics",
		"era": "Information era",
		"uniques": [
			"[+2 Science] [in all cities]",
			"Only available <before adopting [Naturalism]>"
		],
		"policies": [
			{
				"name": "Weather Engineering",
				"uniques": [
					"[+2 Gold] [in all cities]",
					"[+10]% growth [in all cities] <during a Golden Age>"
				],
				"row": 1,
				"column": 1
			},
			{
				"name": "Mutagens",
				"uniques": [
					"[+1 Culture, +1 Food, +1 Science] from every [Hospital]",
					"[+1 Culture, +1 Food, +1 Science] from every [Medical Lab]"
				],
				"row": 1,
				"column": 3
			},
			{
				"name": "Eugenics",
				"requires": ["Mutagens"],
				"uniques": [
					"[+5]% Strength <for [Military] units>",
					"[-25]% Unhappiness from [Specialists] [in all cities]",
					"[+2 Faith] <in cities with at least [2] [Specialists]>"
				],
				"row": 2,
				"column": 2
			},
			{
				"name": "Cybernetics",
				"requires": ["Mutagens"],
				"uniques": [
					"No damage penalty for wounded units <for [Melee] units>",
					"[+1 Production] per [10] population [in all cities]"
				],
				"row": 2,
				"column": 4
			},
			{
				"name": "Scorched Earth",
				"requires": ["Eugenics", "Cybernetics"],
				"uniques": [
					"[+15]% Strength <vs cities>",
					"Cities are razed [2] times as fast",
					"No movement cost to pillage <for [Melee] units>",
					"[+2] Movement <for [Great General] units>",
					"[+25]% Great Person generation [in all cities]",
					"[Great General] is earned [25]% faster",
					"[Faith] cost of purchasing items in cities [-10]%"
				],
				"row": 3,
				"column": 5
			},
			{
				"name": "Bionics Complete",
				"uniques": [
					"Free Great Person",
					"[+10]% Production when constructing [Science] buildings [in all cities]",
					"[+15]% Production when constructing [Military] units [in all cities]"
				]
			}
