# Spatial Characteristics: A user-space interactive interface to conduct interactions in Smart Space.

**Today's Smart Home: Users control smart appliances through personal devices (e.g.,virtual assistants in smartphones/smart displays/smart echos) to acquire service.**

In the present smart world, virtual assistants such as Alexa, Siri, and Google handle user requests with reference to specific devices within the smart space. For instance, a typical interaction might involve a user instructing Alexa to adjust the “reading room lamp” to a certain level or modify the volume of the “bedroom speaker”. This type of interaction presents challenges such as:

-- Users need to have prior knowledge of the device’s type, name, and location to utilize a service at a specific location. With the rise in the number of smart devices, it is becoming increasingly difficult to remember and refer to each device by its name. 

-- Further challenges surface when users, accustomed to their home environment, find themselves in a new setting and aim to interact with the space similarly. Alice, for instance, might be well-versed with the location of devices in their homes, but the chances of accurately pinpointing the placement of analogous devices in a smart hotel room are less likely, and burdensome. 

The practical result is that users use only a small fraction of the available features and reach a saturation point in terms of the acquisition of new devices.

# The Concept of Spatial Characteristics: Users interact with the properties of the space.

We focus on the category of interactions that engage with properties of the space that directly impact the user experience, rather than on device-specific features. 

-- The starting point is the concept of spatial characteristics. A spatial characteristic can be defined as a perceivable property of a space that users can examine and control. Examples of spatial characteristics include temperature, illumination, sound level, security, and privacy, each of which can be regulated by specialized devices within the space. 

-- We envision that a significant portion of interactions with a smart space will occur at the level of spatial characteristics. Such interactions are commonly facilitated by the user's personal device (such as a smartphone, smartwatch, etc.), smart speaker (echo dot), smart display (echo show), etc. 

-- Under this interface, when a person wishes to read a newspaper, they would not attempt to control specific lights in the room. Instead, they would request a certain level of illumination at their location. This request could be fulfilled in various ways, depending on the location and context. For instance, on a sunny day at the breakfast table, smart glass and ambient lighting might be adjusted by the space to provide adequate illumination. Conversely, in a basement playroom, more lights might need to be activated by the space to achieve the desired result. 

-- Regardless of the location- be it a home, office, hotel, or other setting---the user's request remains consistent with the same interface only caring about what they expect from the environment. It is the collective responsibility of the personal device and the smart space to deliver the requested outcome by choosing an appropriate set of devices with the correct device configurations, making the user request more natural and personalized without engaging them in the process.

Figure 1 illustrates the concept of the Spatial Characteristics model and the factors affecting them:


<table>
  <tr>
    <td>Figure 1: Concept of Spatial Characteristics and the factors impacting them.</td>
  </tr>
  <tr>
    <td><img src="https://github.com/HamimAdal/Spatial-Characteristics/blob/main/Figures/conceptual%20diagram.jpg" width=800 height=400></td>
  </tr>
</table>

In our proposed model:

-- Personal devices (on behalf of the user) view the space not as a collection of IoT devices that can be discovered and controlled by the user, but as a set of spatial characteristics that can be inspected and regulated by the space on the user’s behalf. 

-- Exercising control over a spatial characteristic is centered on controlling the physical devices located in that space, including the physical sensors that monitor the state of the environment.  The latter are particularly important in the presence of uncontrollable factors (invisible sources and inaccessible devices) that can influence the space and when user requests span an interval of time or are relative to changing user location.  Figure 1 denotes such situations as the dynamics (user location and time) of user needs.

# A Qualitative Evaluation: The Scope of Spatial Characteristic Model.

To assess the model’s utility and impact, we seek to answer the following evaluation queries-

<b>1. How well do spatial characteristics allow reasoning about smart space interactions independently of any particular space?</b>

In the current conventional settings, users perceive smart space as a group of devices that they control via personal devices (such as smartphones, smart watches, etc.) to obtain specific functionalities. Users visiting a new space find a different set of devices, with different interfaces to be learned, and different configurations to be set, which disrupts consistency in user experiences. When users deal with characteristics instead of devices, their experience in interacting with space remains consistent independent of any space. Whether it’s a smart home, workplace, or a friend’s house, the universality of the spatial characteristics model allows users to express the desired condition changes they expect from the space, without following any manuals, or learning new interfaces and control mechanisms of any device. To ensure proper response, the space only needs to be aware of the properties of the devices, the rest depends on finding the appropriate device settings. Thus, the spatial characteristics model allows users to interact with the space in the same manner regardless of specific devices present in an environment or shifting to a new one. This level of abstraction ensures that the user experience with different setups, or spaces remains uniform. The resulting consistency reduces the complexity in interaction methodology that the user has to face while shifting between spaces.  

<b>2. How does the way that the spatial characteristics model abstracts away specific devices advantages or disadvantages application users, device manufacturers, and researchers/developers?</b>

-- The spatial characteristics model reduces the cognitive load on the user, promising a high-level interaction scheme within the space. The elderly, less tech-savvy, and the customers who feel less motivated to embrace smart setups due to complex device installation and maintenance can be attracted to the spatial characteristics model and interact with the space they feel natural, and comfortable. 

-- The spatial characteristics model is also less sensitive to specific brands, and the evolution (advancement in technology) of devices. As long as a device can affect a property, the space can engage it to deliver an outcome. A device’s ability to influence the condition of the space takes more precedence over a brand, or technology, promoting a homogeneous device ecosystem among manufacturers. 

-- The algorithm developers can get clear insights into the key factors and resources necessary to formulate algorithms that can resolve complex equations, leading to optimal solutions. The software developers do not need to redesign the user interface every time a device is introduced, rather they need to make the devices recognizable to the space, keeping the user interface intact. 

