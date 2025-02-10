# Elixir Enum.each List Modification Bug
This repository demonstrates a common misconception when working with lists and `Enum.each` in Elixir.  Attempting to modify a list in place within an `Enum.each` loop will not affect the original list.  This is due to Elixir's immutable nature.

The `bug.ex` file contains the erroneous code that tries to remove the element '3' from the list. The `bugSolution.ex` file provides the corrected approach using `Enum.filter` to create a new list.

This example highlights the importance of understanding Elixir's immutability and how to correctly manipulate lists.