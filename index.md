# ITIL Tickets to Products

## Gantt is the Enemy of Great

More recently I've been working in organisations that are making a 'lung for the future'. They want, and for good reason, to be product oriented, to move quickly in response to market changes. Out with you foul project thinking, be gone the brandisher of the gantt chart of doom, we are Agile!

## Times they are a change'n

Leadership teams have limbered up and adopted, at least in principle (true change is hard and most likely requires a few attempts), Agile ways of work. It looks good and seems to solve many of the project delivery problems that large organisations suffered from, the problem being for the most part non-delivery.

Agile, as you know, allows projects to operate in a more iterative manner, small build cycles, fast feedback, and experimentation. Of course increased delivery cycle frequency reduces the project risk profile, measuring regularly rather than relying on that big bang at the end, spoiler, it was often (if not always) a fizzer... sometimes a bomb explosion 'in your face!'.

With project methodology sorted then came the operational reality of sub monthly nay sub weekly delivery cycles. It was as if a million Sys Admins cried out and then fell silent as the Agile Death Star's orbit provided a firing solution.

Enter the way of the DevOps dragon to save the promise of Agile. The solution was to build systems that allowed the development team to operationalise the product at will, 
```
git push --set-upstream origin mic-drop
```
with testing (and increasingly security) built into the build pipeline. Now we are cooking with gas, or at least containers and microservices.

This looks and feels pretty good, the business, development and operations are 'Sympatico' as they say. I'm sure you'll agree the project team has a methodology that embodies all the best parts of the lean manufacturing movement and it has the tools to deliver thanks to following advances in technology.

## BAU - Bad as Usual

Project teams are working in sprint cycles typically 2 weeks in duration. There's the agreed tasks that are going to be worked on in the Sprint following dutiful backlog grooming, nothing can interfere with that. The team has defined done, great. However as we know 'stuff' happens and when it does typically, and completely at odds with all the good stuff, I've just written about 'stuff' gets handed to a team completely unrelated to the project team that deployed the solution.

The end result is, quite frankly, a sh&t experience for the user/s. I call this 'the drop off', the jarring experience that is the result of 'over the fence IT' ironically to ensure the organisation remains Agile.

Enter the world if Incidents, Services Requests, Questions and Problems which seem to hark back to a time before Agile before DevOps where risk and change management reigned supreme, where solutions were static and organisational requirements rarely varied (and BTW projects regularly failed to deliver on any metric you'd care to mention).

There was a time, before hyperscaling before digital disruption, where the ITIL methodology helped bring some order to the chaos without pumping the breaks on organisational agility, but I'm calling it, 'it's over'. It's over in terms of ITIL and support operations being a stand alone function that can somehow offer intrinsic value in a fast moving environment powered by Agile methodologies, Source Control, CI/CD pipelines, Containers and Kubernetes.

Please let me be clear, ITIL and the processes it codified are valuable and should not be thrown out like yesterday's jam but as a stand alone function, a team busying itself implementing and operationalising ITIL within an organisation, no that's not going to work.

## From Support Team to Support Capability

The solution to avoiding the 'drop off' without throwing away yesterday's jam is in my opinion to think less about IT Support as a team within an organisation but rather a capability within a team. The people that are best positioned to deal with the stuff that happens should indeed be the ones that actually deal with it, anything else is going to be suboptimal. Therefore the ability to handle operational issues of a project should be baked into a project!

## From Project to Product

Hang on a cotton pick'n second, a project has a defined lifetime it's not going to hang around forever! True so we need to challenge the idea of projects and level up to product thinking as well.

A project is an activity, governed by a nominated practice or methodology, of a product team. It's how product teams get things done. This is radical thinking I know but when you change your perspective from project to product then the idea of having support capability built into the product team's structure starts to make sense. It also creates an environment where the 3 ways of DevOps, as discussed in the DevOps Handbook (Kim, Humble, Debois and Willis (2016) The DevOps Handbook How to create world-class agility, reliability, & security in Technology Organisations) Flow, Feedback and Continual Learning, with a particular focus on Feedback can thrive. After all the product team will be getting 100% of the Incident, Service Request, Question and Problem data feed directly to them in real time, how's that for a fast flow feedback loop!

Hold your horses there cowboy! You just started talking ITIL again! Yep and for good reason ITIL methodologies make sense, just not independently of the practices that occur as part of the Product team's activities. ITIL gives the Product team a framework to build out their support capability with all the lessons of the past baked in!

This idea was also explored in the excellent book Team Topologies (Skelton and Pias (2019) Team Topologies, Organising Business and Technology for Fast Flow).

>'Traditionally, many organizations used a single cross-service team to support applications and services in the live/production environments. When speed of change and system complexity were low, this model enabled organizations to optimize costs around the number and skills of people in the support team. However, with rapid and constant change to software systems, successful organizations are now looking again at the composition and placement of support teams to aid the flow of change rapidly and safely. The model for IT support that consistently seems to work best has two aspects: (1) support teams aligned to the stream of changes, and (2) dynamic cross-team activity to resolve live service incidents.'

So is the Support Team as a 'thing'no longer required in your grand vision here Karl? Well the answer is... complicated. Support teams independent of Products are not required no. However, their methodologies, tools and practices very much are required. Support teams are required as a vehicle for building capability within product teams quickly and efficiently. Henceforth a support 'team' should be focussed on the appropriate application of practices and methodologies to encourage the fast flow of feedback, to ensure that the end user does not experience some horrible 'drop off' as they interact with a team that lacks knowledge and context and get the very best experience from the product possible all while maintaining the pace and agility to ensure the organisation can adapt and win in a dynamic environment.
