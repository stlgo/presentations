# Writing General Purpose Kubernetes Controllers in Go
https://www.meetup.com/StL-Go/events/270424382/

## Meta 
| | |
| --- | --- |
| **When:** | Wednesday, May 27, 2020 |
| **Where:** | VIRTUAL EVENT, CrowdCast |
| **Presenter:** | Daniel Mangum, [@hasheddan](https://twitter.com/hasheddan) |
| **Group Membership:** |  |
| **Total RSVPs:** |  |
| **Total Attendance:** |  |

## Presentation
As Kubernetes becomes ubiquitous as the operating system for the data-center, organizations are extending the platform to build their own internal PaaS. This generally consists of creating new CustomResourceDefinitions (CRDs) and corresponding controllers to manage them. As a platform grows, it is common for different classes of resources to evolve. For instance, a platform may support provisioning different types of compute resources that each require their own CRD, but are reconciled in very similar ways. Writing new reconcilers with complex logic for every primitive in an infrastructure platform can be cumbersome and error-prone.

Fortunately, making use of common interfaces can make this burden much lighter. In this talk we will explore how to write robust general purpose Kubernetes reconcilers using embedded types, code generation, duck types.

## Presenter
Daniel is a software engineer at Upbound where he works on the open source Crossplane project. He also serves on the Kubernetes release team, and is an active contributor to the Kubernetes project and multiple other open source efforts. He hosts a biweekly live stream show, The Binding Status, focused on extending Kubernetes, building Crossplane, and enabling a multicloud future.

## Recording
https://www.crowdcast.io/e/20200527-stlgomeetup
