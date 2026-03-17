

1. Human-computer interaction (touch designer)

Prototype development
In order to realize camera interaction and keyboard interaction in TouchDesigner, it is necessary to combine the characteristics of real-time visualization, and the exhibition with interactive elements will be more attractive to visitors. At the beginning, I （yuki）tried to use touch designer to make visual videos, but it was lack of interactivity, so I began to learn the interaction between keyboard and camera.
 
Camera interaction is primarily done by capturing camera input (such as the user's movements, colors, etc.) and mapping its data into visualizations. The implementation process is as follows: First add the camera TOP (Video Device In TOP), In TouchDesigner, create a 'Video Device in TOP' node. Select your camera device in the parameters window and adjust the resolution, frame rate and other parameters to optimize performance. The video input is then processed using various TOP nodes (such as Threshold TOP, Blur TOP, Edge TOP). In addition, using 'Transform TOP', 'Feedback TOP', etc. to map data to geometric deformation, particle system or dynamic material, the effect is to adjust the direction of particle emission according to the position of the user's movement.
To demonstrate this effect, our team borrowed kinder 2.0 cameras from schools for testing.
 
Keyboard interaction involves listening to keyboard input to trigger specific events or parameter changes. First create the Keyboard In CHOP and add the 'Keyboard In CHOP' node, which will listen for keystrokes on the keyboard. In parameter Settings, you can choose to listen for all keys or a specific key. The pressed or released state of each key is displayed in the CHOP channel, and the key signal is processed as a trigger pulse using Logic CHOP. At the same time, map the key state to other nodes。
 


Keyboard interaction （标题）

展示三张效果图 + 两个视频（横版）


Keyboard interaction: Item breakage and restoration（标题）

展示两张效果图 + 1个视频（竖版）


Camera human interaction（标题）

展示1张效果图 + 1个视频（竖版）

xbox Motion sensing interaction（标题）

展示3张效果图（竖版） + 三张效果图（横版）


Derivative item: Postcard illustration（标题）

展示6张效果图（竖版）