<img src="https://github.com/symdesign/sketch-auto-translate/raw/master/Assets/logo%402x.png" width="100" height="100" alt="Sketch Auto Translate Plugin">
  

# Sketch Auto Translate Plugin

Save time when localising your digital designs. Sketch Auto Translate Plugin handles your language translations so you create multi-lingual apps within minutes instead of hours.

The plugin will translate Text Layers and Symbol Overrides from and to any of the currently 40 supported languages based on your Selection, Current Page or the whole Document. 


<table>
<tr>
<td>
This plugin requires you to <a href="#set-google-api-key">setup a Google API key</a>. <strong>
</td>
</tr>
</table>

<a href="https://www.sketchpacks.com/symdesign/sketch-auto-translate/install">
  <img width="160" height="41" src="https://sketchpacks-com.s3.amazonaws.com/assets/badges/sketchpacks-badge-install.png" >
</a>
<small><br>or <a href="https://minhaskamal.github.io/DownGit/#/home?url=https://github.com/symdesign/sketch-auto-translate/tree/master/SketchAutoTranslate.sketchplugin">Direct Download</a></small> 



<a target="_blank" href="https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=ZK3TU55XHALSE">
<!-- Donate Button »
<img width="160" height="45" src="https://raw.githubusercontent.com/symdesign/sketch-auto-translate/master/Assets/donate-button.svg?sanitize=true" alt="Donate">
« Donate Button -->
<br>
<!-- Powered by »
<img width="160" height="auto" src="https://github.com/symdesign/sketch-auto-translate/raw/master/Assets/cc-badge-powevered.png"/ >
« Powered by -->
</a>


## Supported Languages
Albanian, Arabic, Armenian, Azerbaijani, Bashkir, Belarusian, Bulgarian, Catalan, Chinese, Croatian, Czech, Danish, Dutch, English, Estonian, Finnish, French, Georgian, German, Greek, Hebrew, Hungarian, Italian, Kazakh, Latvian, Lithuanian, Macedonian, Norwegian, Persian, Polish, Portuguese, Romanian, Russian, Serbian, Slovak, Slovenian, Spanish, Swedish, Turkish, Ukrainian ande Vietnamese.


## Translate Selection
Translates your selection on the current page no matter which type, apart from Symbols.

Shortcut: `⇧` `⌘` `X` Translate Selection

<img src="https://raw.githubusercontent.com/symdesign/sketch-auto-translate/master/Assets/TranslateSelection_v2.gif" alt="Screen Recording 'Translate Selection'" >


## Translate Current Page
Translates all Text Layers and Symbol Overrides on Artboards in your current Page but skips them out if placed outside.

Shortcut: `⇧` `⌘` `P` Translate Current **P**age

<img src="https://raw.githubusercontent.com/symdesign/sketch-auto-translate/master/Assets/TranslatePage_v2.gif" alt="Screen Recording 'Translate Current Page'" >

## Translate Entire Document
Translates all Text Layers and Symbol Overrides in the file that are on Artboards but skips them if placed inside a Symbol or outside an Artboard. I made this decision to avoid messing with the file structure.

Shortcut: `⇧` `⌘` `D` Translate Entire **D**ocument

<img src="https://raw.githubusercontent.com/symdesign/sketch-auto-translate/master/Assets/TranslateEntireDocument_v2.gif" alt="Screen Recording 'Translate Entire Document'" >


## Set Google API Key...

To create a Google Translate API Key key yourself, you need a paid account at [Google Cloud Platform](https://cloud.google.com). 

But there is also a free trial option theat gives you $300 in credits which means, as long as you don't exceed that amount you won't have to pay anything. 

[Check out their pricing](https://cloud.google.com/translate/pricing) to find out how many Language Detections and Translations you can get. Bear in mind that for the trial, a Credit Card is still required. 


  
#### 1. Create a new Project
To create your application’s API key please go to the [Cloud Platform Console](https://console.cloud.google.com/) and create a new project and give it a name you prefer.


#### 2. Enable Google Cloud Translation API
With the new project selected, go to `API & Services > Credentials`.
At the Credentials page search for the *Google Cloud Translation API* and enable it.


#### 3. Create API Key
Go to `API & Services > Credentials` again and click the button `Create credentials` inside the credentials card.


#### 4. Use API Key
Copy your API Key, go back to Sketch and select `Plugins > Translate > Set Google API Key...` in the menu. After that you get prompted to paste your key.
