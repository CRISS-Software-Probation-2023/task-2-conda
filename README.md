# Task 2 - Conda

So imagine a situation in which you are working with tensorflow 2 (a deep learning library), but say you have a code that has some redundant features which can work only in tensorflow-1.10. But you do not want to downgrade your tensorflow version for doing this.

### __Introducing virtual environments!!!__

So, the point of a virtual environment is it helps in managing dependencies and isolating projects. One such popular virtual environment manager is conda. 

Another interesting point is that conda serves as the package manager for two Python packages - Anaconda and Miniconda. Anaconda allows you to create a virtual environment with libraries useful for data processing preloaded. The same is for miniconda, but it contains less libraries than anaconda.(which is very useful in our work)

Your further task is to read the medium post here : https://towardsdatascience.com/a-guide-to-conda-environments-bc6180fc533 (if the link does not let you in, try opening in incognito), till the managing environments part, and play around with conda, and create a virtual environment to solve the above problem and submit the commands used. (Note: the command will not be there directly in medium post, you have to search and think around.)

PS: The above problem can be solved using dockers too and it has the option of using any OS kernel you want too, but its completely isolated from the host unlike virtual environments. If you are more interested, you can search on this topic too!!!

You can see for instructions to install miniconda from the official website: https://docs.conda.io/projects/continuumio-conda/en/latest/user-guide/install/index.html

## Task
1) Create a conda enviroment with some name. Windows users will need to use the Minconda prompt, Mac and Linux Users can use their terminals.
2) Go to this website - https://pytorch.org/, scroll down to Install Pytorch, and select the appropriate options (including `Package: Conda`). _M1 users can select `Pip`_
4) Copy the text shown beside `Run this Command:`
5) Then in the Miniconda prompt for Windows users, and terminals for others, paste this text.
6) Further install the following packages:
    1) `matplotlib`
    2) `numpy`
    3) `jupyter`
    
This will be used for the next task. An environments.yml file must be generated and added to this repo. You can learn how to create one here: https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html
