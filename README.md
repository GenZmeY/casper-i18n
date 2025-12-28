# Casper-i18n

[![Autoupdate](https://github.com/GenZmeY/Casper-i18n/actions/workflows/autoupdate.yml/badge.svg)](https://github.com/GenZmeY/Casper-i18n/actions/workflows/autoupdate.yml)
[![GitHub tag (latest by date)](https://img.shields.io/github/v/tag/GenZmeY/Casper-i18n)](https://github.com/GenZmeY/Casper-i18n/tags)
[![GitHub](https://img.shields.io/github/license/GenZmeY/Casper-i18n)](LICENSE)

The same [casper](https://github.com/TryGhost/Casper), but with localization support.  
For more detailed information about theme, see the [casper page](https://github.com/TryGhost/Casper).  

## Available languages

- Chinese (zh)
- Croatian (hr)
- Dutch (nl)
- English (en)
- Finnish (fi)
- French (fr)
- German (de)
- Hungarian (hu)
- Indonesian (id)
- Italian (it)
- Latvian (lv)
- Lithuanian (lt)
- Norwegian Bokmål (nb)
- Polish (pl)
- Romanian (ro)
- Russian (ru)
- Spanish (es)
- Swedish (sv)
- Turkish (tr)

## Usage

1. Go to [Tags](https://github.com/GenZmeY/casper-i18n/tags) and download the **zip** archive for the version you need (if you are unsure which one to use, choose the latest)).  

2. Upload the theme to your Ghost:  
```
Ghost Admin → Settings → Theme → Change theme → Upload theme
```
select the zip archive you downloaded earlier.  

3. Apply the theme:  
agree to the prompt to activate it (after uploading), or manually activate casper-i18n from the list of themes.  

4. Select the language:  
```
Ghost Admin → Settings → Publication language
```
enter the [language code](https://www.w3schools.com/tags/ref_language_codes.asp) and click "Save".  

5. (Optional) Restart Ghost:  
```
ghost restart
```
6. Go to your site and verify that the theme has been applied and the text is displayed in the language you specified.  

**Note if you're deploying Ghost for the first time**  

After applying the Casper-i18n theme, some text on your site may still appear in English. This is not a translation issue:  
- "Home" and "About" buttons - these are pre-configured primary navigation bar buttons; you can change them here:  
```
Ghost Admin → Settings → Navigation → Customize → Primary
```
- "Sign up" button -  this is part of the pre-configured secondary navigation:  
```
Ghost Admin → Settings → Navigation → Customize → Secondary
```
- Content of "About" page and "Coming soon" post - template content. Delete or change it here:  
```
Ghost Admin → Pages
Ghost Admin → Posts → Published
```

## Casper-i18n updates
Casper-i18n differs only minimally from the original [Casper](https://github.com/TryGhost/Casper). This minimal difference allows the theme code to be updated automatically. A GitHub bot periodically merges the original [Casper](https://github.com/TryGhost/Casper) code into Casper-i18n.  

Internationalization is the theme's only feature; no other functionality is planned.  

I am not currently using Ghost and do not test every new version. Therefore, **updates may introduce text that has not yet been localized or may make some existing localizations obsolete. Please keep this in mind.**  

## Contribution

- Most of the text has been machine-translated, so [Pull Requests](https://github.com/GenZmeY/casper-i18n/pulls) with  corrections to translations are welcome, as are contributions of translations for new languages.  
- If you notice untranslated text, you can highlight it in [Issues](https://github.com/GenZmeY/casper-i18n/issues) or create a [Pull Request](https://github.com/GenZmeY/casper-i18n/pulls) with a correction.  
- If your contribution is not related to translation - contribute it to the original [casper](https://github.com/TryGhost/Casper).  

## Contributors

- [gcxfd](https://github.com/gcxfd) - bugfixes ([PR#1](https://github.com/GenZmeY/casper-i18n/pull/1))  
- [basleenders](https://github.com/basleenders) - Dutch translation ([PR#3](https://github.com/GenZmeY/casper-i18n/pull/3))  
- [GGLVXD](https://github.com/GGLVXD) - Latvian translation ([PR#4](https://github.com/GenZmeY/casper-i18n/pull/4))  
- [loviuz](https://github.com/loviuz) - Italian translation ([PR#5](https://github.com/GenZmeY/casper-i18n/pull/5))  

## Copyright & License

Copyright (c) 2013-2026 Ghost Foundation - Released under the [MIT license](LICENSE).
