# c. Hawk URL templates

|||
|-|-|
|**What parameters should I use ?**| _loopcd_ (for all analytics platforms including Adobe, Google or Piano Analytics)using the  _utm_content_  parameter in substitution is possible (only for Google Analytics) | 
|**URL template**| Just add the following string at the end of the destination URL `&loopcd=DIh\|${HAWK_LINE_ID}`. If Adloop is the  **only tracking template** : `?loopcd=DIh\|${HAWK_LINE_ID}`. If you opt for the  _utm_content_ , use this value : `&utm_content=DIh\|${HAWK_LINE_ID}` |
| **Shoud I use both adlcoid & utm_content ?**| No, choose one.  |