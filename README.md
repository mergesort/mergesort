# I am an A+ developer. You can tell because that's what my README says and you cannot lie on the internet.

The libraries and code snippets I share are a labor of love to help developers build better apps, making it easier for you to unlock your creativity, and make something amazing for yourself and your users. If you find my open source valuable I would really appreciate it if you'd consider helping [sponsor my open source work](https://github.com/sponsors/mergesort), so I can continue to work on projects like Boutique to help developers like yourself.

---

### And these are some of my libraries people seem to enjoy using.

#### [Boutique](https://github.com/mergesort/Boutique)
Boutique is a simple but powerful persistence library, a small set of property wrappers and types that enable building incredibly simple state-driven apps for SwiftUI, UIKit, and AppKit. With its dual-layered memory + disk caching architecture Boutique provides a way to build apps that update in real time with full offline storage in only a few lines of code using an incredibly simple API.

#### [Bodega](https://github.com/mergesort/Bodega)
Bodega is an actor-based library that started as a simple cache based on reading and writing files to/from disk with an incredibly simple API. Today Bodega offers a form of infrastructure that any app's data layer can use. Whether you want to store Codable objects with ease, build caches, or interface with your API or services like CloudKit, it all works in just a few lines of code. Best of all, Bodega powers Boutique's automatic offline support. 

#### [Model View Controller Store](https://github.com/mergesort/MVCS)
A sample project demonstrating the Model View Controller Store architecture I developed, powered under the hood by [Boutique](https://github.com/mergesort/Boutique) and [Bodega](https://github.com/mergesort/Bodega). If you'd like to familiarize yourself with Model View Controller Store you can play with the sample app or you can read about the philosophy, along with a very technical walkthrough in this [post](https://build.ms/2022/06/22/model-view-controller-store/).

#### [TableFlip](https://github.com/mergesort/TableFlip)
`UITableView` and `UITableViewCell` animations are hard — really hard. But what if they didn't have to be? Instead of calling brittle methods like `reloadRows()` or `batchUpdates()` and hoping it works, the entire API for TableFlip has one function. Call `reloadData()` like you always do to get a guaranteed `UITableView` state, then call TableFlip's `animate()` with an `Animation`, and your animation is guaranteed to succeed.

#### [FeedbackEffect](https://github.com/mergesort/FeedbackEffect)
A micro-library for playing sound effects and providing haptic feedback, bundled into one line of code. Give your users that special touch by integrating sound and feel into your apps, easier than ever.

#### [Slope](https://github.com/mergesort/Slope)
Flat is out and gradients are in again! Slope makes it incredibly easy to build uniform or percentage based gradients, vertically, horizontally, diagonally, or even radially. You'll be making gradients in no time with the straightforward type-safe API is very straightforward, a real help for UIKit apps where gradients are still hard to make.

#### [GenericCells](https://github.com/mergesort/GenericCells)
Never make another `UITableViewCell` or `UICollectionViewCell` subclass again. Leveraging the power of generics GenericCells lets you build a UIView, and plug it directly into a cell, no extra classes needed.

#### [TypedNotifications](https://github.com/mergesort/TypedNotifications)
A simple drop in package to replace `NotificationCenter`'s untyped API with a typed version. The API mimics `NotificationCenter`'s API so much that you'll barely have to make any changes, but will get the benefit of type safety across your apps.

#### [Anchorman](https://github.com/mergesort/Anchorman)
Anchorman is a slick library that makes interacting with autolayout declarative and easy. There are many out there like it, but people seem to really enjoy using Anchorman for it's straightforward and intuitive syntax.
