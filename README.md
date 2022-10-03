# Connector API for Lokalise content engine

Lokalise **content exchange apps** facilitate the exchange of translatable content between Lokalise and third party content platforms. Users interact with them to connect both systems, select the content they want to translate, transfer it to Lokalise, see the translation status, and send the translations back to the content platform. 

You can build and publish **your own content exchange app** by building a connector for the Lokalise content engine. The **content engine** will take care of the UI and handle the standard install, config and content management flows, while the **connector** will act as a bridge between the content platform and Lokalise content engine.


```
 ------------------     -------------------------     ----------------
| Your content app | = | Lokalise content engine | + | Your connector |
 ------------------     -------------------------     ----------------  
```

This repository contains the [OpenAPI schema](schema.yaml) for a content exchange hosted connector. The technical implementation requirements are detailed on [Lokalise Developer Hub](https://developers.lokalise.com/docs/technical-requirements-content-exchange-hosted-connector).


# Code examples

For a faster start, Lokalise can provide you with application skeletons in NodeJS and PHP. Reach out to our Support team if you’re interested, please.
