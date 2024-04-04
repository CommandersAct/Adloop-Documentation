# b. Snapchat URL templates

|||
|-|-|
|**Level in which I put the URL templates**| Ad level |
|**What parameters should I use ?**| _loopcd_ (for all analytics platforms including Adobe, Google or Piano Analytics)using the  _utm_content_  parameter in substitution is possible (only for Google Analytics) |
|**URL template**| Just add the following string at the end of the destination URL `&loopcd=SMs\|{{ad.id}}`. If Adloop is the tracking template: `?loopcd=SMs\|{{ad.id}}`. If you opt for the  _utm_content_ , use this value : `&utm_content=SMs\|{{ad.id}}`Alternaltively, you can use the following parameter if the previous one is refused (because of the | symbol, for exemple) : `&adlch=SMs&adlcoid={{ad.id}}` |
|**Shoud I use both adlcoid & utm_content ?**| No, just chose one parameter and keep it consistent for all Snapchat Campaigns for now and the future  |