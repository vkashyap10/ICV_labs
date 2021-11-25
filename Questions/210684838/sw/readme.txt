Steps to run:

1) directory where dataset should be places relative to notebooks
	Extract Dataset.zip in the sw folder
	Place the image for question 1: Name_Arial_72.jpeg in /sw/Dataset/ folder. This image is located in sw folder.

2) Run "module load anaconda3"

3) if opencv is not installed run the following commands :
	"pip install --upgrade pip setuptools wheel"
	"pip3 install opencv-python"

4) To run Jupyter notebook without GUI. (There is a separate notebook for each question) Run the following command from sw folder
	"ipython name_of_notebook"
	Example: "ipython Q5_motion.ipynb"

   Lunch jupyter GUI from sw folder:
	"jupyter notebook"


5) Directory where results are stored relative to notebooks:
	sw/Results/
	