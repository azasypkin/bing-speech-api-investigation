# Bing Speech API Investigation Notes
Repository to record investigation notes related to the Bing Speech API.

# Overview
> Microsoft's cross-platform REST API enables speech capabilities on all internet-connected devices. Every major platform including Android, iOS, Windows, and 3rd party IoT devices are supported. Our REST API offers industry-leading speech-to-text, text-to-speech, and language understanding capabilities delivered through the cloud.

> Microsoft has used Bing Speech API for Windows applications like Cortana and Skype Translator as well as Android applications like Bing Torque for Android Wear and Android Phone.

See more at https://www.microsoft.com/cognitive-services/en-us/speech-api/documentation/overview

# Pricing (see [official page](https://www.microsoft.com/cognitive-services/en-us/pricing))
| Plan           |      Features                |  Price (USD)*            |
|:--------------:|:----------------------------:|:------------------------:|
| Free           | 5,000 transactions per month | Free                     |
| Speech to text | Utterance up to 15 seconds   | $4 per 1000 transactions |
| Text to speech |                              | $4 per 1000 transactions |

# Demo
[Official demo page](https://www.microsoft.com/cognitive-services/en-us/speech-api)

# Supported languages
de-DE 	zh-TW 	zh-HK 	ru-RU
es-ES 	ja-JP 	ar-EG 	da-DK
en-GB 	en-IN 	fi-FI 	nl-NL
en-US 	pt-BR 	pt-PT 	ca-ES
fr-FR 	ko-KR 	en-NZ 	nb-NO
it-IT 	fr-CA 	pl-PL 	es-MX
zh-CN 	en-AU 	en-CA 	sv-SE

# Developer Access
The Speech Recognition API provides the ability to convert spoken audio to text by sending audio to Microsoft’s servers in the cloud. Developers have a choice of using the REST API or the Client Library.

* Using the REST API means getting only one reco result back with no partial results. Documentation for the REST API can be found here and code samples here.
* Using the client library allows for real-time streaming, meaning that as audio is being sent or spoken to the server, partial recognition results are returned at the same time. Real-time streaming is supported on Android, iOS, and Windows.

