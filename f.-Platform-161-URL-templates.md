# f. Platform 161 URL templates

|||
|-|-|
| **What parameters should I use ?**| _loopcd_ (for all analytics platforms including Adobe, Google or Piano Analytics)using the  _utm_content_  parameter in substitution is possible (only for Google Analytics) |
| **URL template**| If Adloop is the only URL parameter add the following `?loopcd=DIp\|${DetectedDomain}\|${AdvID}\|${CampID}\|${CrID}`. If your URL already has other parameters (UTM), add this after: `&loopcd=DIp\|${DetectedDomain}\|${AdvID}\|${CampID}\|${CrID}`. If you opt for the  _utm_content_, use this value : `&utm_content=DIp\|${DetectedDomain}\|${AdvID}\|${CampID}\|${CrID}` |
| **Shoud I use both adlcoid & utm_content ?**| No, choose one.  |