Sensor Platform
===============

![](https://i.imgur.com/qiDKL0r.jpg)

The Smart Citizen platform supports the core features of the platform. That means this report documents new components, developed specifically for the project, but also existing components that already existed and made possible the platform.

![](https://i.imgur.com/loUgFJv.png)

We believe building modular and reusable software and using existing platforms is critical towards optimizing the research and development effort. By increasing the technology readiness levels of existing technologies, we can drastically improve the project exploitation strategy.

The previous requirements led to the decision of building the core platform on top of the existing Smart Citizen Platform. The platform is a front and backend solution for ingesting, storing and interacting with public data with a particular focus on crowd sensing applications.

!!! tip "Check the guides"
	We prepared a series of guides to help you on the most common features you will use

	* [Onboarding Sensors](Guides/Onboarding Sensors)
	* [Uploading SD Card Data](Guides/Uploading SD Card Data)
	* [Downloading data](Guides/Downloading the Data)

!!! info "Want to learn more?"
	Check the developers ready [**API Documentation**](https://developer.smartcitizen.me/)

## Software components

* **Smart Citizen Website**: It aims to provide a visual website where the project environmental sensors can be accessed in near real time to facilitate the exploration of data with other contextual data (maps, keywords) and processed reports. This is especially important towards citizens engaging at each local site having a sense of ownership over a technology intervention has been associated with sustained community engagement _(Balestrini et al. 2014)_.

* **Smart Citizen API**: The platform provides a REST interface for all the functionalities available on the Website. That allows applications to be developed on easily on top having access to all the features to create complex and rich tools. One examples of this tools is the Sensors Analysis Framework or the iSCAPE Virtual Living Lab (developed during the [iSCAPE project](https://www.iscapeproject.eu/))

* **Onboarding app**: It aims to facilitate the process of sensor setup to ensure that users, irrespective of technical expertise, can install the sensors. It guides the user through the process of the setup using simple language and a friendly graphic language. It is built as a separate tool from the core Smart Citizen Webpage in order it can be customized for each deployment. It exchange data with the core platform using the Smart Citizen API.

## Source files

<a class="github-button" data-size="large" href="https://github.com/fablabbcn/smartcitizen-kit-20" aria-label="Check the source code">Check the source code</a>