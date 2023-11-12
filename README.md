# Sudoku
generate a sample sudoku board player
# def find_next_empty(puzzle):
    # find the next row, col on the puzzle that's not filled yet --> rep wiith -1
    # return row , col tuple ( or ( None , None ) if there is none)

    # keep in mind that we are using 0-8 for our indices
    
# def is_valid(puzzle , guess , row , col):
    # figures out whether the suess at the row/col of the puzzle is a valif guess
    # return True if is valid , False otherwise

    # lets start with the row:
    
    # now the column
    
    # and then the square
    # this is tricky , but we want to get where the 3x3 square starts
    # and iterate over the 3 values in the row/column
    
    # if we get here, these checks pass


# def solve_sudoku(puzzle):
    # solve sudoku using backtracking!
    # our puzzle is a list of lists, where each inner list is a row in our sudoku puzzle
    # return wether a solution exists
    # mutates puzzle to be the solution ( if solution exists)

    # step 1: choose somewhere on the puzzle to make a guess

    # step 1.1 : if there's nowhere left, then we're done becasue we only allowed  valid inputs
    
    # step 2 : if there is a place to put a number , then make a guess between 1 and 9
    # step 3 : check if this is a valid guess
    # step 3.1 : if this is valid, then place that guess on the puzzle!
    # now recurse using this puzzle!
    # step 4: recursively call our function
            
    # step 5: if not valid OR if our guess doesn't solve puzzle, then we need to
    # backtrack and try a new number
    # reset the guess

    # step 6: if none of the numbers that we try work, then this puzzle is unsolvable!


# draw the board
    <!-- example_board = [
        [3, 9, -1,  -1, 5, -1,  -1, -1, -1],
        [-1, -1, -1,    2, -1, -1,  -1, -1, 5],
        [-1, -1, -1,    7, 1, 9,    -1, 8, -1],

        [-1, 5, -1, -1, 6, 8,   -1, -1, -1],
        [2, -1, 6,  -1, -1, 3,  -1, -1, -1],
        [-1, -1, -1,    -1, -1, -1,    -1, -1, 4],

        [5, -1, -1, -1, -1, -1,    -1, -1, -1],
        [6, 7, -1,  1, -1, 5,   -1, 4, -1],
        [1, -1, 9,  -1, -1, -1,    2, -1, -1]
    ] -->
   




