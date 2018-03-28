A GUI program to display the result from a image segmentation algorithm named  [GrabCut](http://pages.cs.wisc.edu/~dyer/cs534-fall11/papers/grabcut-rother.pdf).

This program is a course project during my second year in university, so some functions in outdated packages may be not supported by the newest packages.

##### Requirements

​	python 2.7

​	matplotlib

​	OpenCV

​	scikit-learn

​	PIL

​	wxPython (GUI package)

​	igraph

​	**Note**: To install igraph package, run **pip install python-igraph**. Do **not** run **pip install igraph**

##### Usage

```
#Organization
./
	|--grab.py - call the GrabCut function in OpenCV.
	|--grabcut.py - use igraph and scikit-learn to implement GrabCut function.(Not a good implementation)
	|--main.py - build the GUI architecture by wxPython.
#Run
	python main.py
```

##### Example

![3](/home/papa/Documents/Trash/GrabCut/1.gif)

![1](2.gif)