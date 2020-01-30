# Puzzle

This is a problem that I had to solve when I was applying for a Computer Vision engineer position at a company. Solved the problem, did not get the job though (-.-)

Anyways, in this problem, a set of JPEG puzzle pieces are provided and I was required to write a program to solve (reconstruct) the puzzle. Each set of puzzles has been uploaded into the Images folder in a .zip format file. The coordinate of each piece is indicated by the number of red and blue dots in the piece. The number of red dots denotes the column index, while the number of blue dots denotes the row index of the puzzle. For example, a piece with 1 RED and 2 BLUE dots indicate that the piece is located at column 1 and row 2 of the puzzle, as shown in Figure 1.

![fig1](https://user-images.githubusercontent.com/44108332/73421048-81fcbd80-435f-11ea-80ce-1bf13001eaac.PNG)

Input: from the following images in Fumo.zip,

![unpuzzle](https://user-images.githubusercontent.com/44108332/73420992-57ab0000-435f-11ea-81fe-39894ac2c711.PNG)

Output: the reconstructed image is expected to be something like this:

![fumo](https://user-images.githubusercontent.com/44108332/73420829-d3f11380-435e-11ea-9952-e6c53128ebf0.jpg)

There are two solution files; 1)Puzzle.py script and 2)Puzzle.ipynb jupyter notebook. Both solutions use the same method. 

### Puzzle.py

Run 'python Puzzle.py' and specify the puzzle set name. For example, 'python Puzzle.py fumo'. It will output the final and resized image into a new folder named '/result'

### Puzzle.ipynb

More interactive and explanation here. 

### Dependencies

1. OpenCV
2. Imutils
3. Pandas
4. Argparse*
5. Pathlib*


(* Only for Puzzle.py script)











