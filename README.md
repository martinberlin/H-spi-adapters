## Small SPI adapters

H stands for Hardware.

In this repository we will keep PCB designs done in KiCAD for SPI adapters we use. 

### ESP32-C3 24 pin Good-Display epaper controller with touch

Along with the 220AC-3.3DC converter with Latch relay this PCB can be used to make a light wall switch but is also great to experiment with SPI epapers and UX design. Here a preview showing front and back Cooper layers plus 3D view:

![Fr cu](https://user-images.githubusercontent.com/2692928/218306190-1fd7f464-35e3-41fd-bcc0-3b9c66186e00.png)

![Back cu](https://user-images.githubusercontent.com/2692928/218306195-ac2b6d8f-d0d7-4895-9ebe-9b89c95623e5.png)

![Silkscreen](https://user-images.githubusercontent.com/2692928/218306225-3c7058b8-ede4-449a-a41e-439912fd12bd.png)

![3D-view](https://user-images.githubusercontent.com/2692928/218306248-25cc7c8f-0f09-4286-9bbc-a478964cdd3d.png)

This PCB will be offered only in our [Lectronz store](https://lectronz.com/stores/fasani/). Last unit is available only till end of February 2023.

### UC8156 SPI adapter for Tinypico

Beginning of 2022 I started to learn KiCAD and get more into Hardware. My intention is to help people with their own projects and make new versions, first of existing adapters, to make them smaller and optimize certain things that, I think, could be make better.

My first product in this direction is the [Tinypico SPI adapter for UC8156 displays](https://www.tindie.com/products/fasani/tinypico-small-uc8156-epaper-hat).

![uc8156-adapter-small](https://user-images.githubusercontent.com/2692928/159118394-60defa3e-656c-4e11-a65b-d45414860087.JPG)

The supported [displays are sold by German company PlasticLogic](https://www.plasticlogic.com/sampleshop).

## Goodisplay SPI adapter

This is currently being designed. There is a 3 pad's jumper in the PCB, this is what they called RESE option, different epapers might need either the 4.7 soldered to the center, others the 3. If this is wrong selected the epaper might fail to refresh.
Please check what is the right choice for your model downloading the [DESPI-co2 datasheet](https://www.good-display.com/companyfile/DESPI-C02-Specification-29.html).

## Other SPI adapters that might come

Goodisplay Tinypico ESP32 HAT (Idea) In Production, needs revisions from a higher hierarchie ;)

![Good display Tinypico HAT](assets/goodisplay-spi.png)

Other epapers.

Intention to make a mini-parallel epaper driver (Will be super hard design)


For more information and currect projects please check:

[https://fasani.de/pcb-design-projects](https://fasani.de/pcb-design-projects)
Most of the PCB's where designed using latest version of KiCAD when writing this lines ( V. 6 )
