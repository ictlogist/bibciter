BibCiter
Copyright (C) 2005-2017 Ismael Peña-López. All Rights Reserved. 
Released under a GNU General Public License version 2.0 (GPLv2)
http://ismael.ictlogy.net
http://github.net/ictlogist/bibciter


BibCiter is an online bibliographic manager, to privately manage your bibliography or openly publish bibliographies on the web.

Multiuser (admin, edit, external).

Lists in APA standards among many others. Other citation styles can be added (with a little bit of coding). 
BibTeX import/export.
RSS feed.

This bibliographic manager was a personal solution for a personal need. You can see it live here:
http://bibliography.ictlogy.net
This bibliographic manager is poorly coded. I never intended to make no serious stuff. Be understanding; be kind.
If you think you can improve it somehow, all contributions will be much welcome.

ismael.


LOG OF VERSIONS

2.0

- major recoding
- minor improvements

1.5

- now it's possible to add tags to works
- now it's possible to include several authors in a work without having to go back again to the work's file
- fixed some security issues
- fixed minor bugs in citation styles
- improved filtering when Bibciter is used as a personal (one author) repository
- fixed minor error in citation of projects
- added possibility to publish projects and bibliographies in Twitter (URLs shortened with bit.ly)
- added ISO citation style
- now, when cloning, includer projects are also cloned
- improved contact form functioning

1.3.1

- fixed a search option that did not work
- improved search routines

1.3

- added RSS feed for EACH author
- added RSS feed for EACH category
- improved the way RSS worked (rss20.xml deprecated)
- added multilanguage feature, now localized into Catalan and Spanish
- fixed some errors in the login procedures, due to malfunctions of cookies
- added "no links" bibliographic style
- improved the output of the searches
- fixed problem in bibliography sorting
- eased the way related and included projects are searched on combos
- improved the form for projects, thus avoiding an error when assigning twice the same author to the same project
- included tagclouds in the bibliographies views
- add works and authors to delicious option
- improved the way BibTeX files are generated

1.2

- improved the behaviour of the toggling sections at the project form (abstract, observations, notes)
- fully changed the installer... had a strange bug that made it impossible to install for some users

1.1

- changed charset to utf-8. Might give some problems if updating
- transformed the database and files to support UTF-8 character coding
- improved the way styles are called (as a variable, not just printed along)
- made some minor changes to be able to work with a WordPress plugin
- created a WordPress plugin so that works and authors can be called from a blog post

1.0	

- way, way, way improved the way projects are cited, including huge improvement in
	bibliography citing styles management	
- solved smallest issue with published works that are "references" (e.g. journals, reviews...)
	and have no publishing date/year	
- slightly improved the exportation to BibTEX format
- improved accessibility
- improved comparison between two bibliographies
- added the possibility to "remember" the user logged in (setting a cookie up)
- in searches, if "not found" or results not satisfactory, possibility to directly add the query as a 
	contact/work
- added the "title" attribute to authors when listed with links, showing the full name of the author
	instead of the "formal/citation" name

0.19

- improved sidebar search form
- better management of nonpublished/forthcoming works
- added new presentation style for bibligraphies: "web_en" to embed in websites an APA styled
	bibliography which includes links to the works on bibciter
- enabled the possibility to compare whatever two bibliographies, regardless if they are hidden and/or public


0.18

- added possibility to sort by year in bibliographies (useful to quicky glance the "range" of a bibliography)
- chaged the sorting option of bibliographies appearing in admin mode besides works: now by ID
- improved bibligraphy presentation filtering
- improved contact presentation filtering
- solved install problem

0.17

- improved the way search results are shown
- minor improvements in bibliography management
- fixed problem in category filtering

0.16

- notably improved the way bibliographies are managed, categorized and presented to both the user and the admin
- fixed the way "forthcoming" (i.e. unpublished) works are listed
- solved idiot error that did not let identify users within a session
- some presentation minor issues

0.15

- added tag cloud to navigate categories
- new feature to compare two biliographies and mass edit their references
- improved the way the bibliographies (list) are shown, filtering by "in progress" and hidden
- solved some import problems
- solved problem with the description of a bibliography (HTML and length)


0.14

- solved counting of works when doing searches with filters
- improved works form
- minor bug fixes
- fixed idiot error when listing the public bibliographies
- fixed error in bibliography search box

0.13

- style improvements in works form
- fixed serious security bug. thanks to the spammer that, by _its_ actions, let me know.

0.12.2

- fixed serious security bug. thanks to the spammer that, by _its_ actions, let me know.

0.12

- added feature that enables uploading files to the server, so you can keep a copy of
you bibliography files in your own website


0.11.2

- corrected minor bugs
- corrected exportation of bibliograaphies

0.11

- you now can clone bibliographies
- you now can mass edit (delete) works belonging to a bibliography by editing it
- more info (public, hide) appears on a bibligraphy view
- minor issues about viewing
- minor code corrections

0.10

- added "number of records found" ("showing XX records") in maing lists: bibs, projects, contacts, categories
- solved privacy bug when showing public/private bibliographies
- added citation preview when editing a project
- solved (again) apostrophe problem with some mysql versions
- added Harvard citation system
- corrected APA citation system (problem with volume and issue of includer projects)
- improved the way citation system and language are selected when viewing bibliographies
- improved privacy when browsing bibliographies by external (not logged) users
- when a project is included into another, if city and editor are blank, includer city and editor values are copied to the included one

0.9.4 

- solved apostrophe problem with MySQL in some text fields (did not happen in all webservers)
- solved problem in retrieving author data when the project is created through "direct assign"

0.9.3.3 

- included "observations" field in the Contact view to users not logged in
- ridiculous error in readme.html


0.9.3.2

- fixed some bad coding in the Categories view
- addes some features when installing, such as update from v0.9.2.2 or older

0.9.3.1

- fixed an important error that made the previous version not to properly work
- install now creates a default non-empty RSS 2.0 feed (rss20.xml), 
to avoid errors when subscribing if no new projects have been added since first install
- a main category is saved automatically (taking at random one of the regular categories) to avoid
having a blank main category
- when assigning a new author to a project, the default order (cross_contacts_projects.order_author)
is set automatically depending on the number of already existing authors. It also sets, by default,
the same type of author than the existing ones
- list of projects by category can now be filtered by year and type of project
- project saves automatically when adding/editing/deleting authors, inclusions and/or relations.
This improvement avoids data accidental data loss if project not saved before any of these actions.

0.9.2.2

- fixed some bugs related to sidebar placing (should be called after some data are loaded, such as
the session and the logged username)


0.9.2.1

- fixed bugs related to bad paths into include tags that worked locally and in some hosting services,
but not in some others (just like SourceForges!).


0.9.1

First public release
