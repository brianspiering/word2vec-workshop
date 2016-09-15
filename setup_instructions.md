__Hi!__  
__Welcome 😄__ 

I'm glad that you decided to attend my workshop. I want you to get the most out of it.

There are 2 ways to access the materials for this workshop:

1. Install Python, clone the GitHub repository, setup the environment, and interactive with the Jupyter Notebooks.
2. Follow along while I present and reference material on the web.

Option 1 is the best. It allows you to "learn through doing". Option 2, aka standard lecture-style, works and seems easier, but trust me you'll have a deeper understanding of the material and enjoy our time together more if you go through the hassle of Option 1.

Setting up environments is still a source of _suck_. Given that people have different backgrounds, levels of experience, hardware, operating systems, software, and if we have entered the Age of Aquarius. 

Let's try to do the best we can...

Here is what works for me. I hope works for you:

1. Install Python via [Anaconda](https://www.continuum.io/downloads).
    - I like Python 3 but it shouldn't matter too much. Pick the flavor of Python that works for you.
2. Get the [word2vec-workshop repository](https://github.com/brianspiering/word2vec-workshop) by clicking on the green button "Clone or download"
    - You can just download the zip and unzip.
    - You can use the command line (if you are that I type)
    - Personally, I use the Desktop client. If you are on Windows machine, restart your machine after installing the Desktop client. Then "Open in Desktop"
3. Setup the environment. We are going to use Anaconda to automatically do it for us (fingers crossed)
    - Open terminal and change directory to the repository. That is`$ cd ~/github/word2vec-workshop` on my system. It should be something similar on yours.
    - Type this command `$ conda env create --force` in the terminal. That tells Anaconda to download and install all the Python packages you need.
    - Wait...
    - Then start your environment by typing this command `$ source activate word2vec` in the terminal.
4. Start the Jupyter Notebook 
    - Type this command `$ Jupyter Notebook`
    - Hopefully, it launches the notebook in your favorite web browser

Don't worry if this doesn't work for you - It doesn't mean that you are a bad person. You can try to Google/Stack Overflow but sometimes that might make it worse. It is better to introduce yourself to a neighbor and ask that person. Or ask for help from one of the staff (including Brian). 
