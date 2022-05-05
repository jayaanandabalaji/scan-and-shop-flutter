
# Scan and shop machine learning app flutter 👋

Advanced scan and shop app built on Flutter that uses machine learning models using TensorFlow and Google Ml Kit flutter packages. The app uses barcode scanner, text detector and TFLite object detection to detect the object precisely.


## 🔗 Demo Link

Android Apk

[![apk](https://www.yt3dl.net/images/apk-download-badge.png
)](https://github.com/jayaanandabalaji/scan-and-shop-flutter/blob/main/apk/app-release.apk?raw=true)


## 📸 Screenshots

![scan and shop app flutter screenshot 1](https://raw.githubusercontent.com/jayaanandabalaji/scan-and-shop-flutter/main/images/1.png)

**Barcode detection**

![scan and shop app flutter screenshot 2](https://raw.githubusercontent.com/jayaanandabalaji/scan-and-shop-flutter/main/images/2.png)

**TensorFlow object detection**

![scan and shop app flutter screenshot 3](https://raw.githubusercontent.com/jayaanandabalaji/scan-and-shop-flutter/main/images/3.png)

**Text detection**

![scan and shop app flutter screenshot 4](https://raw.githubusercontent.com/jayaanandabalaji/scan-and-shop-flutter/main/images/4.png)

**Other screens**

## Features

- The app uses flutter camera package for camera viewer and image_picker for selecting image.
- The image will be first checked for qr code and will go to qr code link if available
- If not available, then text will be checked to available in the image. if considerable amount of text is available, then search results based on the text will be shown.
- Finally, tensor flow object detection model will be used to detect the object.
- Google shopping website in webview has been used to show products search results.
## Enhance more

Currently, the app may show wrong object in certain cases due to limited availability in the TFLite model. The model and text will be present in the assets folder. The model has been limited to 1000 products. 

For further enhancement, the model with larger and better data set can be used and colloborated with google ML Kit TensorFlow custom model and be detected in cloud, which will also reduce the app size.
## Hire me
**Want to hire me on your upcoming or ongoing flutter project? 
Contact me on Fiverr**

[![fiverr](https://img.shields.io/badge/fiverr-1DBF73?style=for-the-badge&logo=fiverr&logoColor=white
)](https://www.fiverr.com/balajikannan03)



## License

Feel free to use the scipt for your project

[![MIT License](https://img.shields.io/apm/l/atomic-design-ui.svg?)](https://github.com/tterb/atomic-design-ui/blob/master/LICENSEs)

