# b. Awin URL Template

|||
|-|-|
|**Level in which I put the URL templates**| Account or Affiliate level  |
|  **Where is it located ?**  | To determine with your account manager |
|**What parameters should I use ?**|  _loopcd_ (for all analytics platforms including Adobe, Google or Piano Analytics)using the  _utm_content_  parameter in substitution is possible (only for Google Analytics) |
|**URL template**| Just add the following parameter at the end of the destination URLs `&loopcd=AFz\|{affiliate_id}`. If Adloop is the only tracking template: `?loopcd=AFz\|{affiliate_id}` or put this value in the utm_content `&utm_content=AFz\|{affiliate_id}`. The parameter `{affiliate_id}` should be filled by the ID of the affiliate as defined by the platform. When the user clicks on the link, it should look like this: `&loopcd=AFz|01234` |
| **Shoud I use both adlcoid & utm_content ?**| No, just chose one parameter and keep it consistent for all Awin Campaigns for now and the future  |