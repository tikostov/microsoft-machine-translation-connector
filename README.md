# Progress.Sitefinity.Translations.MicrosoftMachineTranslatorConnector (Machine translation connector for Microsoft Translator)

### Latest supported version: Sitefinity CMS 12.1.7100.0

When working with the Sitefinity CMS *Translation* module, you can benefit from a number of translation connectors that you use out-of-the-box with minimum setup.

This repo contains a translation connector to work with the **[Microsoft Translator Text](https://azure.microsoft.com/en-us/services/cognitive-services/translator-text-api/)** V3 API service. 


## Requirements

### Sitefinity

For more information, see the [System requirements](https://docs.sitefinity.com/system-requirements) and [Translation procedure](https://www.progress.com/documentation/sitefinity-cms/translation-procedure) for the  respective Sitefinity CMS version.

### Microsoft

You must **[Sign up for Microsoft Translator Text API V3](https://docs.microsoft.com/en-us/azure/cognitive-services/translator/translator-text-how-to-signup)** service in Microsoft Azure. Then you can use one of the generated API Keys there to configure the connector in Sitefinity. All of the [available tiers](https://azure.microsoft.com/en-us/pricing/details/cognitive-services/translator-text-api/) are supported.

## Configure the connector

Using one of the generated API keys after **[sign up for Microsoft Translator Text API](https://docs.microsoft.com/en-us/azure/cognitive-services/translator/translator-text-how-to-signup)** service in Microsoft Azure configure the following setting:
*Administration >> Settings >> Advanced >> Translations >> Connectors >> MicrosoftMachineTranslatorConnector >> parameters >> apiKey*

**Warning** For proper translation of whole paragraphs of text, **do NOT** set the *Strip HTML tags* parameter to *True* (under *Administration >> Settings >> Advanced >> Translations >> Connectors >> MicrosoftMachineTranslatorConnector*).

## Supported languages

You can check out the official [Azure language support documentation](https://docs.microsoft.com/en-us/azure/cognitive-services/translator/language-support#translation). The connector uses the v3 API.
