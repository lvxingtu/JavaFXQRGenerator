# JavaFXQRGenerator - JavaFX Version
<p>
QR code (Quick Response Code) is the trademark for a type of matrix barcode (or two-dimensional barcode) first designed for the automotive industry in Japan. A barcode is a machine-readable optical label that contains information about the item to which it is attached. A QR code uses four standardized encoding modes (numeric, alphanumeric, byte / binary, and kanji) to efficiently store data; extensions may also be used. Read more(Wikipedia) .
</p>
<p>
The QR Generator app is a Java FX version of the QR Generator app. It relies on XZing Library to build the QR and generate the 2D code image that can be exported to the local file system. To read the QR image, you will need to a QR Scanner or the many apps that can scan QR codes using mobile phone camera.
Below is a typical screen of the application running in a Win 7 machine.
</p>
<p>
<img src="https://www.dropbox.com/s/3o5h89hap22jjmm/shot_001.png?raw=1"/>
</p>
# How to use the application (.jar) / (Running the binaries)
<p>
A JRE 1.8 or later is required to run the application. Download the zip and unzip dist folder to a convinient folder. Ensure that the following directories are present in the decompressed folder 
<ul>
<li>+JavaFXQRGenerator - 1.0.3</li>
    <ul>
    <li>+libs<br></li>
    <ul>
      <li>commons-io-2.4.jar</li>
      <li>Filters.jar</li>
      <li>qrgen-1.0.jar</li>
      <li>zxing-core-1.7.jar</li>
      <li>zxing-j2se-1.7.jar</li>
    </ul>
    <li>+JavaFXQRGenerator.jar</li>
    </ul>
</ul>
These (folders)files are  neccessary for the app to run. If everyting is okay double clicking on the .jar file will launch the application. Enjoy
</p>
# Setting up the project in Netbeans/Eclipse or any other IDE / (Compiling the sources)
<p>
This application has been developed on Netbeans platfrom (Netbeans 8.0.2). Just download the sources, & point
netbeans to the downloaded sources. 
Enjoy!!


(C)ZiLabs 2015



