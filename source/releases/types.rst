Types of Releases
=========================================================

Prior to every official stable release of a new major version of any Astrana software, 
there usually are a few releases for the purposes of testing and previewing the 
software before it is made Generally Available (GA).

These "test and preview" releases are tagged as Alpha, Beta or Release Candidate (RC)
releases, according to  how confident the Astrana Project maintainers are in a 
release's overall quality and stability.

Test and preview releases are not yet stable enough for production usage, but are 
essential milestones on the road to an official stable release. They allow a 
much wider pool of users to test the latest code and provide feedback before 
the official stable release. 

.. CAUTION::
These releases should only be downloaded and used by developers very familiar 
with Astrana or those wishing to help find defects in the software.

Alpha Releases
--------------

Alpha releases are *very* early versions of the next major Astrana update. 
They may be made available months before the first Beta release. 

They typically receive minimal testing and have the potential to be unstable 
or be missing features planned for the next major stable release.

These are the first to become available and are the least stable. 
When released, most reported defects are resolved, but there are most likely 
still outstanding known issues, which might include security issues.

Alpha releases are usually created when the Astrana Project maintainers believe 
there is sufficient benefit from creating 

Beta Releases
-------------

Beta releases are usually only created when:

* The project maintainers are confident that all new and changed features are functionally complete and have been reasonably well tested.
* Almost all automated tests are passing and the minimum test coverage requirements are met.
* No blocker or critical severity bugs, vulnerabilities, and code smells are detected by code analysis.
* All critical data loss and security defects are resolved.
* Most of the problems with the upgrade path are resolved and it's possible to successfully upgrade a copy of the Astrana staging environment database to the new Astrana version.

Throughout the Beta release period: 

* Usability features will still be considered
* Localizations (e.g. translations) may be altered
* Fixes for discovered defects will be applied.
* **If absolutely necessary**, the APIs and/or data model could change (e.g. to fix a critical defect). 

Release Candidates
------------------

These releases are considered nearly stable and very close to being ready for official release.

Release candidates are usually only created when:

* No more critical or major defects have been found or reported in the most recent Beta release. 
* All automated tests are passing and the minimum test coverage requirements are met.
* No blocker, critical or major severity bugs, vulnerabilities, and code smells are detected by code analysis.

At this stage, no more usability changes will be allowed, and localizations (e.g. translations) are usually unchanged.


Once a feature freeze is announced, no new features will be added to that version of Astrana. 
 and any new features or change of behavior will need to go into the next release version.

This doc is cross-referenced with Release naming conventions.


Patch Release
-------------

These releases are created and made available very rapidly in order to address 
a critical or high severity issue - usually something that likely will or is 
currently causing significant harm to end-users of the software.