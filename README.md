Backup your sanity datasets to your own offsite storage, AWS S3, DigitalOcean Spaces, Backblaze, Any other S3, Dropbox, Google Drive or Azure.

Schedule backups from Daily to hourly, or provide your own cron schedule. 


### Getting Started

- [Register for SnapShooter.com](https://app.snapshooter.com/register)
- Create your Team
- Choose Sanity Backups
- Follow setup wizard

#### Config

- To go https://www.sanity.io/manage
- Click on your product
- copy Product ID
- Click on the Datasets tab
- Note down the title of your dataset
- Click API Tab
- Add API Token
- Name it e.g. SnapShooter Backups
- Set permissions to Viewer or Editor
- Save
- Copy API Key


If you do not copy the API key when shown you will not be shown again and will have to recreate it, Sanity should email you confirmation that an API key was generated.

#### API Key Information
To connect to your sanity studio dataset we require an API key. This can be a read-only or a read-and-write key. 

If you want to use our automated restore system when something goes wrong you will need a key with write permissions, you can always provide this just before restoring. You will always be free to download the dataset and restore it yourself using your own key, and thus not provide SnapShooter with a write access key.

### Screenshots

![Backup Settings Example](https://i.imgur.com/W52HCqz.png)

![Past Backups Example](https://i.imgur.com/Q7XBI3l.png)
