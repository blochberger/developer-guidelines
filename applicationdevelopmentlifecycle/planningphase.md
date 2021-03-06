# Planning Phase

n order to testify your that you carefully weighed the use and necessity of data, you need to write down your decisions in a separate document. This will also help you to reconsider your design decisions in a later development phase.

Before you start to code, carefully plan your app: what purpose is it for? Which functions will be needed, what are the use cases?

In order to testify you carefully weighed the use and necessity of data, you need to document your decisions in a separate document. This will also help you to reconsider your design decisions in a later development phase.

{% hint style="info" %}
A proper documentation of the risks you identify and the measures you take regarding data protection will help yourself through the development process to keep overview and will enable you to justify your decision in case of someone \(e.g. a data protection authority\) asks.
{% endhint %}

{% hint style="warning" %}
[Art 5.2 GDPR ](https://eur-lex.europa.eu/legal-content/EN/TXT/HTML/?uri=CELEX:02016R0679-20160504&from=EN)entails the obligation of the data controllert to be able demonstrate compliance \("accountability"\).
{% endhint %}

## Defining the Purpose and Functionality of the App

### The App's Purpose

What will the app do for the end-user? It might seem obvious, but **it is a good start to take a moment and reconsider what the actual aim of the app is**.

* Which functions should the app provide and
* which user data is necessary for the planned functionality.

Especially it is important to carefully think which user data is needed and how it will be processed.

{% hint style="warning" %}
According to Art. 5 of the GDPR the processing and storage of personal data is only allowed for "specified, explicit and legitimate purposes" \(1b\) and be "adequate, relevant and limited to what is necessary " \(1c\).
{% endhint %}

**Determining the purpose is important for deciding upon the functionality that may be included in the app, and if and how user data needs to be processed.**

{% hint style="info" %}
For example a weather app might let you choose and display weather information; a firewall app might let you inhibit or monitor a smartphone's connections to the internet. For this functions certain user data might be necessary or useful like geo-data or access to data connections. This data has implications which need to be taken into account at an early stage of development for proper integration of security measures.
{% endhint %}

{% hint style="success" %}
For further information have a look in the [ENISA Report on Privacy and data protection in mobile applications](https://www.enisa.europa.eu/publications/privacy-and-data-protection-in-mobile-applications) p. 55
{% endhint %}

### Intended and Unintended Ways to Use the App

When planning the application design, consider not which purpose you design the app for but also take into account that users might find alternative ways to use the app which can have an impact on other users of the device.

{% hint style="info" %}
For example a firewall app can give you information about other apps' illegitimate connections to the internet. Yet it might also give end users a tool to secretly record and monitor other users' internet activities.
{% endhint %}

**Be creative about potentially harmful ways to use of your app. Think about safeguards against illegitimate uses.**

Not only people with physical access to the device can make use of the app, and the data generated. Other apps might have access to shared memory, service providers might use the data in unintended ways, and finally governments might get access to data stored by the service providers or on the device.

_For example third party apps might get access to pictures taken on political manifestations, or governments might be interested in the social-graph included in the contact list or regular whereabouts to trace political opponents._

This might appear far from daily risks, but keep in mind that people are travelling around the world and we are facing a growing number of totalitarian regimes, who

**The safest data is data which is not collected or stored.**

## Defining the App's Functionality and Permissions

A privacy-friendly app will only include functionality and permissions that is needed to serve the purpose determined in the beginning.

**Think carefully about which permissions are essential for providing the functionality.**

_An app providing location based services does not need to access the device's microphone to do so._

Ideally any permissions that are not strictly necessary to serve the intended purpose should be avoided. Any need for permissions must be explained and justified in a comprehensible way. Take into account that users have no deeper understanding of the dependencies and technical necessities. Only if they really understand why and how the permission is used they can actually give a real consent.

## Defining the sort of data to be used

There are different categories of data which are relevant for the use of the app.

* **Primary Data: Pre-existing data**: Data related to the end-user or to other data subjects concerned. Be aware that on the device might be data which the user has no right to give third parties access to, for instance contact data or pictures of other persons.
* **Secondary Data: User generated data**: Data will be produced while the app is running. This might be user content \(e.g. messages\), log data, data related to payment, statistics to authorizing access or other. These will also contain personal data that require protection and thus need to be specified and assessed.

#### 

