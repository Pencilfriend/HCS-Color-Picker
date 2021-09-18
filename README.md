		Using the program: 

	-Click the color pallet to adjust your hue and contrast.
	-Use the saturation slider to adjust the saturation value.
	-Input values into the Hue, Contrast, and Saturation Entry boxes then click the check mark next to the box to adjust those values.
	-Import HLS, RGB, or Hex Code's by pasting them in the bottom entry boxes and clicking the check mark.
	-Export HLS, RGB, or Hex Code's by copying them from the entry boxes and pasting them in a different program.


		Explanation:

	This is pretty self explanatory. A HLS style color picker which is scaled by contrast rather than luminosity. This means that colors left or right of each other will have the same contrast*. This program is more so meant to be a proof of concept than anything else and I would be happy to find that someone implements a system like this into actual drawing software or drawing software plugins.


	*Because you can't have half a point of luminosity the values of many points are rounded. This means they often won't be exactly the same but off by a few degrees of contrast. For all intents and purposes though, any two points horizontally aligned will be essentially the same in terms of actual contrast.

	This concept was inspired by https://youtu.be/gJ2HOj22gDo or "Something strange you should know about color | QUICK ESSENTIALS'' by Marco Bucci. This is a concept I and some other artists have known about but this video puts it very concisely. Essentially, contrast plays a big role in picking colors for drawing but the traditional color picking formats do not take contrast into account. I built this program to emulate what such a picker would act like. I say emulate because with the amount of shortcuts I took to make the picker it's hard to really say that I brought it fully into fruition.

	I'm very lacking in experience with python so my code is extremely messy and Ive taken many shortcuts to make up for my lack of mathematical knowledge and coding experience. Even so, perhaps someone will get some use out of this.
