#install opencv 


* download opencv2.4.11 
```
http://sourceforge.net/projects/opencvlibrary/files/opencv-unix/2.4.11/
```
* unzip opencv.2.4.11
```
sudo su
cd opencv.2.4.11
mkdir release
cd release
cmake -D CMAKE_BUILD_TYPE=RELEASE -D CMAKE_INSTALL_PREFIX=/usr/local ..
make
sudo make install
```

#install Scikit-learn

* Scikit-learn requires:
	Python (>= 2.6 or >= 3.3),
	NumPy (>= 1.6.1),
	SciPy (>= 0.9).

```
pip install -U scikit-learn
```
