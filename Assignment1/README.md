# Assignment 1

The goal of this assignment is to develop an understanding of how the brain performs computations at the neuronal level. To do so, you will develop several models of a spiking neuron. By the end of this assignment, you should

- be comfortable with developing models of spiking neurons at different levels of abstraction, from the biologically plausible Hodgkin-Huxley model to the phenomenological LIF model;
- understand how neurons use their firing rate to represent continuous-valued information;
- understand the trade-offs involved in spike-based information representation.

1. First, follow the instructions below to set up a working python environment or make a local installation with the required packages:

- Create a CS computing account: https://resources.cs.rutgers.edu/docs/new-users/getting-started/
- Check iLabs' Status: https://report.cs.rutgers.edu/nagiosnotes/iLab-machines.html?v1
- Login through iLab web GUI: https://weblogin.cs.rutgers.edu
- Download the assignment, unzip, and navigate to the assignment folder in the terminal
- Create a Python virtual environment in your home directory by typing `python3 -m venv ~/.venvs/a1`
- Activate the virtual environment by typing `source ~/.venvs/a1/bin/activate`
- (Inside venv) upgrade pip and install deps by typing `python -m pip install --upgrade pip`
- Install the necessary packages by typing `pip install --no-cache-dir -r requirements.txt`
- type the following `pip install --index-url https://download.pytorch.org/whl/cpu torch==2.3.1 torchvision==0.18.1 torchaudio==2.3.1`
- Make a Jupyter kernel for this venv (so you can pick it in the UI) by typing `python -m ipykernel install --user --name a1 --display-name "A1 (venv)"`
- Troubleshooting: if the above steps do not work you can run `source /common/system/venv/python310/bin/activate` to use the existing python virtual environment on your ilab account. Alternatively, proceed via Google Colab or by downloading the required packages on your local machine. 
- Start coding by running `python -m jupyterlab`

2. Download the jupyter notebook titled "Assignment1_Questions.ipynb" on the ilab machine (if using ilab), or your local machine.

3. The assignment is a mix of conceptual and coding questions.

   - Implement your code in the space provided in the cells in the Jupyter notebook.
   - Write your answers to the conceptual questions in the space provided in the Jupyter notebook. Please use the Markdown formatting to enter your answers. You can find the basic Markdown syntaxes here: https://www.markdownguide.org/cheat-sheet/

4. You will submit the completed jupyter notebook on Canvas. Please note that we will **NOT** accept any additional code files, PDFs, etc. We will only grade your jupyter notebook. So make sure that the submitted notebook is self-contained and has all your answers. We will also NOT accept any late submissions, for any reason (including mysterious late-submission system glitches), unless there is a good reason for such a delay, that will be communicated to us well in advance (e.g., days before the due date.)

5. If you have conceptual questions regarding course content related to the assignment please email us at as4115@scarletmail.rutgers.edu or so504@scarletmail.rutgers.edu with "[CS425]" or "[CS525]" in the subject line. Note: we **will not** debug code, if you have an issue running something or run into syntax/logical errors it is your responsibility to solve these glitches.

Good luck and start early!
