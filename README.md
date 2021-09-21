<!-- markdownlint-disable MD002 MD022 -->

```charty
{
  "title":   "Radar chart",
  "caption": "With a caption",
  "type":    "radar",
  "options": {
	"legend":  true,
    "labels":  true,
    "numbers": true
  },
  "data": [
    {
		"label": "iPhone",
		"value": [64, 23, 45, 34, 52, 43, 59, 40],
		"points": [
			"Features",
			"Style",
			"Usability",
			"Ratings",
			"Apps",
			"Softness",
			"Ruggedness",
			"Appeal"
		]
	},
	{
		"label": "Android",
		"value": [86, 53, 55, 66, 80, 46, 49, 40]
	},
	{
		"label": "Chrome",
		"value": [100, 35, 76, 90, 36, 9, 0, 90]
	}
  ]
}
```

```charty
{
  "title":   "Area chart",
  "caption": "With a caption",
  "type":    "area",
  "options": {
	"legend":  true,
    "labels":  true,
    "numbers": true
  },
  "data": [
    {
		"label": "2010",
		"value": [120, 23, 45, 34, 52, 43, 59, 40]
	 }
  ]
}
```

```charty
{
  "title":   "Area chart",
  "caption": "With a caption",
  "type":    "area",
  "options": {
	"legend":  true,
    "labels":  true,
    "numbers": true
  },
  "data": [
    {
		"label": "2010",
		"value": [120, 23, 45, 34, 52, 43, 59, 40]
	 },
	 {
 		"label": "2010",
 		"value": [1520, 523, 445, 364, 952, 43, 959, 40]
 	 }
  ]
}
```

```charty
{
  "title":   "Bar chart",
  "caption": "With a caption",
  "type":    "bar",
  "options": {
	"legend":  true,
    "labels":  true,
    "numbers": true
  },
  "data": [
	{ "label": "2012", "value": [199, 100] },
	{ "label": "2014", "value": [85, 217] }
  ]
}
```

```charty
{
  "title":   "Bar (stacked) chart",
  "caption": "With a caption",
  "type":    "bar-stacked",
  "options": {
	"legend":  true,
    "labels":  true,
    "numbers": true
  },
  "data": [
	{ "label": "2012", "value": [1, 2, 3, 4] },
	{ "label": "2012", "value": [5, 6, 7, 8] },
	{ "label": "2012", "value": [9, 1, 2, 3] },
	{ "label": "2012", "value": [4, 5, 6, 7] }
  ]
}
```

```charty
{
  "title":   "Column chart",
  "caption": "With a caption",
  "type":    "column",
  "options": {
	"legend":  true,
    "labels":  true,
    "numbers": true
  },
  "data": [
	{ "label": "2012", "value": [199, 100] },
	{ "label": "2014", "value": [85, 217] }
  ]
}
```

```charty
{
  "title":   "Column (stacked) chart",
  "caption": "With a caption",
  "type":    "column-stacked",
  "options": {
	"legend":  true,
    "labels":  true,
    "numbers": true
  },
  "data": [
	{ "label": "2012", "value": [11, 2, 3, 4] },
	{ "label": "2012", "value": [5, 6, 7, 8] },
	{ "label": "2012", "value": [9, 1, 2, 3] },
	{ "label": "2012", "value": [4, 5, 6, 7] }
  ]
}
```

```charty
{
  "title":   "Donut chart",
  "caption": "With a caption",
  "type":    "doughnut",
  "options": {
	"legend":  true,
    "labels":  true,
    "numbers": true
  },
  "data": [
  	{ "label": "1", "value": 54746850 },
  	{ "label": "2", "value": 319169166 },
  	{ "label": "3", "value": 31281822 },
	{ "label": "4", "value": 142856940 },
	{ "label": "5", "value": 275231882 }
  ]
}
```

```charty
{
  "title":   "Pie chart",
  "caption": "With a caption",
  "type":    "pie",
  "options": {
	"legend":  true,
    "labels":  true,
    "numbers": true
  },
  "data": [
      { "label": "2012", "value": 1024 },
	  { "label": "2010", "value": 200 },
	  { "label": "2011", "value": 560 }
  ]
}
```

```charty
{
  "title":   "Ring chart",
  "caption": "With a caption",
  "type":    "rings",
  "options": {
	"legend":  true,
    "labels":  true,
    "numbers": true
  },
  "data": [
	  { "label": "2010", "value": 0.75 },
	  { "label": "2010", "value": 0.45 },
	  { "label": "2010", "value": 0.90 },
	  { "label": "2012", "value": 0.80 }
  ]
}
```

```charty
{
  "title":   "Section chart",
  "caption": "With a caption",
  "type":    "section",
  "options": {
	"legend":  true,
    "labels":  true,
    "numbers": true
  },
  "data": [
	  { "label": "2012", "value": 0.3 },
	  { "label": "2010", "value": 0.5 },
	  { "label": "2012", "value": 0.02 }
  ]
}
```

```charty
{
  "title":   "Line chart",
  "caption": "With a caption",
  "type":    "line",
  "options": {
	"legend":  true,
    "labels":  true,
    "numbers": true
  },
  "data": [
	  { "label": "Features",  "value": [ 10, 90, 20, 80, 60, 70, 30, 40, 0 ] }
  ]
}
```

```charty
{
  "title":   "Line chart",
  "caption": "With a caption",
  "type":    "line",
  "options": {
	"legend":  true,
    "labels":  true,
    "numbers": true
  },
  "data": [
	  {
		  "label": "Features",
		  "value": [ 231, 923, 234, 834, 345, 643, 464, 0, 743, 335 ]
	  },
	  { "label": "Sales",  "value": [ 10, 90, 20, 80, 30, 70 ] }
  ]
}
```

```charty
{
  "title":   "Bubble chart",
  "caption": "With a caption",
  "type":    "bubble",
  "options": {
	"legend":  true,
    "labels":  true,
    "numbers": true
  },
  "data": [
  { "label": "Test 1",  "value": [ 2455, 7665, 47, 70, 443, 2142 ] },
  { "label": "Test 2",  "value": [ 6321, 8765, 223, 873, 443, 2142 ] }
  ]
}
```

```charty
{
  "title":   "Scatter chart",
  "caption": "With a caption",
  "type":    "scatter",
  "options": {
	"legend":  true,
    "labels":  true,
    "numbers": true
  },
  "data": [
	  { "label": "2010",  "value": [ 10, 90, 20, 80, 30, 70, 20 ] },
	  { "label": "2015",  "value": [ 245, 765, 467, 70, 443, 242, 30 ] },
	  { "label": "2020",  "value": [ 995, 33, 85, 650, 56, 200 ] }
  ]
}
```

```charty
{
  "title":   "Review chart",
  "caption": "With a caption",
  "type":    "review",
  "options": {
    "labels":  true,
    "numbers": true
  },
  "data": [
    { "label": "2010", "value": 10 },
	{ "label": "2012", "value": 20 },
	{ "label": "2014", "value": 30 }
  ]
}
```
