# homework_3.1

What are the arguments of usb_cam-test.launch? 

Els arguments del fitxer launch varien en funció del node.
Pel node usb_cam:
- video_device: amb valor /dev/video0
- image_width: amb valor 640 
- image_height: amb valor 480
- pixel_format: amb valor yuyv
- camera_frame: amb valor usb_cam
- io_method: amb valor mmap

Pel node image_view:
- autosize: amb valor true
