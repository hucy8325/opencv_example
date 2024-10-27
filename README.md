# opencv_example
import cv2

# 创建一个简单的黑色图像
image = cv2.imread('/home/hcy/opencv/釉瑚.png')  # 替换为您的图像路径
if image is None:
    print("Could not open or find the image!")
    exit()

# 显示图像
cv2.imshow('Image', image)
cv2.waitKey(0)
cv2.destroyAllWindows()