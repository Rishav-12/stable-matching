# stable-matching
Implementing the Gale-Shapley algorithm to solve the Stable Marriage Problem

### How to Use
- Command line utility
- Simply add the preferences in the code as shown and run the file to get the results

``` code
preffered_ranking_men = {
	'1' : ['C', 'B', 'E', 'A', 'D'],
	'2' : ['A', 'B', 'E', 'C', 'D'],
	'3' : ['D', 'C', 'B', 'A', 'E'],
	'4' : ['A', 'C', 'D', 'B', 'E'],
	'5' : ['A', 'B', 'D', 'E', 'C']
}

preffered_ranking_women = {
	'A' : ['3', '5', '2', '1', '4'],
	'B' : ['5', '2', '1', '4', '3'],
	'C' : ['4', '3', '5', '1', '2'],
	'D' : ['1', '2', '3', '4', '5'],
	'E' : ['2', '3', '4', '1', '5']
}
```

This script is inspired by the video regarding Stable Matching by the YouTube channel The Simple Engineer
