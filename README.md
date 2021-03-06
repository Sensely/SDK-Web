# Sensely Web Conversational SDK

<a href="mailto:info@sensely.com"><img src="https://cl.ly/ca1a088639e6/request-access-button.png" alt="Request access" width="157"></a>

The Sensely Web/JavaScript SDK is designed to allow you to easily incorporate custom avatar technology and conversational content in your desktop or web app. Start using the SDK today to leverage the power of conversational language interfaces. The avatar supports both voice and text options, allowing you to intelligently communicate with your patient and insurance plan member populations.

## Try it out
* SDK (Mobile or Desktop): https://clinician-web.sense.ly/
* SDK embedded in a drawer (low-code implementaiton over existing site) : https://clinician-web.sense.ly/nhs/

## Technical overview

The Sensely Web SDK can be embedded in an existing desktop website or mobile web application. When calling the SDK, the partner app will get a conversation flow (e.g. mayo symptom checker). Here is an overview of the integration:

* The partner app activates the Sensely UI and begin the conversation experience:
    * The user proceeds through the conversation by interacting with the Sensely UI.
    * During the conversation, the sensely conversation engine will direct a user through a flow, described below.
* Once the conversation has been completed:
    * The results of the conversation are returned in JSON format. These results can also be recorded in Sensely’s backend if desired.

## Integration with Mayo Clinic symptom assessment tool

Sensely is ready to use with the Mayo Clinic symptom assessment tool in 8 languages (contact us for more languages). The introduction can be reviewed and customized with disclaimers by the partner’s team. The Mayo symptom checker also supports using the symptom checker on behalf of a 3rd party (child, other family member).

In addition to symptom checker interactions, partners are able to build other conversation interactions using either our conversation design tools or ad-hoc using a specification of the conversation definition and building the conversation programmatically. More documentation is available upon request. 


## Supported Browsers
Integration is as easy as dropping our JavaScript div into your website. 
- Desktop: Google Chrome, Mozilla Firefox
- Mobile: iOS (Safari, Web Views), Android, WeChat

## Full Documentation and more details

  To get more details about SDK please request full documentation from Sensely.
  
  <a href="mailto:info@sensely.com"><img src="https://cl.ly/ca1a088639e6/request-access-button.png" alt="Request access" width="157"></a>

## Licenses

The Sensely SDK is released under the Sensely license. See the [LICENSE] file for more details.

[LICENSE]: https://github.com/Sensely/SDK-iOS/blob/master/LICENSE

## Other platforms of the Sensely SDK
* [iOS](https://github.com/Sensely/SDK-iOS/)
* [Android](https://github.com/Sensely/SDK-Android)
