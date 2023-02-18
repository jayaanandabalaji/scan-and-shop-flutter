
# Scan and shop machine learning app flutter 👋

Advanced scan and shop app built on Flutter that uses machine learning models using TensorFlow and Google Ml Kit flutter packages. The app uses barcode scanner, text detector and TFLite object detection to detect the object precisely.


## 🔗 Demo Link

Android Apk

<a href="https://mega.nz/file/d1xC3KZB#IZX6KWSR9HgvLFnB9PIos2CxLY_4kXpuhCxvASWbkRA"><img src="https://www.yt3dl.net/images/apk-download-badge.png" style="height:100px;"></a>


## 📸 Screenshots

![scan and shop app flutter screenshot 1](https://lh3.googleusercontent.com/pw/AMWts8Aj7PPFoWo-dKZxV4QK_sgZJ_VsS5h_PhxaU9qaVLz3L_AMP2cpYoAIuZvb3TjNWp704dJOxdB-PAyOcsQCz8XWJbkiPHLrOBs7pL9n0ElVJgldC2YUtbxa30J1FCP_qYZKDc84snqiRgeGwdRRS7o=w1154-h649-s-no?authuser=0)

**Barcode detection**

![scan and shop app flutter screenshot 2](https://lh3.googleusercontent.com/pw/AMWts8BOoUavI-rJMXFfqHgxR3NNFpHKc4m5dnbzLtM35c9uK2jZpN3o_XKiYFU7zcieMsn_cxxex_u97VdZIC8ucAL2sgxAsVUQgQTMfCe0z4Hp9jikjqoroJa64weo_u-Toq6iHFD2fL0Iz_Bo0flTKlA=w1154-h649-s-no?authuser=0)

**TensorFlow object detection**

![scan and shop app flutter screenshot 3](https://lh3.googleusercontent.com/pw/AMWts8BR0KJJyasbWB1aQqNgI9cuBnVnVPpFQqeDUkEZhXrRZRuuglaTb_UgoojCp9RTbxctfMKDxfMsmahVAKfJmwb3Con0syWjYenxTzWi_kwRy8rfXlzkf6X_HGdyAMAyM0yEzgylutrGm610NrXAMtA=w1154-h649-s-no?authuser=0)

**Text detection**

![scan and shop app flutter screenshot 4](https://lh3.googleusercontent.com/pw/AMWts8Ag5Tbvgm9DVHRSU_-wfieP5RAhlSCZa4iiHjemVjtSWWSv5mblPlcyvqhr8yoPIPYgcHrsew0-Zw_jdE59MNll4RiPIskx6tf8LzW2hEzhOpPGOxHCVs0cNNrM-qYJkFcp_-T7vA1uitpHhOGlZEg=w1154-h649-s-no?authuser=0)

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

