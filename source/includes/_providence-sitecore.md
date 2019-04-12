# Providence Sitecore 6 DEV

### Support

- Point: Graham <graham@wheelhousedmg.com>, Sheila <sheila@wheelhousedmg.com>
- Backup: Drew <drew@wheelhousedmg.com>

### Tasks In Progress

- CS-104 – Change Banner for Oregon - in CM, awaiting feedback or green light to deploy
- CA-106 – Change Mobile Experience “Navigation” for Oregon - in CM, awaiting feedback or green light to deploy
- COS-74 – Oregon Location Page Updates

### Status

 - Currently there is debate around the implementation of CS-104 as the content team was not involved in the intial tests. The key players right now are Peter (CRO), Whitney (Content), and Guy. There is a meeting set for Tues. 16th which I may not make. This is to determine the way forward with the banner design and layout.

### Notes

- Slack: We have slack channel #prov-sitecore - This has much of Guy’s team on it. @schooley and @Bhanu are our primary contacts.
- Repo: The repo does contain multiple sites. For now we are only supporting Oregon.
- Next up is a meeting to determine final direction for the homepage sliders

### Web Stack and DEV-Ops

- **CMS**: Sitecore 6 (.NET)
- **Primary Domain**: https://oregon.providence.org
- **DEV Domains:**: 
  - https://dev-oregon.providence.org/
  - https://cm-oregon.providence.org/
- **Code Control?**: Yes
- **Repository**: https://bitbucket.org/medtouch/providence-oregon/branches/
- **Repository Access**: Bitbucket Access granted to Dustin, Graham and Drew by <Jeremy.Kinser@providence.org>, requests for other access should go through Jeremy.
- **RDP Access**: Personal Credentials emailed to Dustin, Graham and Drew from <Joseph.Schooley@providence.org> on Jan 10, 2019.

> Here are the connections you can now RDP into:

```shell
dev (WEB-SC-DEV): 104.42.55.216 #Sitecore files located at F:\inetpub\wwwroot\dev-oregon.providence.org\
stage (WEB-SC-CM01): 104.42.74.29 #Sitecore files located at F:\inetpub\wwwroot\cm-oregon.providence.org\
prod 1 (WEB-SC-CD01): 104.210.48.125
prod 2 (WEB-SC-CD02): 104.42.46.44
prod 3 (WEB-SC-CD03): 104.42.49.191
prod 4 (WEB-SC-CD04): 104.42.195.182
```
### DEV Update Procedure
- Clone local repository
- Create Feature Branch from Release
- Make Code Updates
- Copy and Paste to WEB-SC-DEV to view on dev-oregon.providence.org
- Coordinate with Guy's team for release to CM
- Guy to coordinate release to Prod
- Ensure that pull-request is made to "release" branch for Med-Touch