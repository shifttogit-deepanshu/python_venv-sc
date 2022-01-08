# python_venv-sc

## make a respository and enter into it (use anaconda prompt afterwards)

<b>Step 1.</b> Create a new virtual environment in python
<pre>
python -m venv tfod
</pre> 
<br/>
<b>Step 2.</b> Activate your virtual environment
<pre>
source tfod/bin/activate # Linux
.\tfod\Scripts\activate # Windows 
</pre>
<br/>
<b>Step 3.</b> Install dependencies and add virtual environment to the Python Kernel
<pre>
python -m pip install --upgrade pip
pip install ipykernel
python -m ipykernel install --user --name=tfodj
</pre>
<br/>

<b>Step 4.</b> Open Jupyter Notebook from same environment
<pre>
jupyter notebook
</pre>

<b>Make sure to select the corrent virtual environment in Anacaonda
<br/>
<img src="https://raw.githubusercontent.com/shifttogit-deepanshu/python_venv-sc/main/forpyvenv.png">
