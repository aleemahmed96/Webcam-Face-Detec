
Webcam-Face-Detect
==================

** PROBLEMS **
On windows, following problems were occured:
error: (-215:Assertion failed) !empty() in function 'cv::CascadeClassifier::detectMultiScale'
`anonymous-namespace'::SourceReaderCB::~SourceReaderCB terminating async callback

** FIXES **
Windows users having errors due to file path problems.

Run the program like this:

*python webcam_cv3.py*

alpython.com/blog/python/face-detection-in-python-using-a-webcam/


Update: Now supports OpenCV3. This change has been made by furetosan ( https://github.com/furetosan) and tested on Linux.

To run the OpenCV3 version, run python webcam_cv3.py haarcascade_frontalface_default.xml

