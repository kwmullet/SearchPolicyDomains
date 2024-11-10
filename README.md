# SearchPolicyDomains
As currently implemented, this is a file you can paste at the end of a Google search to restrict the search to a list of what University of Pennsylvania determines to be the top 100 US "think tanks."  I'm assuming "think take" = policy institute.

- v. 0.1 — proof of concept.  If this works, and I'm not the only user, then I would consider the next level of development reasonably including but not limited to:
  - Multiple sources from which to scrape the domains of policy institutes
  - splitting it into multiple paste files for different scopes or disciplines
  - including R, Python, and/or Bash code for the user to update their own copies of the files.

My source for these domains is:
<p style="padding-left: 4em; text-indent: -4em;">Humphrey, L. (2024, October 18). Research Think Tanks: Top Think Tanks—US [Penn Libraries Guides]. University of Pennsylvania Libraries. https://guides.library.upenn.edu/c.php?g=1035991&p=7509974 </p>

I manually added [The National Conference of State Legislators](ncsl.org), so I probably do need to include more sources.

## how to use it
### Mac OS
To use this with a Mac, try these steps.
Once you download policyDomains.txt, you can use this command line to load it up into your paste buffer:
```
cat policyDomains.txt|pbcopy
```
Next, do your Google search in your browser, and paste the contents of your paste buffer at the end.

### MacOS, if you want to skip the download step
Use this command line to load it up into your paste buffer
```
curl --silent https://raw.githubusercontent.com/kwmullet/SearchPolicyDomains/refs/heads/main/policyDomains.txt|pbcopy
```
Next, do your Google search in your browser, and paste the contents of your paste buffer at the end.

### MS-Windows
To use this from a PC, try these steps.
Once you download policyDomains.txt, you can use this command line to load it up into your paste buffer:
```
type policyDomains.txt|clip
```
Next, do your Google search in your browser, and paste the contents of your paste buffer at the end.

Please [send me an email](mailto:kwm+SearchPolicyDomains@themullets.net) if you have anything to say about this, such as suggestions, questions, indignant responses, or offers to collaborate.



