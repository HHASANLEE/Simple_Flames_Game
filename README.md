# Simple_Flames_Game

The code starts by taking the first name, player 1 name.
It converts all of the letters into lower case and replaces any space with an empty string.
Next, it makes a list of all of the letters in player 1’s name.
The code then takes the second name, player 2 name.
It converts all of the letters into lower case and replaces any space with an empty string.
Next, it creates a list of characters from both players’ names.
The code starts by setting the proceed flag to True .
Then it calls the remove_match_char function on each list.
The remove_match_char function looks for common characters between both lists and removes them.
If no common characters are found, then proceed is set to False and the loop ends.
However, if common characters are found, then ret_list[0] stores the index of “*” in it (the border mark), ret_list[1] stores the flag value (True ), and star_index stores the index of where that character was found in p1_list or p2_list (depending on which list was used).
So after removing all of the common characters from each list, p1_list and p2_list
The code firstly takes in two player names as input.
Next, all of the letters in each name are converted to lower case.
Finally, any spaces are replaced with an empty string.
A list of these strings is then created.
Next, the remove_match_char function is called once for each list.
This function looks for a common character between the two lists and removes it.
If no common characters are found, the return value is [list1, False] and the proceed flag is set to True .
If a common character is found, the return value is [list3, True] and the proceed flag is set to False .
Finally, the concatenated list is returned with either [list3, True].
