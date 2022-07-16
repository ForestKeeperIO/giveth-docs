---
id: troubleshooting
title: Troubleshooting
slug: dapps/troubleshooting
---
import useBaseUrl from '@docusaurus/useBaseUrl'


If you are having technical problems with the Giveth DApp, you may find a solution on this page.

## Brave Browser

If you try to sign into the Giveth DApp with Brave browser, Torus (the wallet provider) notifies you that it needs cookies to operate. (Torus needs these permissions for their OAuth services, so our users can be provided easily with their own Ethereum wallet that is tied i.e. their Google account.)

To quickly solve this problem you can:

- click on the site settings (Brave icon)
- change the cookie setting just for Giveth.io to "all cookies allowed"

<img
  alt="Enable Cookies in Brave"
  src={useBaseUrl('img/content/screenshot-brave-cookies.png')}
/>

[Read more about handling cookies in Brave.](https://support.brave.com/hc/en-us/articles/360050634931-How-Do-I-Manage-Cookies-In-Brave-)

### Giveth.io shows a blank screen! Help!

Sometimes updates get pushed to the Giveth.io website, and your cached files and cookies don't always get along well with the new updates on the site, so you'll need to clear your cache, delete your cookies, then refresh the browser.

To clear your cache and cookies on Brave, navigate to: ``Settings -> Additional Settings -> Privacy and Securiy -> Clear Browsing Data `` Once you're arrived there, check off `Cookies` and `Cached images and files`, and make sure at the top of the pop-up window you check off the appropriate Time Range. You can select `All Time` just to be sure you got 'em all.

Clearing your cookies will log you out of most sites. If you don't want to go through the hassle of logging back in to all the websites you frequent, then head to: ``Privacy and Security -> Cookies and othersite data -> See all site cookies and other data`` Then from this menu look up the Giveth domain like so:

<img alt="Deleting Cookies in Brave" src={useBaseUrl('img/content/givethcookies.png')} />

Then click the trash icon to delete the cookie for Giveth. If that's finished, pull up a fresh Brave browser window, head back to Giveth, and get back to giving!
