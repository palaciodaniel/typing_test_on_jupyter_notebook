[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/palaciodaniel/typing_test_on_jupyter_notebook/main?filepath=https%3A%2F%2Fgithub.com%2Fpalaciodaniel%2Ftyping_test_on_jupyter_notebook%2Fblob%2Fmain%2Ftyping_test_on_jupyter.ipynb)
# Typing Test on Jupyter Notebook

It is just a small program I wrote yesterday during the afternoon. It will generate a random text that you need to write as fast as possible, but without sacrificing precision. At the end you will get your Words per Minute (WPM) and a comparison with the average typing speed.

The most challenging part was to make Jupyter Notebook to correctly display the randomized text output. Given that it is a long string, it tended to cut words in the middle when changing lines. I considered several alternatives, like using Regular Expressions or the pprint module, but in the end the only effective approach I found was to create a copy of the randomized text and to add it "\n" newlines to avoid this inconvenience.

<p align="center"> 
<img src="https://images.unsplash.com/photo-1586227740560-8cf2732c1531?ixlib=rb-1.2.1&auto=format&fit=crop&w=828&q=80">
</p>

## Instructions

To run the program, you can either enter the following [link](https://mybinder.org/v2/gh/palaciodaniel/typing_test_on_jupyter_notebook/main?filepath=https%3A%2F%2Fgithub.com%2Fpalaciodaniel%2Ftyping_test_on_jupyter_notebook%2Fblob%2Fmain%2Ftyping_test_on_jupyter.ipynb) or click on the **Launch Binder** icon. Once the Jupyter Notebook is loaded (it can take a while!), just go to the **Cell** tab on the menu and press **Run All**.

If you want to repeat it, go to the **Kernel** tab and press **Restart and Run All**.

Depending on your typing speed, the test might take between two to four minutes to complete. Consider there is a strong emphasis on writing the text correctly; if you commit many mistakes you will be required to start all over again, so be warned in advance.

## Credits

Code written from scratch by **Daniel Palacio**.

Image of girl with a notebook by **Kristin Wilson** - *Unsplash.com* - (https://unsplash.com/photos/z3htkdHUh5w)
