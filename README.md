{
	"_meta": {
		"sources": [
			{
				"json": "GiddyItem",
				"abbreviation": "Brew",
				"full": "TheGiddyLimit",
				"authors": [
					"TheGiddyLimit"
				],
				"version": "1.0.0",
				"url": "https://github.com/TheGiddyLimit/homebrew",
				"targetSchema": "1.0.0"
			}
		],
		"currencyConversions": {
			"GiddyCurrency": [
				{
					"coin": "ap",
					"mult": 1
				},
				{
					"coin": "bp",
					"mult": 0.001,
					"isFallback": true
				}
			]
		},
		"dateAdded": 0,
		"dateLastModified": 0
	},
	"itemProperty": [
		{
			"abbreviation": "Cust",
			"source": "GiddyItem",
			"entries": [
				{
					"type": "entries",
					"name": "Entangle",
					"entries": [
						"When hit by a weapon with the entangle property the target gains the Grappled condition until the weapon is removed."
					]
				}
			]
		}
	],
	"itemType": [
		{
			"abbreviation": "PSIW",
			"source": "GiddyItem",
			"name": "psionic weapon",
			"entries": [
				{
					"type": "entries",
					"name": "Psionic",
					"entries": [
						"This weapon has no physical form, and appears as a faint shimmer (comparable to heat haze) in the air."
					]
				}
			]
		}
	],
	"item": [
		{
			"name": "Hook of Butchery",
			"type": "M",
			"weaponCategory": "martial",
			"weight": 2,
			"dmg1": "1d8",
			"dmgType": "P",
			"property": [
				"T",
				"Cust"
			],
			"range": "40/40",
			"tier": "major",
			"rarity": "very rare",
			"source": "GiddyItem",
			"value": 2000,
			"currencyConversion": "GiddyCurrency",
			"entries": [
				"An enchanted butcher's hook forged from adamantine, you gain a +1 bonus to attack and damage rolls made with this magic weapon.",
				"As part of a ranged attack made with the hook, you may choose to grab a chain which begins to magically extend from the hilt. If you choose to grab the chain, it continues to extend behind the thrown weapon, to a maximum length of 40 ft. When the chain has fully extended or if the attack hits, the chain becomes taught. While taught, the chain will not extend further, and magically shortens to remove any slack. If you let go of the chain, it retracts into the hook.",
				"The chain can be broken with a successful DC 30 Strength check. It has 23 AC, and each 5-foot section has 5HP. It is immune to damage, except from adamantine weapons.",
				"As a bonus action while the chain is extended and the hook is not magically attached to a creature, you can reel the hook in along the path of the chain, returning it to the hand you threw it with.",
				"Whenever you hit a creature with a ranged attack using the hook, the hook magically attaches itself to the target. As an action, a creature may attempt to detach the hook by succeeding on a DC 20 Strength (Athletics) check. On a success, the creature take {@dice 2d6} Necrotic damage as the hook is torn free.",
				"While you are holding the chain and the hook is magically attached to a creature, you may attempt to reel the creature in. Make a Strength (Athletics) check contest by the creature's Strength (Athletics) check. On a success, the target is knocked prone and pulled up to 40 ft. directly towards you, stopping if they come within 5 ft. of you. The hook then detaches from the creature and returns to your hand."
			],
			"bonusWeapon": "+1"
		},
		{
			"name": "Psiblade",
			"type": "PSIW",
			"source": "GiddyItem",
			"dmg1": "1d8",
			"dmgType": "Y",
			"rarity": "legendary",
			"property": [
				"F"
			],
			"weaponCategory": "martial"
		}
	],
	"variant": [
		{
			"name": "Bow of Power",
			"requires": [
				{
					"name": "Shortbow"
				},
				{
					"name": "Longbow"
				}
			],
			"inherits": {
				"namePrefix": "Powerful ",
				"source": "GiddyItem",
				"rarity": "very rare",
				"entries": [
					"An extremely powerful bow."
				]
			}
		}
	]
}
