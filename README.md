# Inclusivity in a Diverse Workspace

**Active link:** *[Inclusivity in a Diverse Workspace](https://herbiejames.github.io/ci-individual-assessment/)* 
## Purpose
To introduce diversity and inclusion concepts to employees of a workplace, and offers basic guidance on how to implement these practices.
## Target Audience
Employees of a workspace.
## User Stories
- **Jen Barber, Relationship Management:** The user wants to gain a basic understanding of diversity and inclusion in the workplace or educational environment, so that they can apply those strategies to their team leadership. They seek straightforward information and tips presented in a clear, organised format.
> A landing page comprised of a concise and apparent navigation to the document on company policy creates an unintimidating path to the precise information sought after.

- **Denholm Reynholm, Policy Manager for Company:** The site's content is easy to update with new policy or alterations to previous policy as values and practices develop.
> Having a DOM where all policy is within one, sectioned HTML file makes it easy for the Policy Manager to, with the site owner's graces, edit this document, and replace it with ease. Effective use of comments throughout the i-and-d.html file also facilitate this nature of use.

## Wireframes
![Wireframe](assets/images/wireframe.jpg "Wireframe")

## Accessibility Considerations
i-and-d.html document has been coded into sections, and as one complete article using semantical html. Furthermore, a 'Download' button floats above this article on the i-and-d.html enabling Users to access a .pdf version of the document.
index.html features a large navigation centre, enabling Users to quickly access the most relevant sections of i-and-d.html.
### Core Features (Must-Haves)
- **Policies Article:** A description of the policies Reynholm Industries wishes to promote.
- **Navigation:** A set of buttons, enabling User's to navigate directly to whichever section of the i-and-d.html document they require.
### Advanced Features (Could-Haves)
- **Document Navigation:** A collapsible, simpler version of the navigation feature, available on the i-and-d.html document itself
- **Form:** A separate page that enables Users to submit enquiries, or complaints, about the document's content.
## Deployment Process
Entering the Settings tab of my repo's github page, within the 'Pages' section of 'Code and Automation', I changed the source of my project from 'none' to branch 'main', and saved the change.
### Testing Results
I used the python3 command "http.server" in GitPod to launch my site in a private environment, alongside Google Chrome's Dev tools to preview the site beside it's code. I was able to adjust dimension sizes, and ensure all features would be operable on a multitude of devices. Specifically, this showed me how my first solution to fixing a footer to the bottom of the page would be insufficient if the device's veiwport dimensions exceeded that of the site itself; with a fixed position, the footer sat centrally in the page in these circumstances. I responded to this by using an absolute position for the footer instead, and the page displayed as intended.
### Validation
![HTML Validator](assets/images/Screenshot%202024-10-02%20114003.jpg "HTML Validator")
![CSS Validator](assets/images/Screenshot%202024-10-02%20114153.jpg "CSS Validator")

In response to the validation process, several updates were made to the image alts. No further action was necessary

## Assets Used:
https://theitcrowd.fandom.com/wiki/Reynholm_Industries?file=Reynholmlogo.png
https://pixabay.com/illustrations/portrait-man-office-worker-8694041/