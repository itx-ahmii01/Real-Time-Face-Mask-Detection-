Real Time Mask Detector
created by
Rana Abdul Muneem	19L-1046
Muhammad Shariq		19L-1060
Muhammad Ahmad		19L-1199
Behzad N. Khokher	19L-2744

Included files:
	README.txt
	MaskDetector.ipynb
	RealTime.ipynb
	mask_detector.model
	OpenCV_face_detector/architecture.prototxt
	OpenCV_face_detector/weights.caffemodel
	OpenCV_face_detector/video-not-working.png

To avoid errors, please make sure all files are present


MaskDetector.ipynb contains code for building, training, testing, and exporting a mask detection model using mobilenetv2
Trained model is exported as mask_detector.model
RealTime.ipynb uses constructed model along with face detection model provided by OpenCV to perform face mask detection
in realtime

Simply open RealTime notebook and run. Please make sure required dependencies are installed.