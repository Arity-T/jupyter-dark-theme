# Dark theme for Jupyter Notebook

Simple dark theme for Jupyter Notebook with exactly same functionality, only the colors have changed.
It goes well with the [dark version of chrome](https://chrome.google.com/webstore/detail/just-black/aghfnjkcakhmadgdomlmlhhaocbkloab).

![dark theme preview](preview.png)

## Installation

1. Find config directory. <br>
	In Windows, run the command `jupyter --config-dir` <br>
	In Linux it is `~/.jupyter`

1. In this directory create a `custom` subfolder if it doesn't exist.
1. Paste file `custom.css` there.
1. Update Jupyter Notebook (`ctrl + f5` to refresh css)

Also note, if you are already using theme from [jupyter-themes](https://github.com/dunovank/jupyter-themes) run command `jt -r` to return default theme and only then install this one :wink:
