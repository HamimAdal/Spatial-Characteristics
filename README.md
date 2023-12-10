# Spatial Characteristics

This is a design of a user-space interacting framework that works as a mediator between the user and smart space, shifting the level of abstraction from device level (e.g., smart light, smart speaker, smart HVAC, etc.) to a set of properties called spatial characteristics (i.e., illumination, sound, temperature, etc.) that influence the physical environment. The goal is to realize user interactions in terms of spatial characteristics where the user interacts with properties of the space (e.g., ``Alexa, provide me illumination for reading a book on my bedroom desk") instead of controlling individual devices (e.g., ``Alexa, set the brightness of the bedroom lamp to level 5"), making the user request more natural and personalized.

<table>
  <tr>
    <td>Figure 1: Concept of Spatial Characteristics and the factors impacting them.</td>
  </tr>
  <tr>
    <td><img src="https://github.com/HamimAdal/Spatial-Characteristics/blob/main/Figures/conceptual%20diagram.jpg" width=800 height=400></td>
  </tr>
</table>


In our proposed model (Figure ~\ref{fig:char}), personal devices (on behalf of the user) view the space not as a collection of IoT devices that can be discovered and controlled by the user, but as a set of spatial characteristics which can be inspected and regulated by the space on the user’s behalf. Exercising control over a spatial characteristic is centered on controlling the physical devices located in that space, including the physical sensors that monitor the state of the environment.  The latter are particularly important in the presence of uncontrollable factors (invisible sources and inaccessible devices) that can influence the space and when user requests span an interval of time or are relative to changing user location.  Figure ~\ref{fig:char} denotes such situations as the dynamics (user location and time) of user needs.

Spatial characteristics are location-specific having (mostly scalar values) that vary across locations in space. As such, users typically interact with a characteristic at a particular location—either the user location or some location of their choice. When the value of a characteristic must be maintained over time with respect to the changing user location, the space needs to continuously reevaluate the controls given to the relevant devices. For example, a user enjoying a piece of music with a level of sound (e.g., 60db) in the living room may walk into the kitchen and should be able to listen to the song at the same level without explicitly requesting the audio to shift to the speakers in the kitchen, leaving the space to figure out the correct speaker settings and adjust the same sound level (which is 60db) in the new location. 

In a different scenario, the user may expect the space to control the state of a particular characteristic for a duration of time, e.g., the level of illumination, temperature, and humidity in the sunroom during the daytime hours.  Such requests tend to be repetitive, of longer duration, and independent of the user location, i.e., they exhibit different dynamics.


Uncontrollable factors, invisible sources, and inaccessible devices, add significant levels of complexity in satisfying such user requests. Sunlight coming from a transparent window or outside weather can continuously affect the illumination and temperature levels of the sunroom. Also, when a space is equipped with physical devices operated by a third party; they may influence the state of a particular characteristic yet exist outside the control of the smart space. A neighbor’s floodlight can have an impact on the nighttime conditions in the sunroom.
