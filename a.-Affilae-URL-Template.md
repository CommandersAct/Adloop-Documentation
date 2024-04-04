# a. Affilae URL Template

|||
|-|-|
|**Level in which I put the URL templates**| Account or Affiliate level  |
|  **Where is it located ?**  | To determine with your account manager |
|**What parameters should I use ?**|  _loopcd_ (for all analytics platforms including Adobe, Google or Piano Analytics)using the  _utm_content_  parameter in substitution is possible (only for Google Analytics) |
|**URL template**| Just add the following parameter at the end of the destination URLs `&loopcd=AFa\|{put_here_the_Affiliate_ID}` or put this value in the utm_content `&utm_content=AFa\|{put_here_the_Affiliate_ID}`. The parameter `{put_here_the_Affiliate_ID}` should be filled by the ID of the affiliate as defined by the platform. When the user clicks on the link, it should look like this: `&loopcd=AFa\|01234` |
| **Shoud I use both adlcoid & utm_content ?**| No, just chose one parameter and keep it consistent for all Affilae Campaigns for now and the future  |