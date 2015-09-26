This repository is contains information related to the tool ExampleTool presented Foundations of Software Engineering, 1901. The tool was originally presented in  https://cs.uwaterloo.ca/~obaysal/icse14_kononenko_preprint.pdf.

This repository is not the original repository for this tool. Here are some links to the original project:

The Official Project Page, including source code
The Tool on the Visual Studio Gallery
A Video of the Tool
In this repository, for ExampleTool you will find:

:x: Source code (not available)
:white_check_mark: The original tool (available)
:white_check_mark: A slightly modified version of the tool Esha Sharma got working (available)
This repository was constructed by Esha Sharma and Yihuan Dong under the supervision of Emerson Murphy-Hill. Thanks to Jane Smith and John Doe for their help in establishing this repository.


dash
====

About this project
------------------

Dash is a project led by [Olga Baysal](https://cs.uwaterloo.ca/~obaysal/) from
the University of Waterloo to help provide Mozilla developers with customized
dashboards that summarize their current Bugzilla issues. The project was started
after investigating the <a href="https://wiki.mozilla.org/Bugzilla_Anthropology">Mozilla Anthropology</a>
interviews. The project is in active development; if you have any questions,
comments, or suggestions, please <a href="mailto:obaysal@uwaterloo.ca?Subject=Feedback%20on%20Developer%20Dash"
target="_top">get in touch</a>.

  * The most related article relevant to this project is [here](developer_dash_ieeesoft13.pdf)
  * Our analysis of the Mozilla Anthropology Interviews is <a href="http://www.cs.uwaterloo.ca/research/tr/2012/CS-2012-10.pdf">here</a>.
  * The original version of this dashboard, which relies on Bugzilla REST API,
can be found <a href="http://claw.cs.uwaterloo.ca/dash">here</a>.
  * This version was created by <a href="https://cs.uwaterloo.ca/~okononen">Oleksii Kononenko</a>

Installation
------------

The server side requires Apache, with Python CGI scripting enabled.  The server Python installation also requires:

  * pytz: ```pip install pytz```
  * HTML: Found at [http://www.decalage.info/files/HTML.py-0.04.zip](http://www.decalage.info/files/HTML.py-0.04.zip)
You may need to delete ```python\Lib\site-packages\html.py``` before you run
```setup.py```

