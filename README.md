# YouTube-Podcast
Template to transform your youtube channel into a Podcast hosted on Anchor.fm

[youtube-to-anchorfm](https://github.com/Schrodinger-Hat/youtube-to-anchorfm) is a wonderful tool which will upload your YouTube videos as a Podcast to Anchor.fm  
  
Building on the great work of the fellows at [Schrodinger-Hat](https://github.com/Schrodinger-Hat), this tool will convert your entire youtube channel into a podcast as well as continuously monitor for new videos.
  

## Getting Started
1. Use this template. 
2. Set up the following [GitHub secrets](https://docs.github.com/en/free-pro-team@latest/actions/reference/encrypted-secrets#creating-encrypted-secrets-for-a-repository): 
	- *ANCHOR_EMAIL*
	- *ANCHOR_PASSWORD*.
	- *YOUTUBE_CHANNEL_ID*
	- *PERSONAL_ACCESS_TOKENS*  
		- [Creating a personal access token](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token) and [Triggering a workflow from a workflow](https://docs.github.com/en/actions/using-workflows/triggering-a-workflow#triggering-a-workflow-from-a-workflow)  

This environment variables are mandatory as they specify the sign in account.
