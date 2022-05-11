# Find the Nearest Number in TouchDesigner
Example of a way to find the nearest number in a dataset/table in TouchDesigner

This is an idea of finding the nearest number from a column in a table to find where in the original table the nearest number exists to get other information from that table entry.

Updated to only test up to the nearest number of the sorted list - no need to test all the numbers higher than (and thus farther away from) the target/input number.

Notes:

* The current code favors the higher number if the target number is equally between two numbers.
* This example uses a CHOP Execute because it was the easiest for me to test it that way, but should work in other script-based DATs
