# ESP32-WROOM32-Dev-Board
I decided a while back that I wanted to design, build and open source a WROOM32 ESP32 development board that was designed to plug a 2.1mm 5V power supply directly into it to drive high loads like hundreds of SK6812B's or 64x32 RGB Matrix Panels.

My revision 2 board works great, but uses a fairly expensive FT231XS FTDI USB Serial chip, so I thought I'd try to redesign it to use a cheap CH340C USB chip that has a built in oscillator to reduce parts.

My aim was to drive the CH340C from 3.3V and not 5V, and the data sheets suggests this is possible, but from my experience, it’s a terrible implementation.

So I have 2x CH340C folders…
Rev4 - CH340C driven from 3.3V
Rev5 - CH340C driven from 5V

Feel free to give the 3.3V version a whirl and if you can get ti working, please let me know how!

Anyway, this was just an experiment and it’s been a fun and frustrating journey, but I learnt a lot doing this and I’ve learnt stacks more since starting this project, so it’s time to let the files out into the wild so others can have a play with them. 

Enjoy!

# Buy me a coffee or back me on Patreon?
I love making and designing projects but sharing open source projects takes a lot of thought and time. I do it because I think it’s important to share knowledge and give back to the community like many have done before me.

If you find this project useful or want to see more open source projects like it, please consider buying me a coffee or backing me on Patreon to say thanks!

[![buymeacofee](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://www.buymeacoffee.com/YLVGbhJP0)
[![patreon](http://3sprockets.com.au/um/PatreonSmall.jpg)](https://www.patreon.com/unexpectedmaker)

# Unexpected Maker
http://youtube.com/c/unexpectedmaker

http://twitter.com/unexpectedmaker

https://www.facebook.com/unexpectedmaker/

https://www.instagram.com/unexpectedmaker/

https://www.tindie.com/stores/seonr/
