# Azure Cloud Console (preview)
This repo includes staged documents for the Azure Cloud Console. Please refer to these documents for updates throughout previews.

## About Azure Cloud Console
The Azure Cloud Console is a free service providing a browser accessible BASH shell. 
This console provides users with the ability to interact with Azure resources via the Azure CLI 2.0 which is pre-installed. 
Additional developer tools are also pre-installed, if you find vital tools missing please email juluk@microsoft.com and we will evaluate including more tools. 

This service is launched via the Azure Portal and as a result, allows single-click cli access to your subscription resources.

## Access 
In order to receive internal access you must:

1. Be whitelisted - this was achieved via a sign-up form on the blog announcement through January 10th, internals may email juluk@microsft.com to request further access. <br>
2. Navigate to [aka.ms/accbeta] (www.aka.ms/accbeta). This shortlink provides full Ibiza access so it can be used as a replacement link. <br>
3. Launch the console via the terminal icon on the top navigation pane.

## Console timeout
Your console is set to timeout after 10 minutes of zero output activity. You can reactivate your console by pressing the "Enter" key after timeout.

## Availability
This service is currently available to select Microsoft internals only.

## VM sku
Your console is running on a single-tenant F1 during preview.

## Pricing
This will be a free service to all Azure customers.

## Supported browsers
The cloud console is supported for Chrome, Firefox, Safari, IE, and Edge.

## Feedback
Please utilize the smiley face icons in Ibiza to provide feedback about the ACC.

## Updates

## Known Preview Issues
1. CLI 2.0 latency is a known to be slow, 4-5 second latency per command. This is an open issue with the CLI team.
2. Force kill/restart is coming soon, if your console freezes please open an issue with repro details. Refreshing the page and relaunching the console will clear the state.