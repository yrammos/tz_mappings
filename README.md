# tz_mappings

Time-zone mappings for CLDR data.

Contains:

1. Country names, abbreviations, and time-zones grouped by two-letter CLDR country code. Example:

```
	"PG": {
			"name": "Papua New Guinea",
			"abbr": "PG",
			"zones": [
				"Pacific/Port_Moresby",
				"Pacific/Bougainville"
			]
		},
```


2. Reference timezone geolocation, alternative timezone names, and relevant timezone countries grouped by full CLDR timezone name. Example:

```
		"Africa/Maputo": {
			"name": "Africa/Maputo",
			"lat": -24.0333,
			"long": 32.5833,
			"countries": [
				"MZ",
				"BI",
				"BW",
				"CD",
				"MW",
				"RW",
				"ZM",
				"ZW"
			],
			"comments": "Central Africa Time"
		},
```

