# Untangling the Monorepo: Moving to Go Modules
https://www.meetup.com/StL-Go/events/276220371/

## Meta 
| | |
| --- | --- |
| **When:** | Wednesday, September 23, 2020 |
| **Where:** | VIRTUAL EVENT, Zoom/YouTube |
| **Presenter:** | Anthony Lee |
| | Dylan Bourque |
| **Group Membership:** | ??? |
| **Total RSVPs:** | ??? |
| **Total Attendance:** | ??? |

## Presentation
Do you have nearly 400 Go services and libraries tangled together in a Gordian knot of a monorepo? As an early adopter of Go, much of CrowdStrike’s codebase predates the concept of dependency management tools. With the release of Go Modules, many of the assumptions and patterns that have served us well need to be adjusted or discarded. Join Dylan Bourque and Anthony Lee as they detail their Herculean effort to retool the development experience for Go modules.

In this talk, Anthony and Dylan reboot their GopherCon 2020 session by diving into issues they encountered at CrowdStrike while converting the monorepo.

They will be sharing techniques to:
* Evaluate whether multi or monorepo is right for your organization and responsibly untangle the monolith without interrupting developers.
* Identify non-idiomatic and module incompatible code to align with best practices. (We’ve all done things we’re not proud of.)
* Creatively extend an internal module proxy to create “flash frozen” modules from modified third-party dependencies.
* Build shiny, new custom tooling to transition our older, crustier custom tooling to standard, community-supported projects.

## Presenter
Anthony Lee and Dylan Bourque
