LicensePlateLicense plate detection is an image processing technology that uses a license
(number) plate for vehicle identification. The objective is to design and
implement an efficient vehicle identification system that identifies the vehicle
using the vehicle’s license plate. The system can be implemented on the
entrance of parking lots, toll booths, or any private premises like college, etc.
to keep the records of ongoing and outgoing vehicles. 

License plate of the vehicle is detected using various features of image processing library
open CV and recognizing the text on the license plate using python tool named as easyocr.
To recognize the license plate, we are using the fact that License plate of any vehicle has
rectangular shape. So, after all the processing of an image we will find the contour having
four points inside the list and consider it as the License Plate of the vehicle.




