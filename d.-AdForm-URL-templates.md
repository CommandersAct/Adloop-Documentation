# d. AdForm URL templates

|||
|-|-|
|**What parameters should I use ?**| _loopcd_ (for all analytics platforms including Adobe, Google or Piano Analytics)using the  _utm_content_  parameter in substitution is possible (only for Google Analytics) |
|**URL template**| Just add the following string at the end of the destination URL `&loopcd=DIf\|{put the creative ID here}`. If you opt for the  _utm_content_ , use this value : `&utm_content=DIf\|{put the creative ID here}`. Ad Form **does not allow**  **dynamic tracking templates** , so if you want automatic attribution matching, the Creative ID number must be hard coded in the URL parameters.You can use our  **native matching function** . To use our automatic matching function, put exactly in the UTM parameters the names of the campaign, adgroup & ad with one element per parameter. _Example_  : name of the campaign in the UTM campaign, name of the adgroup in the UTM keyword and name of the ad in UTM content. |