-- Finally, the model also provides new opportunities for researchers to study properties of the space, and design high-level user-space interaction schemes. This leads to investigating more intuitive, and personalized user interaction interface, gaining further insights into user’s perceptions and expectations from a smart space.

<b>3. How does the spatial characteristics model promise a more adaptable and responsive smart space?</b>

Figure 2 provides a visual representation of how the Spatial Characteristics Model can be realized through interconnected smart devices to foster a more adaptable and responsive smart space for the user. A crucial determinant of this adaptability is the ability of a space to discern the potential impacts of interconnected smart devices on the properties of the space, which can be supported by the Spatial Characteristics model. The model can help space recognize mutual dependencies of spatial Characteristics stemming from the properties of the smart devices. Below are some examples of how users can benefit from joint optimization offered by the model- 

-- In the absence of a dedicated smoke detector, temperature sensors integrated into smart HVAC or air cooler systems could monitor and detect unusual temperature fluctuations, triggering a warning to alert occupants of potential fire hazards. 

-- Similarly, smart windows, primarily designed for regulating natural light and indoor climate, could enhance air circulation in the absence of a dedicated vent system. 

-- In scenarios where power outages occur, smart TVs equipped with battery backup could serve as an alternate source of emergency lighting.

While there are opportunities for joint optimization, the spatial characteristics model can also recognize potential conflicts between multiple characteristics. For instance- 

-- The utilization of smart windows to address illumination queries can be commendable due to its energy-saving benefits, except when it conflicts with the user's privacy concerns. 
-- Similarly, the smoke detector's activation due to smoke or cooking fumes may cause the air purifier to enhance air circulation, inadvertently exacerbating the situation by spreading the smoke. 

By recognizing the potential impacts (conflict and joint optimization) that individual devices may have on the environment, the Spatial Characteristic model can facilitate the development of a more adaptable and responsive IoT architecture for the user. 

<table>
  <tr>
    <td>Figure 2: Recognizing Mutual Dependencies of Spatial Characteristics Stemming from Device Characterization.</td>
  </tr>
  <tr>
    <td><img src="https://github.com/HamimAdal/Spatial-Characteristics/blob/main/Figures/deviceCharacterization.jpg" width=800 height=400></td>
  </tr>
</table>

<b>3. How does the Spatial Characteristics model allow the space to leverage various contexts to effectively achieve user requests?</b>

Depending on spatial contexts, the user can rely on the space to predict an optimized solution. As of now, operating smart devices based on context is not an unfamiliar practice in today’s IoT ecosystem. Autonomous control of lights and HVAC based on human presence is common in smart spaces. However, the scope of exercising this trend remains confined to a small number of devices and specific contexts. The figure 3 illustrates how the Spatial Characteristics model allows the space to go beyond illumination (lights) and temperature (HVACs) and explore more opportunities with a wider range of characteristics and contextual scenarios. For instance:

-- Under the characteristic "Floor-Cleaning", the space can adjust the vacuum cleaner's settings in accordance with the type of floor surface, applying a faster speed on carpets and a gentler one on hardwood floors. 

-- Similarly, for the characteristic "Washing", heavier laundry can be handled with higher cycle speeds, while lighter loads can utilize lower cycles. 

-- “Monitoring” can also be context-aware, pausing the surveillance devices from operation during daytime periods (avoiding frequent movement during active hours) and activating the alarm for movement at night. 

-- The watering can also be controlled based on soil moisture levels, with the smart hose increasing its operation when the moisture content is low, and decreasing activity when the soil is adequately moist.

-- Lastly, the water flow rate during a shower can also be adjusted based on the reservation status, optimizing water usage.


<table>
  <tr>
    <td>Figure 3: Context-Driven Controlling of Spatial Characteristics</td>
  </tr>
  <tr>
    <td><img src="https://github.com/HamimAdal/Spatial-Characteristics/blob/main/Figures/context.jpg" width=800 height=400></td>
  </tr>
</table>

# Case Studies.

Let’s consider two smart spaces- one at home and another in a corporate office. 

-- When users work remotely at home, their desired level of illumination can be met by the space by dimming light fixtures that surround their personal workstations. Over time, after a successive occurrence of interactions, the space can also learn and recognize the user’s preferred light fixtures and engage them in the process of delivering a request. However, when the user is working in an office, the preferred level of illumination may be served by exploiting the light fixture mounted above their personal desk without causing discomfort to other colleagues. 

-- Similarly, for inhabitants of metropolitan areas where there are high-rise apartments, the space might exploit thermostats, floor heating systems, or light fixtures to provide ambient temperature or illumination. Smart blinds/windows are less effective because dense construction in cities can limit sunlight and compromise the air quality. But on vacation, when a user makes the same request in an Airbnb on lakeside, or in beachfront condos, the space might involve motorized shades for a gentle gleam of sunlight or utilize smart windows to allow a natural breeze.     

In the above instances, despite there being variations of devices and configurations across distinct spaces, the user request was clearly met. To run this process, the user only needs to be aware of the properties of the devices, the rest depends on finding the appropriate device settings. Thus, the spatial characteristics model can generalize and satisfy user requests based on the best available resources. This level of abstraction ensures that the user experience with different configurations, or space remains uniform. The resulting consistency reduces the complexity in interaction methodology that the user has to face while shifting between spaces.

# Demonstration.

https://github.com/HamimAdal/Demonstration-Spatial-Characteristics-in-Unity-Engine (Platform: Unity Game Engine)

# Prototype.

https://github.com/HamimAdal/Middleware_Space_Broker (Platform: Android Studio, Raspberry-Pi)

# Simulation platform for evaluating Algorithms.

https://github.com/HamimAdal/Simulation-Unity/tree/main (Platform: Unity Game Engine)
