![image](https://github.com/user-attachments/assets/59dbfa34-0b6d-4c46-8124-ca3ce9715ebb)# Virtual-Painting
Virtual AI painter using OpenCV and Mediapipe is an application that  tracks the movement of an object. Using this tracking feature the user can  draw on the screen by moving the object (which in our project is the human  hand) in the air, in front of the webcam. 

ABSTRACT

Virtual AI painter using OpenCV and Mediapipe is an application that tracks the movement of an object. Using this tracking feature the user can draw on the screen by moving the object (which in our project is the human hand) in the air, in front of the webcam.OpenCV (Open Source Computer Vision) - is a programming language library consisting of different types of functions mainly for computer vision.


INTRODUCTION
1.1GENERAL
Virtual AI painter using OpenCV and Mediapipe is an application that tracks the movement of an object. Using this tracking feature the user can draw on the screen by moving the object (which in our project is the human hand) in the air, in front of the webcam. This real time webcam data generated by tracking the movement of the object helps the user to draw simple things which are both interesting and challenging. OpenCV ( OpenCV (Open Source Computer Vision) - is a programming language library consisting of different types of functions mainly for computer vision. To explain in a simple language or in general way it is a library used for Image Processing. It is used mainly to do all the operations which are related to Images.


1.2OBJECTIVES OF THE RESEARCH

OpenCV is a library for images. It roughly supports all main programming languages. Commonly used in python and C++. OpenCv can be used to read or write an image, for image modification. Convert coloured to gray, binary etc. OPENCV is also an OPEN SOURCE.
Some of it’s notable applications are as follows:
1.Face detection
2.Multi-hand tracking
3.Detecting and tracking an object.
4.AutoFlip - pipeline to crop videos automatically.

LITERATURE REVIEW


 
Many methods are used for hand gesture recognition in real-time. Sayem Mohammad Siam, Jahidul Adnan Sakel, and Md. Hasanul Kabir has proposed a new method of HCI (Human-Computer Interaction), that uses marker detection and tracking technique. Instead of having a mouse or touchpad, two colored markers are worn on the tips of the fingers to generate eight hand movements to provide instructions to a desktop or laptop computer with a consumer-grade camera . They have also used the "Template matching" algorithm for the detection of markers and Kalman Filter for tracking. In the developed system uses a data glove-based approach to recognize real-time dynamic hand gestures. The data glove has ten soft sensors integrated in it that measure the joint angles of five fingers and are used to collect gesture data. Real-time gestures are recognized using techniques such as gesture spotting, gesture sequence simplification, and gesture recognition.

Furthermore, Mohamed Nasir Bin Mohamed Shukor, Lo Hai Hiung and Patrick

Sebastian entitled “Implementation of Colour Filtering on FPGA” proposed presents the construction of a real time hardware image processing system on Field Programmable Gate Array (FPGA). The chosen image processing algorithm is a single colour Filtering algorithm. This work utilizes Altera DE2 development board empowered by the Cyclone II FPGA paired with a 1.3 Mega pixel CMOS camera from Terasic Technologies. Verilog HDL is chosen as the hardware programming language for this system and its compiled using Quartus II program. The functionality of the algorithm is first verified in Matlab, simulating the expected output of the system before implementing it onto the FPGA development board. colour Filtering algorithms are successfully implemented on Cyclone II FPGA. The double band-pass filter algorithm is
found to be more effective to capture a wider spectrum of blue colour compared to that of a single band-pass filter algorithm. Currently work is done to quantify a performance metric for the system before implementing and testing the triple and quadruple band-pass filter algorithm to determine if there were further improvement could be achieved.


EXISTING SYSTEM
Writing Hand Pose Detection

Recognizing the position of the composing hand and recognizing it through other signals is an fundamental step in initializing airborne composing. Not at all like conventional writing, when the write moves down, and the write moves up, composing within the discuss isn't laid out as a writing arrangement. Events. The framework recognizes the position of a piece hand and recognizes it from a non- writing hand by tallying the number of raised fingers.



PROBLEM STATEMENT
Object recognition and tracking with real-time smart camera plays an important role in many modern vision applications such as work force tracking, intelligence surveillance, fire detection and many more. This research will be present a FPGA-based digital control for a Virtual Paint. Virtual Paint project use DE2 board, 5 megapixel 3 camera and a VGA monitor, which is uses the camera to capture hand movements, so you can hand in the air painting and displayed on a monitor, the whole process without using mouse or joystick like device. The main motivation of this project is to extract the gesture detection and color segmentation technique from CMOS camera sensor to perform virtual paint. The control algorithm will be using a Verilog language based on the use of logical state diagram.






5.1PROPOSED SYSTEM



In the Proposed System we have utilized the advancements, for example,open cv and media pipe. Hand motion acknowledgment can likewise be utilized for applications like modern robot control, communication through signing interpretation, in the restoration gadget for individuals with furthest point actual debilitation and so on. Hand motion acknowledgment finds applications in shifted spaces including virtual conditions, brilliant observation, gesture based communication interpretation, clinical frameworks and so on.


5.2MODULES

The modules are
1.Full compilation success 2.Camera not working 3.Remove iExposure function 4.Pin assignment for camera 5.Image for hidden camera
6.Random dot colour appear on monitor



5.3MODULE
1.FULL COMPILATION SUCCESS
Even successfully compiled and downloaded to the board, monitor running normally, but the camera still does not work.


2.CAMERA NOT WORKING
Replacement of the CCD control file, CCD_Capture.v, I2C_CCD_Config.v, I2C_Controller.v and Reset_Delay.v in submodule files has been made and CCD camera module still does not work. Recompile the compiler get an error because the main function module refers to original I2C_Controller.v to define a function.


3.REMOVE IEXPOSURE FUNCTION

Downloaded to the board running well, but still no success for camera function. Change on pin assignment for 1.5 megapixel camera pin out have been made and the compilation is successful .

4.PIN ASSIGNMENT FOR CAMERA

CCD_DATA bit wide for 1.5 megapixel camera is 12 bits. Modifications and

compilation successfully done. Download and run program, camera still cannot correctly read images, but the images rich in color than before.


5.IMAGE FOR HIDDEN CAMERA

If any movements detect over the lens, there will be on the screen moving

images. Figure 4.6 shows an image with hidden camera which image becomes dark.


6.RANDOM DOT COLOUR APPEAR ON MONITOR

After programming, the white screen appeared a few scattered dots but the longer run the more points occurs on the screen show that it is still not possible to control brush function. At this point, the image points increased significantly which is Red, Green and Blue dots appear randomly based on three colors corresponding palette.



RESULT AND DISCUSSION
The project has been created based on Verilog language which is run using the

Quartus 8.1 software. Collected information provided on the website and research paper about procedures and software operation is carefully analyzed. Based on collecting information, the main challenge is to set up cursor movement that not response to the specified target color. With a different interface for 1.5 megapixel camera properties, reallocation of the pin assignment for 1.5 megapixel camera have been made.


CONCLUSION
This application is capable of tough traditional writing strategies. It gets rid of the want to hold a cell telephone in hand to take notes, offering a easy manner to do the identical. The last intention is to create a computer imaginative and prescient device studying application that promotes human-computer interaction (HCI) moreover referred to as Human-laptop interaction (MMI)] which refers to the connection between humans and the PC or particularly the gadget. This undertaking allows the client to have interactive surroundings in which the customer can draw some thing he goals by the usage of choosing the preferred colors from the displayed collaboration.

FUTURE SCOPE



This work can be further improved by experimenting with different interpolation methods such as PyGame which includes a line drawing method that could help produce smoother and cleaner lines. In the same vein, a variety of brush shapes and textures can be implemented to make this application more robust.


REFERENCES


1.M. Petouris, A. Kalantzopoulos and E. Zigouris (2005), “An FPGA-based Digital Camera System Controlled from an LCD Touch Panel”, Electronics Laboratory, Electronics and Computers Div., Department of Physics, University of Patras, GR-265 00 Patras, GREECE.
2.Suh Ho Lee, Seon Wook Kim and Suki Kim (2004), “Implementation Of A Low Power Motion Detection Camera Processor Using A Cmos Image Sensor”,
ISCAS 2004, Department of Electronics Engineering, Korea University, Seoul, Korea.
3.Mohamed Nasir Shukor, Lo H. Liong and P. Sebastian (2007), “Implementation of Color Filtering on FPGA”, Electrical and Electronic Engineering , Universitiy Teknologi PETRONAS, International Conference on Intelligent and Advanced Systems.
4.Nai-Jian Wang, Sheng-Chieh Chang, Pei-Jung Chou (2012), “A Real-time Multiface Detection System, Implemented on FPGA” IEEE International Symposium on Intelligent Signal Processing and Communication Systems (ISPACS).
5.C. T. Johnston, K.T. Gribbon, and D. G. Bailey (2004), "Implementing Image

Processing Algorithms on FPGAs", Proceedings of the Eleventh
ElectronicsNew Zealand Conference, ENZCon’04.

6.A.Downton and D. Crookes (1998), "Parallel architectures for image processing," Electronics& Communication Engineering Journal , 1998.
7.Zoltan Pele, Tatj ana Samardzic, Neboj sa Maluckov and Nikola Teslic

(2003),"One Application of FPGA Integrated Circuits CMOS Camera and LCD Display Controller Design", 6th International Conference on 42
Telecommunications in Modem Satellite, Cable and Broadcasting Services, TELSIKS 2003, Nis, Serbia & Modenegro.
8.G. L. Foresti (1999), “Object recognition and tracking for remote video surveillance,” Circuits and Systems for Video Technology, IEEE Transactions on.
9.G. L. Foresti, C. S. Regazzoni (1994), “A change detection method for multiple object localization in real scenes”, Industrial Electronics, Control and
Instrumentation, IECON '94, 20 th International Conference on.

10.Jacky Baltes (2010), "Efficient Image Processing for Increased Resolution and Color Correctness of CMOS Image Sensors", 5th Robot World Cup Soccer
Games and Conferences.

11.Yakun Wu, Xiaohui Duan, Zhouhui Lian, Tiantian Shen, Shihu Zhao and Lei Van (2008), "The Design of Storage System for Digital Airborne Camera Based SOPC", Internation al Congress on Image and Signal Processing, CISP 2008, Sanya, Hainan, China .
12.S.Y. Chien, S. Y. Ma, and L. G. Chen (2002), “Efficient moving object

segmentation algorithm using background registration technique, ”IEEE Transactions on Circuits and Systems for Video Technology, Vol. 12, NO. 7,pp. 577-586.
13.Y. C. Chung, J. M. Wang, and S. W. Chen (2002), “Progressive Background

Image Generation, ” in Proc. of 15th IPPR Conf. on Computer Vision, Graphics

and Image Processing, pp. 858-865.

14.L. Maddalena and A. Petrosino (2008), “A Self-Organizing Approach to Background Subtraction for Visual Surveillance Applications,” IEEE Transactions on Image Processing, Vol. 17, NO. 7, pp. 1168 - 1177.43
15.S. S. Ghidary, Y. Nakata, T. Takamori, and M. Hattori (2000), “Human Detection and Localization at Indoor Environment by Home Robot,” in Proc. of
IEEE International Conference of Systems, Man, and Cybernetics, Vol. 2,

pp.1360–1365.

16.K. K. Ken, S. H. Cho, H. J. Kim, and J. Y. Lee (2005), “Detecting and tracking moving object using an active camera, ” in Proc. of 7th International
Conference of Advanced Communication Technology, ICACT , Vol. 2p,p. 817– 820.
17.D. Murray and A. Basu (1994), “Motion tracking with an active camera”,
IEEE Trans. On Pattem Analysis and Machine Intelligence, 16(5), pp. 449-459.

18.M. Irani, R. Roousso, and S. Peleg (1994), “Recovery of ego-motion using

image stabilization”, En Proc. Of the IEEE Computer Vision and Pattern Recognition, pp. 454-460.
19.B. Jung and G. S. Sukhatme (2010), “Detecting moving objects using a single camera on a mobile robot in an outdoor environment”, In the 8’Conf. on
Intelligent Autonomous Systems,pp. 980-987.

20.Ronald J. Tocci, Neal S. Widmer (2001), “Digital Systems: Principles and

Application”, 8th Edition, Prentice Hall.

21.Rafikha Aliana A. Raof, Norina Idris, Phaklen Eh Kan, Mohammad Nazri Md. Noor (2006), “Digital Electronics Design,” Prentice Hall.
22.Altera (2006), "DE2 Education and Development Board User Manual",
Version 1.4.

23.Terasic (2007), "TRDB-LTM 4.3 Inch Digital Touch Panel Development
Kit".

24.Altera (2008), "Creating Low Cost Intelligent Display Modules With an
FPGA and Embedded Processor", White Paper.


APPENDIX
import cv2
import numpy as np import os
import track_hands as TH


class VideoCamera():
def	init	(self,overlay_image=[],draw_color =(255,200,100)): self.cap = cv2.VideoCapture(0,cv2.CAP_DSHOW) self.cap.set(3, 1280)
self.cap.set(4,720) self.xp =0
self.yp =0
self.x1 = 0
self.y1 = 0
self.x2= 0
self.y2 = 0
self.brush_thickness =15
self.eraser_thickness =100 self.overlay_image = overlay_image self.draw_color = draw_color
self.detector = TH.handDetector(min_detection_confidence=0.85) self.image_canvas = np.zeros((720,1280,3), np.uint8) self.default_overlay = overlay_image[0]

def	del	(self): self.cap.release()


def set_overlay(self,frame, overlay_image): self.default_overlay = overlay_image[0] frame[0:125,0:1280] = self.default_overlay return frame

def get_frame(self, overlay_image):
frame = self.cap.read() frame = cv2.flip(frame, 1)
frame[0:125,0:1280] = self.default_overlay
frame = self.detector.findHands(frame, draw=True) landmark_list = self.detector.findPosition(frame, draw =False)

if(len(landmark_list)!=0):
self.x1, self.y1 =(landmark_list[8][1:]) #index self.x2, self.y2 = landmark_list[12][1:] #middle

my_fingers = self.detector.fingerStatus() if (my_fingers[1]and my_fingers[2]): self.xp, self.yp = 0,0
if (self.y1<125): if(200<self.x1<340):
self.default_overlay = overlay_image[0] frame[0:125,0:1280] = self.default_overlay self.draw_color = (255,0,0)
elif (340<self.x1<500): self.default_overlay = overlay_image[1]

self.draw_color = (47,225,245) frame[0:125,0:1280] = self.default_overlay elif (500<self.x1<640):
self.default_overlay = overlay_image[2] self.draw_color = (197,47,245) frame[0:125,0:1280] = self.default_overlay elif (640<self.x1<780):
self.default_overlay = overlay_image[3] self.draw_color = (53,245,47) frame[0:125,0:1280] = self.default_overlay elif (1100<self.x1<1280):
self.default_overlay = overlay_image[4] self.draw_color = (0,0,0) frame[0:125,0:1280] = self.default_overl
Ccv2.putText(frame, 'Color Selector Mode', (900,680)fontFace=cv2.FONT_HERSHEY_COMPLEX, color= (0,255,255), thickness=2, fontScale=1) cv2.line(frame, (self.x1,self.y1), (self.x2,self.y2), color=self.draw_color, thickness
if (my_fingers[1] and not my_fingers[2]): cv2.putText(frame, "Writing Mode", (900,680), fontFace=
cv2.FONT_HERSHEY_COMPLEX, color= (255,255,0), thickness=2, fontScale=1)
cv2.circle(frame, (self.x1,self.y1),15, self.draw_color, thickness=-1 if self.xp ==0 and self.yp ==0:
self.xp =self.x1 self.yp =self.y1
if self.draw_color == (0,0,0):
cv2.line(frame, (self.xp,self.yp),(self.x1,self.y1),color=

self.draw_color,thickness=self.eraser_thickness
cv2.line(self.image_canvas, (self.xp,self.yp),(self.x1,self.y1),color=self.draw_color, thickness=self.eraser_thickness)


else:
cv2.line(frame, (self.xp,self.yp),(self.x1,self.y1),color= self.draw_color, thickness=self.brush_thickness)
cv2.line(self.image_canvas, (self.xp,self.yp),(self.x1,self.y1),color= self.draw_color, thickness=self.brush_thickness)
self.xp , self.yp = self.x1, self.y1 frame[0:125,0:1280] = self.default_overlay
img_gray = cv2.cvtColor(self.image_canvas, cv2.COLOR_BGR2GRAY) imginv= cv2.threshold(img_gray, 50, 255, cv2.THRESH_BINARY_INV) imginv = cv2.cvtColor(imginv, cv2.COLOR_GRAY2BGR)
frame = cv2.bitwise_and(frame, imginv)
frame =cv2.bitwise_or(frame, self.image_canvas)
_,jpeg =cv2.imencode('.jpg', frame) return jpeg.tobytes()
def maiN overlay_image=[] header_img = "Images"
header_img_list = os.listdir(header_img) for i in header_img_list:
image = cv2.imread(f'{header_img}/{i}') overlay_image.append(image)

cam1 = VideoCamera(overlay_image=overlay_image)


while True:
ret, input_img = cam1.cap.read() input_img = cv2.flip(input_img,1)
my_frame = cam1.get_frame(frame=input_img, overlay_image= overlay_image)
cv2.imshow('out', my_frame) cv2.waitKey(1)
if	name	=="	main	" :
main()
from flask import Flask, render_template, Response import cam
import os import cv2

app = Flask(	name	,template_folder='templates')


overlay_image=[] header_img = "Images"
header_img_list = os.listdir(header_img) for i in header_img_list:
image = cv2.imread(f'{header_img}/{i}') overlay_image.append(image) @app.route('/')
def index():
return render_template('index.html') def gen():

cam1 = cam.VideoCamera(overlay_image= overlay_image) while True:
frame = cam1.get_frame(overlay_image=overlay_image) yield (b'--frame\r\n'
b'Content-Type: image/jpeg\r\n\r\n' + frame + b'\r\n\r\n')


@app.route('/video_feed') def video_feed():
return Response(gen(),
mimetype='multipart/x-mixed-replace; boundary=frame') if	name	== '	main	':
app.run(host='0.0.0.0', debug=False) #192.168.0.105



