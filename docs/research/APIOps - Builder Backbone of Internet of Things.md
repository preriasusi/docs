![](https://hackpad-attachments.s3.amazonaws.com/hackpad.com_gWgGgv8ja9j_p.376760_1429787093981_builerhero.png)

## Introduction

_[Lets coin the term APIOps now and start educating APIOps people in Finland]. Once this document is ready to meet our standards, lets push it to own domain for further development. We could easily create a handout from this]_

**McKinsey Global Institute** estimates the potential economic impact of the Internet of Things to be $2.7 trillion to $6.2 trillion per year by 2025.  The GSM Association predicts that by 2020, there will be 24 billion connected devices, while Cisco’s Internet of Everything prediction is 50 billion “intelligent things,” such as cars,  appliances, smartphones, tablets, monitoring sensors and more, connected  to the Internet. The rise of IoT depends on a whole host of enabling technologies like  RFID, IPv6, Big Data, and Application Programming Interfaces (APIs). Web APIs, or more specifically REST APIs, are key for connecting devices to the Internet.

**[DRAWING OF  CONNECTED THINGS - API IN THE MIDDLE]**

A large part of the interoperability, scale, and control for IoT can be achieved through [API management](https://www.mashery.com/api-management).  Standards-based  design patterns for Web APIs, API management, and a  RESTful  architecture provide tremendous value in simplifying the task  of  interoperability across heterogeneous systems handling vast amounts  of  data. Since APIs have become ubiquitous, IoT deployments spanning a  wide  range of market segments can benefit from this proven  architecture.

**"Companies focusing on enabling fast API development together with customers and nearby interest groups will rule the IoT**. "

Industrial Internet, Internet of Everything, Internet of Things (IoT) and Industrie 4.0 are the terms which are brought up more and more in articles and discussions when it comes to future and the visions for it. IoT is driven by the power and speed of **APIs**. IoT is often discussed in the context of industry mostly because that is where it will first create biggest changes. However, to understand more clearly what IoT is we should take imagine what it could be in the everyday life of citizens. 

In everyday life IoT can be rather simple things. For example your coffee maker is connected to your alarm clock and no matter what time up the alarm goes off, coffee is brewed. Your colleagues at work can be notified of your possible delay because of possible traffic jams on your way to office. Your home automation can shut the lights and adjust  temperature when everyone is away. According to Samsung in 2020, every device Samsung sells world wide will be connected to the Internet of Things. Since leading manufacturers of our digital devices have such goals, it is no wonder that Gartner predicts that there will be nearly 26 billion devices on the Internet of Things by 2020. Eventually it means that even our living room chairs are connected to IoT and exchange information with other devices. Our living room it self could be connected to tv and according to noise level adjust the volume to be just perfect. This also gives us opportunities to use surfaces as interfaces. For example we could use ordinary windows made of glass as email app interface. Or we could watch morning news from the mirror while brushing teeth.

**[DRAWING HERE ABOUT ONE COMMON EVERYDAY LIFE IOT EXAMPLE]**

International Organization for Standardization is well known and established standardization body and their definition of IoT is as follows: 

*   _"An infrastructure of interconnected objects, people, systems and information resources together with intelligent services to allow them to process information of the physical and the virtual world and react." _

Just  like DevOps can be seen as offspring or spinoff of Agile thinking,  APIOps can be seen to extend DevOps to fulfil the needs of Application  Interface and Internet of Things development (IoT).  Therefore I foresee clear need for APIOps, a new breed of DevOps to support creation and maintence of IoT driven ecosystem. 

**Practitioners of APIOps principles and values are the builders of the future.  **

## APIOps manifesto

*   **APIOps Values** – APIOps values are effectively captured in      the Agile Manifesto. APIOps extends the “[People over Process over Tools](http://dev2ops.org/2010/02/people-over-process-over-tools/),” and urges API developer  +  system operator + 3<sup>rd</sup> party service developer collaboration.
*   **APIOps Principles** – APIOps at the conceptual level is based on Agile’s and DevOps principles to focus on effective collaborative design, development and maintenance of APIs to enable extremely fast and flexible service design and development.
*   **APIOps Methods** – You can use Scrum with operations, Kanban with operations, etc. Provide methods to collaboratively design APIs for service development utilizing the principles of design first approach.
*   **APIOps Practices** – Provide low barrier access to reliable APIs, documentation supporting usage, sandboxes to test and build on top of, generated libraries and code examples for service developers. 
*   **APIOps Tools** – Tools you’d use in the commission of these principles. In the APIOps world there’s a lot of  emerging tools and evolving standards in provisioning (docker, vagrant), design (RAML, API Blueprint, Swagger), API server code generation ([Drakov](https://www.npmjs.com/package/drakov) ), generating OS specific libraries ([APIMATIC](https://apimatic.io/) ), managing APIs (apinf.com, 3scale.com,) and many more.

## API design first development process

![](https://hackpad-attachments.s3.amazonaws.com/hackpad.com_gWgGgv8ja9j_p.376760_1429848186118_apiops-2.png)

**Joint open design process**

**[DRAWING OF PEOPLE DOING COOPERATION]**

API design first approach focuses on involving service and API developers and marketing to same process of co-creating API description. API description is a communication tool, it is not code, at best it is browser-based graphical userface in which all participants collaborate and contribute. Process involves 3rd party service developers into the development since they are endusers of APIs and know best the needs. Obviously the product owner of service utlizing APIs is involved. During the process all work together; sometimes intensively and occasionally there might be total silence. The  team uses f2f meetigns and online environments as well as instant messaging tools to communicate. In other words, there is no written rule or need to necessary to be all the time in the  space/room. This phase produces shared version controlled understanding of:

*   API feautures
*   API consumer needs
*   Machine readable description of API or multiple APIs

**Speed up development with code generation**

In the  second phase APIOps (API developer) uses the machine readable  description file to configure code generation toolchain. Toolchain automatically generates both API server skeleton and client side development kits (SDK) for plethora of operating systems including mobile platforms such as iOS, Android, Windows. 

Generating API server code kicks the development at fullspeed right from the start. API developer needs to adjust and finetune actual code a lot less compared to other approaches. The SDKs are important since they lower the barrier to utilize newly created APIs. Having top knotch API is nice, but widely utilized and liked API is golden. 

**Service Development Platform as online hub**

Eventually API server code is launched at production server and attached to API management, which is part of Developer Portal (DP). DP enables service developers' easy access to APIs, API documentation, SDKs, code examples and community. In Developer Portal  API provider can limit the usage of APIs, see metrics and even retire entire API. In portal, API developers and consumers can exchange ideas and use documented comments as feedback for the next cycle which begins from the Joint open design process.  

All this should take plane inside planned roadmap and business plan. Internet of Things (IoT) is something  which in common terms connects devices to each other to exchange data.  IoT relies heavily on web APIs which in fact enable us to connect  services and objects with each other. Without reliable, easily  implemented backends and frontend support, new services build on top of  IoT, will not succeed. 

## What can we do for you

Solutions and services apinf & Sampo Software can provide: 

*   Understanding and experties of API lifecycle and development
*   Fullstack API design process and browser based toolchain
*   Agile APIs driven Service Development Platform
*   APIOps  as hired guns to speed up your IoT service development
*   Top API management solution
*   Community discussion platform: [](https://apiops.slack.com)[https://apiops.slack.com](https://apiops.slack.com) established - join now!

![](https://hackpad-attachments.s3.amazonaws.com/apinf.hackpad.com_gWgGgv8ja9j_p.376760_1434960912447_apiops-vs-apitalisti-2.png)

![](https://hackpad-attachments.s3.amazonaws.com/apinf.hackpad.com_gWgGgv8ja9j_p.376760_1434960969948_apiops-vs-apitalisti.png)