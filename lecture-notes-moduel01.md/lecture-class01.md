# Lecture Class 01
---
## Course overview

### Moduel 1
> Linux diagnostics and IT Service Delivery

### Moduel 2
> Windows diagnostics

### Moduel 3
> Software Networking, Virtualization and Cloud Computing

### Moduel 4
> Project

### Course Over view:
CompTIA Exam + Project Week (25%)

CompTIA ITF+ FCO-U61  (100 Points)
- Taking the exam is a requirement to complete 201 but, passing the exam isn't.
- 650 Or Higher = 100 Points
- 650 Or Lower = 90< Points
- Take the exam before end of moduel 4

  ## Lecture: Back up and Restore
  > SYSTEMS ARE REPLACEABLE
  > DATA IS SACRED
At the end of the day most cyber attacks They are aiming to steal data, steal passwords, sensitive information. So the data is the valuable thing that we're trying to secure. Protect.

### Back up Stratagies
 Data inventory, classification of data, Location, Redundancy, and Replication.
 We are also gonna dive into frequency and scheduling.
 How do we test this?
 
 > Backups are unproven until you actually test them

 Alot of this backup strategy is going to be tied into the bigger umbrella of the disaster Recovery plans. we're always gonna have some sort of the disaster recovery plan aspect.
The amount of data you're backing up is always gonna be a factor in when it comes to a lot of things.
  it's gonna be a lot of factor when it comes to how often or how much of your data can you backup?
Because that stuff requires space in the sense of you need that hard drive, space to store that stuff and hardware costs money.

Because in security and in it. In general, the limiting factors are gonna be your budget. You're always gonna be working with a budget.
personnel, Right? How many people you have in your teams? And do they have the time to do all this?

### Backup Types
- Normal/Full
> Backs up everything

- Incremental
> All files changed since last incremental backup
> Low backup Time/ High restore time

- Differential
> All files changed since the last back up
> Moderate backup/ restore time

### OffSite Backups
- Hot Site
> Ready to take ofver for the failed production site immeadiatly.
> The most expensive option

If we blow that up to a data center. Imagine, you have one data center with all your servers, all your stuff that you need to run.
And in order to build the hot site. For that you would pay for another duplicate exactly the same that has all the stuff you need ready to go right?

- Cold Site
> Takes a long time to spin up
> Less costly than Hot sites

 Cold site  is where, you have some of the things you need. But you still gotta put in some work to build it up and get back up and running.
There's some things that have to be figured out, but is the cheapest one, because you don't have all the components and you dont have to front the money for all that stuff.

- Warm Site
> Takes some time to spin up but not as long as a cold site
> Middles the cost to maintain

### Systems Redundancy
***High Avalibility***: Is achieved when redundancy is implemented incase the first server goes down.

The main idea with redundancy is that you have 2 things that are ready to go.
and especially they might be they might be serving the same thing. So it's very common with web servers, for example.

Think of Netflix right! Think of how many people go onto Netflix to watch their shows. Chances are at some point or another, there's millions of people on there, So they probably have biggroups of servers
handling all that traffic. They all serve the same shows. They all serve the same kind of user experience, but they're kind of spreading out that load.

So they're redundant. They all do the same. They all have the same job.

But now we've kind of spread out that load into 10 servers. Let's say, instead of just one.
 That's that that idea of high availability.
So when we achieve this idea of high availability is when we implement that redundancy. And now we're not relying on one server
to be our single point of failure. So, for example, Netflix, they can probably lose 10 servers right and sure the load will be higher on the other ones.
But the user never sees that, because there's other other servers there to kind of pick up that slack.

