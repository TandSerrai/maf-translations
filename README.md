Might &amp; Fealty Translations
================

These are the YAML translation files for [Might & Fealty](http://mightandfealty.com)

They're in this repository to allow collaborative translations as demanded by players.



How To Translate
----------------

All files have the format **domain . language . yml**. Only ever change the language part and always use the 2-digit
ISO language code. So the german translation file for messages.en.yml would be messages.de.yml

Within the files, you will find syntax like the following:

	dateformat:   Y-m-d
	gametime:
	 current:     It is year %year%, week %week%, day %day% in the world of Might & Fealty
	 long:        year %year%, week %week%, day %day%
	 short:       %year%-%week%-%day%
	realtime:
	 forever:     eternity
	 day:         %d% day (real time)|%d% days (real time)

The quickstart instructions for translating are:

* Always keep everything in front of the colon : exactly as it is.
* Translate the string following the colon :
* Keep words in %% symbols untranslated, they are keywords.
* If there is a pipe | symbol, it means the string has a singular (before the pipe) and plural (after the pipe)
* In case of doubt, ask. In the above, for example, Y-m-d is a dateformat string and should be reformated according to your locale, but not translated, and "Might & Fealty" is, of course, a name and thus should also be kept unchanged


So the german translation for the above would be:

	dateformat:   d.m.Y
	gametime:
	 current:     Es ist Jahr %year%, Woche %week%, Tag %day% in der Welt von Might & Fealty
	 long:        Jahr %year%, Woche %week%, Tag %day%
	 short:       %year%-%week%-%day%
	realtime:
	 forever:     Ewigkeit
	 day:         %d% Tag (Echtzeit)|%d% Tage (Echtzeit)


