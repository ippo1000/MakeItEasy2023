
# Household Energy Optimization 

## _Make It Easy 2023 Edition_
[![N|Solid](https://github.com/ippo1000/MakeItEasy2023/blob/main/IMG/3.png?raw=true)](https://www.makeiteasychallenge.it/)

`Opening Intro`
Oh hey! Do you want to know how to save on the electricity bill?


`At the Desk`
Today, we will explore sustainable and clean ways of producing and consuming electricity using the Smart Home technology and some algorithms I developed.

`Casalpalocco 8Kv Tower`
The electricity we get from the National Grid comes from various sources, including renewable ones like hydroelectric power plants (**Marmore**), solar panels(**Field C.Palocco**), and wind turbines (**Wind Sicilia**), as well as non-renewable sources like gas, fossil fuels , and nuclear power plants (**nuclear power plant condensing tower**).
With modern technology, today anyone can generate their own electricity and use it in a smart way. 


`In my Electronics Home laboratory`
To simplify this process, I created a device (**Video of me creating the device**) that measures the electrical power used bay an appliance in real-time. The data are collected and sent to a server in my home via WIFI and mqtt protocols, which processes it for multiple uses. (**Device Communication Animation**)

![N|Solid](https://github.com/ippo1000/MakeItEasy2023/blob/main/IMG/1.gif?raw=true)

`Home Roof`
Solar panels are increasingly common in households because they are becoming more efficient and less expensive (**Text Motion Graph**). However, the main issue with renewable energy is energy storage.
To address this issue, a smart and connected system can be used to create an algorithm that turns connected appliances on and off when there is solar production. This allows us to use the available energy more effectively and save on our electricity bills.

`At the Desk`
As you can see on my screen there are the data’s collected by the server about my home's solar production and energy consumption. In non-smart homes, the high consumption usually occurs in the evening when there is no solar production, and energy storage is too expensive and inefficient. (**Lithium Battery Animation**) 

`Home Roof`
However, a smart system can use an algorithm (**Me Conding it**) to turn on connected appliances when there is solar production, allowing us to use free electricity from the sun at the right time. 

`At the Desk`
So as you can see in this spot, this is not completely true ([Enel Last Spot](https://www.youtube.com/watch?v=L0udZNkpgVE&list=PLLZyU9TzayOe90SZy9EU5G5uVcYI-2vww&index=19))

Let’s try, as you can see my solar production is above the threshold I’ve decided (**My home Smart UI**), then the dishwasher has started! (**Check Binary Switch**) Obviously, I can turn on and off it when I want, even remotely, thanks to the internet.

![N|Solid](https://github.com/ippo1000/MakeItEasy2023/blob/main/IMG/5.png?raw=true)

In the future, artificial intelligence (AI) will manage these algorithms and let them exactly fit our needs to optimize energy use. (**Video of ChatGPT Writing one**). With other sensors, the AI can determine when to use energy and when not to, improving our planet's health by using renewable energy sources in a sustainable way. (**Video of DaVinci-1 and OpenAI server**)

![N|Solid](https://raw.githubusercontent.com/ippo1000/MakeItEasy2023/main/IMG/IMG6.webp)

`Home Terrace `
That's all for today! Thank you for watching and stay tuned for my next project!
You can check my full article at ifcorp.it/makeiteasy

See you the next year. 

## Development 
If you want to reproduce this project you can find the code in the project data here in Github. 
These are the steps 

- Setup and Home Assistant Istance with MQTT Broker (https://www.home-assistant.io/installation/)
- Install on Docker the Esphome Addon (https://esphome.io/)
- Buy the hardware parts and create the device, if you want you can create a box printed in 3D - Below you can see the schematics and the part list inside of it.
- Create the device by following the schematics 
- Put the code into the schematics (`wemoscode.yaml` file)
- Connect Esphome with Home Assistant
- Create the energy dashboard (`lovelace.yaml` file)
- Setup the Algorithm for the Washing Machine (`dishwasher.yaml` file)

This is a very generic description, to do so you need basics of 
Electricity, Docker, Linux, Virtual Machines, Yaml, C++, Wifi, MQTT. 

![N|Solid](https://github.com/ippo1000/MakeItEasy2023/blob/main/IMG/4.png?raw=true)

If you need clears or issue you can contact me on

**Whatsapp**: +39 3518914680
**Email**: Filippo.toni@ifcorp.it
**Fiver**: fiver.com/ippo1000


## How to read? 

| Text | Description |
| ------ | ------ |
| **Bold Text** | Description of the images |
| `Red Highline` | Place where i am |
| Cit. | Code |
| Normal Text | What i say |

## License
All rights reserved
Copyright (c) [2023] [IFCorp - Filippo Toni]
[MIT](https://choosealicense.com/licenses/mit/) License
[![N|Solid](https://i.ibb.co/kDcyNtD/Powered-By.png)](ifcorp.it)


