---
title: Exit the page quickly
description: Give users a way to quickly exit a service, website or application quickly and safely.
section: Patterns
theme: Help users to…
aliases:
backlog_issue_id: 213
layout: layout-pane.njk
status: Experimental
statusMessage: This component is currently experimental and part of a community consultation.
---

Give users a way to quickly exit a service, website or application quickly and safely.
Use this pattern to add the [Exit this page](/components/exit-this-page/) component to your service and help users use it safely to protect their privacy.

## When to use this pattern

Use this pattern to help the user protect their privacy when your service contains sensitive information that could:
- put someone at risk of abuse or retaliation
- reveal someone’s plans to avoid or escape from harm

For example, a potential victim using a service to help them leave domestic abuse.

Other examples of sensitive information that could put users at risk include:
- rape or sexual assault
- child abuse and neglect
- any other type of abuse
- stalking and harassment
- reporting crime or fraud (whistleblowing)

## When not to use this pattern

You should not use this pattern for standalone content pages, such as dashboards and guidance. In these cases, use the Exit this page component on its own.

## How it works

First, you’ll need to add the [Exit this page](/components/exit-this-page/) component to your service and decide how it should work within your service.

The component has several parts, including:
- a button, that takes the user to another website
- a secondary link, to give people that use assistive technologies a way to activate the component
- a loading overlay, to immediately clears any content off the browser until the next website loads

Next, you’ll need to create new content pages in your service.

The purpose of these pages are to:
- tell the users how to use ‘Exit this page’ to protect their privacy
- give users information they need to stay safe online

Keep in mind that this pattern is not a complete solution to eliminating all possible risk to the user. Perpetrators can monitor potential victims through other methods, such as malicious software.

## Interruption page

Create a page to tell users what Exit this page does.

Show this page just after the start point of your service, and just before the user sees the Exit this page button for the first time. 

On longer services, you might need more than one interruption page.

The page should tell the user:
- about the ‘Exit this page’ button and what it’s for
- what happens when they press it
- that they can also activate Exit this page by pressing shift 3 times or [using the secondary link](/exit-this-page/#adding-the-secondary-link)

The page should also tell the user that:
- their browser history will not be erased. 
- any information they’ve entered will not be saved, depending on what you’ve [decided to do with user session data](/components/exit-this-page/#consider-what-to-do-user-session-data)
- to return to the service, they can search for the site they were using, or find it in their browser history
- there are other things they can do to stay safe online – include a link to a ‘safety content page’ where they can learn more

## Safety content page

Create a page to give users important information they need to stay safe online.

Generally, this page should tell the user other steps they can take to protect their privacy.

What you include will depend on your service and who uses it. But wherever practical, you should recommend that the user takes some basic steps such as:
- only using your service on a public device, such as in a library
- using private browsing
- clearing their browsing data and cookies

Example of a safety content page:

<hr class="govuk-section-break govuk-section-break--xl govuk-section-break--visible">

## Ways to stay safe online

It can be easy for someone to see what you’re doing online, especially if you’re using a home computer.

You can make it more difficult for them by taking some precautions.

If you think your devices or internet search activities are being monitored, try to use a device that is not being monitored. That should be a device that the person does not or has not had physical or remote access to. This is the safest thing to do if you do not want someone to know that you’re visiting certain websites.

### Cover your tracks online

Every time you use the internet, your browser stores a record of where you’ve been online with:
- a list of the pages you’ve looked at and the files you’ve downloaded
- small files called cookies which remember your settings for different sites

### Deleting browser history
You can improve your safety by deleting your browser history. But you need to be careful because:
- deleting cookies will also get rid of stored passwords for online accounts
- clearing your history could make someone more suspicious

Try to only remove information about the websites you want to keep private. You can find out how to do that on:
- [Google Chrome](https://support.google.com/chrome/answer/95589?hl=en&rd=1)
- [Internet Explorer](https://support.microsoft.com/en-us/windows/view-and-delete-your-browsing-history-in-internet-explorer-098ffe52-5ac9-a449-c296-c735c32c8678)
- [Mozilla Firefox](https://support.mozilla.org/en-US/kb/delete-browsing-search-download-history-firefox)
- [Safari](https://support.apple.com/kb/PH19215?locale=en_US&viewlocale=en_US)
- [Opera](http://www.opera.com/help/tutorials/security/sharing/)

### Browsing in private

You can also look at a website without information like cookies being stored by using the private browsing setting in your browser. Go to the menu, click on ‘File’ and choose:

- InPrivate on Internet Explorer
- Private Browsing on Mozilla Firefox or Opera
- Incognito on Google Chrome
- Private Window on Safari

<hr class="govuk-section-break govuk-section-break--xl govuk-section-break--visible">

Useful resources to help write this safety advice include:
- [Refuge: Secure your tech](https://refugetechsafety.org/secure-your-tech/)
- [Women’s Aid: Cover your tracks online](https://www.womensaid.org.uk/information-support/what-is-domestic-abuse/cover-your-tracks-online/)
- [National Cyber Security Centre: Information for individuals and families](https://www.ncsc.gov.uk/section/information-for/individuals-families/)

Let us know if you know about any other useful resources we should add to the list.

## Research on this pattern

The design of this pattern is based on research from a specialist provider of services to survivors of domestic abuse, and in consultation with the Ministry of Justice, Department for Work and Pensions and the Scottish Government.

Live examples of similar components can be found on these websites:
- [GOV.UK: Check if you can get legal aid](https://www.gov.uk/check-legal-aid)
- [GOV.UK: Apply for help arranging child maintenance](https://child-maintenance.service.gov.uk/apply/eligibility/info)
- [mygov.scot: Domestic abuse support](https://www.mygov.scot/domestic-abuse/)
- [Women’s aid website](https://www.womensaid.org.uk/)
- [Refuge website](https://www.nationaldahelpline.org.uk/)