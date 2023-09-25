## Kanban
```
Two key concepts that came out of this culture are Kanban and Kaizen. In Japanese, Kanban just means billboard more or less, though it can be translated more directly as signal card. Ohno implemented the three bin system for parts. There was one bin that was on the assembly floor full of parts. When it was empty, this created a demand signal in the form of a well formed Kanban, a signal card that described what was needed and when, and was attached to the empty bin. After creating the Kanban, the worker would take the bin to the factory store, where he would find the second bin, the one that had the next batch of parts so he could resume work. The store would then prepare a Kanban for the third‑party manufacturer. The order form essentially, and that would constitute the third bin the one full of replacement parts sitting in the manufacturer's warehouse. Kanban exists in software most fundamentally in issue trackers in the form of boards. With Kanban boards, whether they're physical boards with actual paper cards or electronic issue trackers, the status of a work item can be tracked through the various phases of the software lifecycle: new, working, testing, deployment, complete. We'll talk more about applying Kanban later. Kanban has been widely adopted by the software industry, but its sibling concept Kaizen much less so. Kaizen means continuous improvement, becoming better and better one step at a time, over time. Individual steps in Kaizen may yield only small benefits or no benefits at all, but may pave the way for more powerful improvements along the way. Years ago, I worked at a small firm on a team of three, and most of us were working with entirely different projects at the same time. So not a lot of actual integration going on with our code. Our code branches were pretty linear, so the use case for moving to continuous integration was not especially powerful. It would take a few weeks since we hadn't done it before and once it was done, it would really only automate a single step that we are all performing manually that took less than a minute, build the code, look for any problems. The actual payout, the time to recoup the cost of automating the work was probably in years. But I knew the power of Kaizen and though I didn't know at that moment what exactly the value would be, I knew that things that are automated can be improved in a way that manual processes cannot be. So I moved us all to the new build server that had just come out that year, Jenkins. The first value showed up in our deployments, though they were still a manual beyond compare sort of deal. Now we were deploying bills rather than directly from our dev machines. This quickly gave way to deploying automatically with a tool called Octopus Deploy and other Kaizen, like automating unit tests and generating documentation came later. We were eventually able to do a lot of things that would have simply been impossible without our set up. It wouldn't have occurred to us to try because that stuff just wasn't in our world. The key to Kaizen is Teian, the proposal. What are we working on improving? If you don't have an answer to that question, the answer is that nothing is improving. A key principle of Kaizen is that the answer can come from anywhere. I work for a client who had me doing crazy deployment automation, NuGet migration, and Jenkins scripting that would make you go cross‑eyed, all while the developers couldn't debug on their local machines. That stuff I was doing was useful, but I could resolve the problem that every developer had all 60 of them, in debugging locally inside of three days. But nobody said anything and nobody asked until my contract was almost up. The last concept relating to Kaizen I wanted to touch on before we leave this topic is Andon, another Japanese term meaning paper lantern, a lantern that would be lit indicating that there was a problem on the manufacturing floor. This term was later generalized to refer to the cord that the worker, any worker, pulled when he or she saw problem. This democratization of quality control relates to one of the 12 principles outlined in the Agile Manifesto. "Build projects around motivated individuals. Give them the environment and support they need, and trust them to get the job done."
```

## Notes
- Kanban, which means "signal card" in Japanese, originated from the Toyota Production System (TPS) and involves a visual system for managing work items through various phases.
- Kanban boards are used in software development to track the status of work items as they progress through different stages of the development process.
- Kaizen, meaning "continuous improvement," is another concept from TPS that focuses on making small, incremental improvements over time.
- Kaizen encourages individuals and teams to identify areas for improvement and propose changes, even if the improvements seem small.
- The principle of Teian, or proposal, is crucial in Kaizen, as it drives the identification of areas to improve.
- Andon, derived from the Japanese term for a paper lantern, refers to a system where any worker can signal a problem or issue in the manufacturing process.
- The concept of Andon relates to the Agile Manifesto principle of trusting motivated individuals and giving them the support and environment to address problems.