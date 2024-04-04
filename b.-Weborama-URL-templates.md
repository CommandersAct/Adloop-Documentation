# b. Weborama URL templates

|||
|-|-|
|**Level in which I put the URL templates**| Campaign level |
|**What parameters should I use ?**| _loopcd_ (for all analytics platforms including Adobe, Google or Piano Analytics)using the  _utm_content_  parameter in substitution is possible (only for Google Analytics) |
|**URL template**| Just add the following string at the end of the destination URL `&loopcd=DIw\|~INSERTION_ID~`. If Adloop is the  **only tracking template** : `?&loopcd=DIw\|~INSERTION_ID~`. If you opt for the  _utm_content_ , use this value : `&utm_content=DIw\|~INSERTION_ID~` |
|**Shoud I use both adlcoid & utm_content ?**| No, just chose one parameter and keep it consistent for all Bing Campaigns for now and the future  |