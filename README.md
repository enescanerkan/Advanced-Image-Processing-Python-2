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




