# Lego Set Explorer

## Data Dictionary
<b>set_id:</b> Official LEGO item number

<b>name:</b> Name of the LEGO set

<b>year: </b> Release year

<b>theme:</b> LEGO theme the set belongs to

<b>subtheme:</b> Subtheme within the theme

<b>themeGroup:</b> Overall group the theme belongs to

<b>category:</b> Type of set pieces	Number of pieces in the set

<b>minifigs:</b>Number of mini figures included in the set

<b>agerange_min:</b> Minimum age recommended

<b>US_retailPrice:</b> US retail price at launch

<b>bricksetURL:</b> URL for the set on brickset.com

<b>thumbnailURL:</b> Small image of the set

<b>imageURL: </b> Full size image of the set

## Important KPIs

<b>1.Total Sets</b> 

```
Total Sets = DISTINCTCOUNT(lego_sets[set_id])
```

<b>2.Total Groups</b>

```
Total Groups = DISTINCTCOUNT(lego_sets[themeGroup])
```

<b>3. Average Age </b>

```
Avg. Age = AVERAGE(lego_sets[Age])
```

<b>4. Average Price </b>

```
Avg. Price = AVERAGE(lego_sets[US_retailPrice])
```

<b>5. Average Pieces </b>

```
Avg. Pieces = AVERAGE(lego_sets[pieces])
```

