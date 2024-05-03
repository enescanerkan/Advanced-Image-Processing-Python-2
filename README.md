# Advanced-Image-Processing-Python-2
This repository contains advanced image processing applications implemented in Python, providing a comprehensive set of tools for image analysis and manipulation.(Bu depo, Python'da uygulanan gelişmiş görüntü işleme uygulamalarını içerir ve görüntü analizi ve manipülasyonu için kapsamlı bir araç seti sunar.)

# 1) LAB_Color_Space_Masking
 This script performs object masking in an image using the LAB color space and morphological operations to find masks of objects in the image.
The script utilizes the LAB color space to isolate specific objects based on color information, enhancing segmentation capabilities. Morphological operations such as erosion and dilation are applied to refine the masks and extract object boundaries accurately.(Bir görüntüdeki nesneleri LAB renk uzayında maskeleme işlemi yaparak morfolojik işlemler yardımıyla görüntüdeki nesnelerin maskelerini bulmak.)

![LAB_Color_Space_Masking](https://github.com/enescanerkan/Advanced-Image-Processing-Python-2/assets/154825118/bbf2854a-2ee7-431b-b9ca-63ca10d2a296)


# 2) Fruit_Counter
This script performs fruit counting in an image using object-oriented programming approach. It utilizes Gaussian blur and Canny edge detection to preprocess the image and then applies contour detection to identify fruits. The script then draws circles around the detected fruits and annotates them with numbers indicating their order. Finally, it displays the original image with the fruit count.(Bu betik, nesne tabanlı programlama yaklaşımını kullanarak bir görüntüde meyve sayma işlemi gerçekleştirir. Görüntüyü ön işlemek için Gauss bulanıklığı ve Canny kenar tespiti kullanır ve ardından kontur tespiti uygularak meyveleri tanımlar. Betik daha sonra tespit edilen meyvelerin etrafına daireler çizer ve sıralarını belirten sayılarla işaretler. Son olarak, orijinal görüntüyü meyve sayısı ile birlikte görüntüler.)

![Fruit_Counter](https://github.com/enescanerkan/Advanced-Image-Processing-Python-2/assets/154825118/c203af51-1216-495c-9bde-217f6eb65a15)

# 3) Grabcut_Flower
The script utilizes the GrabCut algorithm to separate the flower from the background. First, it reads the image in BGR format and converts it to RGB. Then, it defines a region of interest (ROI) using a rectangle. Next, it initializes the GrabCut algorithm with the rectangle and updates the mask to separate the flower and background. Finally, it visualizes the segmented flower by removing the background and displaying the result.(Betik, çiçeği arka plandan ayırmak için GrabCut algoritmasını kullanır. İlk olarak, görüntüyü BGR formatında okur ve RGB formatına dönüştürür. Ardından, dikdörtgen bir bölgeyi (ROI) kullanarak ilgi alanını tanımlar. Sonra, GrabCut algoritmasını dikdörtgenle başlatır ve maskesini güncelleyerek çiçeği ve arka planı ayırır. Son olarak, arka planı kaldırarak ve sonucu görselleştirerek segmente edilmiş çiçek görüntülenir.)

![grabcut](https://github.com/enescanerkan/Advanced-Image-Processing-Python-2/assets/154825118/7db02cb4-f11b-442d-917d-70ccc365ca6d)

# 4) Object_Tracking
This repository contains a Python script that utilizes OpenCV for object detection in a video stream. Object detection is a fundamental task in computer vision, with applications ranging from surveillance to autonomous vehicles.(
Bu depo, bir video akışında nesne tespiti için OpenCV'yi kullanan bir Python betiği içerir. Nesne tespiti, gözetimden otonom araçlara kadar geniş bir uygulama alanına sahip olan bilgisayar görüşünde temel bir görevdir.)

Object detection is the process of locating and classifying objects within an image or video frame. In this script, we focus on detecting moving objects within a video stream. The algorithm consists of two main steps:
Background Subtraction: We use OpenCV's BackgroundSubtractorMOG2 algorithm to separate foreground objects (moving objects) from the background. This algorithm models each pixel as a mixture of Gaussian distributions to adapt to changing lighting conditions and scene dynamics.
Contour Detection: After obtaining the foreground mask, we use contour detection to identify and locate individual objects. Contours are outlines of objects in a binary image and can be used to extract features such as area, perimeter, and bounding boxes.(Nesne tespiti, bir görüntü veya video karesi içindeki nesneleri bulma ve sınıflandırma işlemidir. Bu betikte, bir video akışı içinde hareket eden nesneleri tespit etmeye odaklanıyoruz. Algoritma iki temel adımdan oluşur:
Arka Plan Çıkartma: Arka plan çıkartma işlemi için OpenCV'nin BackgroundSubtractorMOG2 algoritmasını kullanıyoruz. Bu algoritma, her pikseli değişen ışık koşullarına ve sahne dinamiklerine uyum sağlamak için Gauss karışımı olarak modellemektedir.
Kenar Tespiti: Ön plan maskesini elde ettikten sonra, kontur tespiti kullanarak bireysel nesneleri tanımlayıp konumlandırıyoruz. Konturlar, ikili bir görüntüdeki nesnelerin dış hatlarıdır ve alan, çevre ve sınırlayıcı kutular gibi özelliklerin çıkarılmasında kullanılabilirler.)

![6](https://github.com/enescanerkan/Advanced-Image-Processing-Python-2/assets/154825118/69e1346f-94cf-472d-af29-17ba300260f1)



