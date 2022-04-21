# Preethiba-M--Bungee-Tech

Answer1:-

There are various approaches to doing this activity. Perhaps the most reasonable choice is to utilize the groupby work inside the fillna work.
First checking the average price of each product.
However, we can't utilize this line of code inside the fillna work. All things being equal, we will transform it somewhat by adding the change technique.
Finally checking the results by comparing the missing values in the price column with the values in the new column.
The missing value for tomato is loaded up with 3.12 which is the typical worth we determined beforehand. Additionally, the missing qualities for cucumber and onion are loaded up with the right typical worth.

Answer2:-

For the items that have a unit of kg, the deals sum values will be equivalent to deals amount values.
For the items that are sold in pieces, we want to remove the kg data from the portrayal and increase it by the deals sum.
We can utilize the where capacity to restrictively refresh the qualities. The weight data can be removed by utilizing the split capacity under the st accessor.
I would have rather not shown the code as text since it appears to be somewhat intricate in plain text.
The where capacity acknowledges a condition or a bunch of conditions. We can then appoint separate qualities for the lines that fit and don't fit the circumstances.
The condition is determined in the first inside the where work. The lines that fit the condition stay unaltered. In this way, the lines that don't have a unit of pieces will be kept something very similar.
The second and third lines determine how to refresh the columns that don't fit the condition. The subsequent line extricates the weight data from the item depiction. In the third line, this worth is duplicated by the deals amount.
We should really look at a portion of the outcomes.
The “butter-0.25” weighs 0.25 kg. In the last row, the sales quantity is 36 so the sales amount needs to be 0.25 * 36 which equals 9.

Answer3:-

Sort the teams by Red Cards, then to Yellow Cards

discipline.sort_values(['Red Cards', 'Yellow Cards'], ascending=False)
