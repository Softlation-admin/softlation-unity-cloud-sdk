<img src="http://softlation.com/files/gma@2x.png"  width="200">

# Softlation Localization Service

## TOC

- [Overview](#overview)
- [Quickstart](#quickstart)
  * [Softlation Service init](#softlation-service-init)
  * [Get words by key](#get-words-by-key)
  * [Get list of languages](#get-list-of-languages)
  * [Change current language](#change-current-language)
- [Licence and Copyright](#licence-and-copyright)

## Overview

**Softlation**'s service is a plugin for Unity that provides a simplest way to implement localization updates and improve QA processes for your games and apps [**Softlation Service**](http://softlation.com). If you want use **Softlation Service** in your project you need to include the plugin in your project from Asset Store or Official Website.

## Working with the Service
Download Asset from Unity3D Asset Store or Softlation Service Official Website and include it to your project.

## Quickstart
## Softlation Service init
First you must init Soflation Service in Start function:

```
void Start() {
	SoftlationService.init();
}
```

## Get words by key
You can get value just by key:

```
SoftlationService.GetTextValue(key); //return string
```

And you can get value with parameters:

```
SoftlationService.GetTextWithParameter(key, params);
```

In your value you need set @i, if you want that params set that place.

## Get list of languages

```
SoftlationService.listLanguges(); //return massive string[]
```

## Change current language
You can change current display language to another by send locale you need

```
SoftlationService.changeLanguage(en-EN); //return void
```

## Licence and Copyright ##

**Softlation** © 2014-2017 All Rights Reserved

*Unauthorised copying or unauthorised use is a violation of applicable laws.*
