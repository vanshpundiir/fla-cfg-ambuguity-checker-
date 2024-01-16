vansh pundir project

1. Runs on Ubuntu - or similar environment
2. Install Anaconda. Refer [official docs](https://docs.anaconda.com/anaconda/install/index.html)
3. ``` git clone https://github.com/kr-prince/fitness_trainer.git``` or simply download the folder locally as zip, and extract it
4. Open Anaconda prompt and run the following commands
	```sh
	> cd fitness_trainer/app/
	> conda env create -f environment.yml
	> conda activate virtualFit
	```
4. Run the application by
	```sh 
	> streamlit run app.py 
	```