# Thunderobot ML703 Driver guide

Guide for installing and translating the driver of Thunderobot ML703 driver.

## Mouse info

![Image preview](images/mouse_preview.jpg)

* Buy link: [aliexpress](https://aliexpress.ru/item/1005002361372571.html)
* Official website: https://www.thunderobot.com/

## Installing driver

* link for drivers: https://www.thunderobot.com/service/download

#### Guide for downloading driver

![Step 1](images/driver_download_1.jpg)
![Step 2](images/driver_download_2.jpg)

Use Google Chrome and built-in language translator.

## Interface translation and localization

<details>
  <summary>English UI</summary>

  ![EN UI 1](images/en_ui_1.jpg)
  ![EN UI 2](images/en_ui_2.jpg)
  ![EN UI 3](images/en_ui_3.jpg)
  ![EN UI 4](images/en_ui_4.jpg)
  
</details>

Thanks to the manufacturer - they moved all text data to `text.xml` file. So you can translate it using any online service like Google or Yandex translator - or even ChatGPT.

* Go to drivers folder (`C:\Program Files (x86)\ML703 Gaming Mouse`)
* copy and backup original text file to another folder
* close the app from tray
* replace the `text.xml` with your language file:
    * [original CN text.xml](text_files/cn/text_cn.xml)
    * [english version of UI - text.xml](text_files/en/text_en.xml)
    * [russian version of UI - text.xml](text_files/ru/text_ru.xml)

**Don't forget to rename file to `text.xml` and replace it inside of installation folder** 
