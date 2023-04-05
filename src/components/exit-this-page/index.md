---
title: Exit this page
description: Give users a way to quickly exit a service, website or application quickly and safely.
section: Components
aliases:
backlog_issue_id: 213
layout: layout-pane.njk
status: Experimental
statusMessage: This component is currently experimental and part of a community consultation.
---

Give users a way to quickly exit a service, website or application quickly and safely.

This component must be used together with the pattern to help a user [exit the page quickly](/patterns/exit-the-page-quickly/).

## When to use this component

Use the component on pages with sensitive information that could:
- put someone at risk of abuse or retaliation
- reveal someone’s plans to avoid or escape from harm

For example, when a potential victim is using a service to help them leave a domestic abuser.

You can use the component on either:
- all the pages in a service
- parts of the journey with sensitive information

## When not to use this component

Do not use this component if the service or content is unlikely to put a user at risk. See the [Exit the page quickly](/patterns/exit-the-page-quickly/) pattern for examples of at-risk and sensitive topics.

Keep in mind that seeing this component might discourage certain users from using your service. If the user does not identify themselves as being at risk, they might see the button on a service and decide it’s not relevant to them.

## How it works

There are 2 ways to use the exit this page component. You can use HTML or, if you are using Nunjucks or the GOV.UK Prototype Kit, you can use the Nunjucks macro.

The Exit this page component has several parts, including:
- a button, that takes the user to another website
- a secondary link, to give people that use assistive technologies a way to activate the component
- a loading overlay, to immediately clears any content off the browser until the next website loads

All parts of this component must be used together and alongside the Exit the page quickly pattern.

## Adding a button

Position the button component immediately below the header of your page. Its position should be 'sticky', so that as the user scrolls down the page, the button remains visible and is easy to activate. 

On mobile devices, position the component at the bottom of the screen at all times. This makes it easier to press with their thumb and hidden with their hand.

When the user presses the button, their browser will immediately go to a predetermined page that’s set in the code, which is BBC weather by default.

### Choosing a different website to load

The component is set to take the user to the [homepage of BBC Weather](https://www.bbc.co.uk/weather). You can change this if there’s a more appropriate site for your users.

Avoid websites that might show personalised pages (such as frequently visited, last visited, or suggested links), as this content could put the user at risk.

## Consider what to do user session data

You’ll need to decide if your service will store the user’s session data after they’ve activated the Exit this page component and left your service.

We recommend that services clear the user’s session data once they’ve activated Exit this page. This can be through the button, the secondary skip link or pressing the shift button 3 times.

## Adding the secondary link

The code will need to go in the layout file of your service. It will need to go after your block header.

To activate the secondary link, users will need to either:
- tab to the Exit this page link
- press the shift key 3 times

These will perform the same action as pressing the button.

### Showing progress for 'Shift key' presses

To show the user the number of times they’ve pressed the shift button, there’s a series of 3 progress dots under the button, provided as a visual enhancement. Each time the shift key is pressed, one of the dots will be filled.

The user has 5 seconds to press the shift key 3 times. After that, the sequence and progress dots will reset.

This feature requires the user to have Javascript enabled on their browser.

## Loading overlay

When the user activates Exit this page, a ‘loading overlay’ will immediately appear. This is to help users with slow connections clear their screen until the browser loads the next page.

## Research on this component

The design of this component is based on research with people with a lived experience of domestic abuse and people with accessibility needs, and in consultation with the Ministry of Justice, Department for Work and Pensions and the Scottish Government.

Live examples of similar components can be found on these websites:
- [GOV.UK: Check if you can get legal aid](https://www.gov.uk/check-legal-aid)
- [GOV.UK: Apply for help arranging child maintenance](https://child-maintenance.service.gov.uk/apply/eligibility/info)
- [mygov.scot: Domestic abuse support](https://www.mygov.scot/domestic-abuse/)
- [Women’s aid website](https://www.womensaid.org.uk/)
- [Refuge website](https://www.nationaldahelpline.org.uk/)

### Accessibility features and considerations

We'll explain why there’s the keyboard option and the skip-link version.

We'll explain our testing with Dragon, and what we expect to be possible.