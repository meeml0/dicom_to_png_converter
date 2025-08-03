# DICOM to PNG Converter
This project contains a Python script that reads medical image files in DICOM (.dcm) format, normalizes the images, and converts them to PNG format.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Features:
Reads image data from DICOM files.

Normalizes pixel values to the 0-255 range.

Resizes images to 256x256 pixels.

Saves the converted images as .png files in the specified folder.

Compatible with additional packages required to open JPEG Lossless compressed DICOM files.

Provides conveniences for running in Google Colab environment but also works on general Python interpreters.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Installation and Running

### Required Packages:-
To run the project, the following Python packages must be installed:
- pip install pydicom

- pip install pylibjpeg

- pip install pylibjpeg-libjpeg

- pip install pylibjpeg-openjpeg

- pip install opencv-python

- pip install tqdm

If you are using Google Colab, additionally install:

- !apt-get install -y gdcm

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Usage

1) Set the d_dcm variable to the folder path containing the DICOM files.

2) Set the d_png variable to the folder path where the converted PNG files will be saved.

Run the script. All .dcm files in the folder will be converted to PNG format and saved in the specified directory.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Notes

- The code is written to work in basic Python environments and on all common operating systems.

- However, to open JPEG Lossless compressed DICOM files, some extra libraries (e.g., pylibjpeg, gdcm) need to be installed.

- It is easy to run in Google Colab, and commands for installing the required packages are provided.

- If you run it locally, make sure you have installed the necessary libraries correctly.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Contributing

You can contribute to the project or report issues by opening a pull request or an issue.








# DICOM'dan PNG'ye Dönüştürücü

Bu proje, tıbbi görüntü formatı olan **DICOM (.dcm)** dosyalarını okuyup, bu görüntüleri normalize ederek **PNG** formatına dönüştüren Python tabanlı bir script içerir.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Özellikler:

- DICOM dosyalarındaki görüntü verilerini okur.
- Piksel değerlerini normalize ederek 0-255 aralığına getirir.
- Görüntüleri 256x256 boyutuna yeniden boyutlandırır.
- Dönüştürülmüş görüntüleri `.png` formatında belirtilen klasöre kaydeder.
- JPEG Lossless sıkıştırmalı DICOM dosyalarını açmak için gerekli olan ek paketlerle uyumludur.
- Google Colab ortamında çalıştırılmaya özel kolaylıklar sağlar, ancak genel Python derleyicilerinde de çalışabilir.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Kurulum ve Çalıştırma

### Gerekli Paketler:

Projeyi çalıştırmak için aşağıdaki Python paketlerinin kurulması gerekmektedir:
- pip install pydicom
- pip install pylibjpeg
- pip install pylibjpeg-libjpeg
- pip install pylibjpeg-openjpeg
- pip install opencv-python
- pip install tqdm

Google Colab kullanıyorsanız ayrıca kurulması gereken Paketler:
- !apt-get install -y gdcm

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Kullanım:

1) d_dcm değişkenine DICOM dosyalarının bulunduğu klasör yolunu,
2) d_png değişkenine ise dönüştürülen PNG dosyalarının kaydedileceği klasör yolunu girin.

Scripti çalıştırın. Klasördeki tüm .dcm dosyaları PNG formatına dönüştürülerek belirtilen klasöre kaydedilecektir.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Notlar:

- Kod, temel Python ortamlarında ve tüm yaygın işletim sistemlerinde çalışacak şekilde yazılmıştır.

- Ancak JPEG Lossless sıkıştırmalı DICOM dosyalarını açabilmek için bazı ek kütüphanelerin (ör. pylibjpeg, gdcm) kurulması gerekir.

- Google Colab ortamında çalıştırılması kolaydır ve ek paket kurulumu için gereken komutlar sağlanmıştır.

- Eğer yerel bir ortamda çalıştırıyorsanız, gerekli kütüphaneleri doğru kurduğunuzdan emin olun.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Katkıda Bulunma:

Projeye katkıda bulunmak veya hata bildirmek için pull request veya issue açabilirsiniz.




