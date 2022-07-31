# Sudoku solver using openCV and Tensorflow


### Steps to run the program
1. Clone the repo
2. Create a virtual environment using `python -m venv venv`
3. Install all the dependencies using `pip install -r requirements.txt`
4. Run the `sudokuMain.py` file

The program uses openCV to detect and extract the numbers on the board. It then uses tensorflow to identify the digits. Then backtracking algorithm is used to solve the board.

## Original Image
<img src="https://user-images.githubusercontent.com/56396463/182033863-1fcf0672-2c69-4fb2-b844-fcacf43dd2b5.jpg" width="600" height="600" />

## Preprocessing Image
<img src="https://user-images.githubusercontent.com/56396463/182034349-4524a3ff-77a3-4c96-b864-8db10db59970.png" width="600" height="600" />

## Identifying Contours
<img src="https://user-images.githubusercontent.com/56396463/182034139-c01bf694-ce3c-4e94-9770-54e3979c7c55.png" width="600" height="600" />

## Selecting Board
<img src="https://user-images.githubusercontent.com/56396463/182034412-338417b3-177d-4deb-9414-e804955fe415.png" width="600" height="600" />

## Predicting Numbers
<img src="https://user-images.githubusercontent.com/56396463/182034440-41f6a8b8-5894-4537-8a2a-d64e4f6bb18c.png" width="600" height="600" />

## Final Image
<img src="https://user-images.githubusercontent.com/56396463/182034447-1c518194-b42f-4c62-88ae-af678814c1ab.png" width="600" height="600" />
