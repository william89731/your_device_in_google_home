# your devices in google home. free

Are you using [home assistant](https://www.home-assistant.io/) and [node red](https://nodered.org/)? well, this mini guide is for you !!

look below:

![20201228_144833](https://user-images.githubusercontent.com/68069659/103222947-7b871500-4925-11eb-8811-41b1bfc08ec4.gif)


# Nora nodes

Go [here](https://node-red-google-home.herokuapp.com/login), login and get your token ;

in **manage palette**  download **node-red-contrib-nora** ;

and these are the new nodes installed:

![immagine](https://user-images.githubusercontent.com/68069659/103479181-3b63de80-4dcc-11eb-85a9-0e7c1b888ba6.png)

and now we can expose our devices in google home.


# lights

Configure nora before building your flow:

![immagine](https://user-images.githubusercontent.com/68069659/103479553-c7770580-4dce-11eb-960b-e5177e8463d0.png)

with these two flows you now have your light in google home :

![immagine](https://user-images.githubusercontent.com/68069659/103479703-cabec100-4dcf-11eb-97e9-adbaf4cb8757.png)

code [here](https://github.com/william89731/your-devices-in-google-home.-free-/blob/main/luce%20flussi%20nora.txt)


# smartplug

same procedure as the lights:

![20210103_145237](https://user-images.githubusercontent.com/68069659/103480662-cd241980-4dd5-11eb-8c8b-21aaca955ff3.gif)

![immagine](https://user-images.githubusercontent.com/68069659/103480737-55a2ba00-4dd6-11eb-93ad-e74d9915fd19.png)

code [here](https://github.com/william89731/your-devices-in-google-home./blob/main/flow%20smartplug.txt)

# temperature and humidity sensor

in this case you have to use the scene node and create a routine that recalls it:

![immagine](https://user-images.githubusercontent.com/68069659/103481132-06aa5400-4dd9-11eb-9dd3-6d49596f12c0.png)

for your tts you can use the [cast](https://flows.nodered.org/node/node-red-contrib-cast) node


# thermostat

thanks to [rexer78](https://github.com/rexer78) for his collaboration and integration of his thermostat:

![20210103_155048](https://user-images.githubusercontent.com/68069659/103481681-dd8bc280-4ddc-11eb-9b3d-762d6eed2c41.gif)

![photo_2021-01-03_16-05-02](https://user-images.githubusercontent.com/68069659/103481862-b1247600-4ddd-11eb-889b-8d7bebe7b21c.jpg)

code [here](https://github.com/william89731/your-devices-in-google-home./blob/main/ClimaCameraNora%20(2).json)







