FROM python:3.7

# to upgrade a pip
RUN pip install --upgrade pip

# to install a jupyter notebook
RUN pip install notebook

# to install a qiskit
RUN pip install qiskit

# to install packages which is needed to run a code
RUN pip install ipywidgets matplotlib pylatexenc

# to fix a workspace
WORKDIR /home/workspace

# to run a jupyter notebook
CMD ["jupyter", \
	"notebook", \
	"--ip=0.0.0.0", \
	"--port=8888", \
	"--no-browser", \
	"--allow-root", \
	"--NotebookApp.token=''", \
	"--NotebookApp.password=''"] 
