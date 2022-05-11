# Find the Nearest Number in TouchDesigner
Example of a way to find the nearest number in a dataset/table in TouchDesigner

It takes a target number, looks through the list it is meant to compare it to, and finds the nearest number. Then, with that number, it can be compared to an unsorted list to find information tied to that number, including its index. Knowing the index in the original list will allow you to also pick table entries near it.

By no means is this meant to be efficient, just the first way I thought of using Python scripting

Notes:

* This example has a lot of print outs to confirm the code is working - they can be removed
* This example uses a CHOP Execute because it was the easiest for me to test it that way, but should work in other script-based DATs
