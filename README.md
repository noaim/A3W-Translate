# a3w-translate

Supported Languages in v1.5.2:

Original - English
German
Czech
Turkisch
Dutch
Italien
Spanish
Russian
French
Portoguese


Lines such as <Dutch>XXXXXXXXXXXXXXXXXXXXXXX</Dutch> need to still be translated.
 
Do not add more < or > to a line, due to breaking the XML Stringtable file. Also do not rename the languages, so there won't be any typos.

These typos could break the script:
<Dutch>XXXXXXXXXXXXXXXXXXXXXXX</DutcH>
<Dutch><XXXXXXXXXXXXXXXXXXXXXXX</Dutch>
<Dutch>>XXXXXXXXXXXXXXXXXXXXXXX</Dutch>
<DutchXXXXXXXXXXXXXXXXXXXXXXX</Dutch>
<Dutch>XXXXXXXXXXXXXXXXXXXXXXX<Dutch>


To Translate a Language from English to ***** just download its stringtable file. As soon as you are done, upload the stringtable file either in the #dev-translation channel or push it onto github.

To Edit stringtable.xml files either use notepad++, visualstudio or a XML editor.

Please do not update the original stringtable.xml, only the stringtable-language.xml files.

Please keep in mind, that the stringtables will also be updated (added new lines) in future.