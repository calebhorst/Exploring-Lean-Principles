## What Is Waste in Software?
```
Waste, by definition, is something we don't want. If we wanted, it wouldn't be waste. But the meaning of waste in software is not entirely obvious. Is spending more on tools waste? Is the time spent generating documentation when it might change waste? Again, antithesis is a useful tool here. The opposite of waste is value. So the job of identifying waste is the job of identifying value. In my war stories from the first section, clearly the enterprises I mentioned had not adequately done the job of identifying value. In manufacturing, Ohno regarded inventory kept just‑in‑case as waste, and the equivalent of this in software is partially completed features. This can arise from developers not being allowed to focus on their work and being constantly pulled in new directions by new requirements. And on the other end of the scale, it can arise from gold plating, the practice of adding features that aren't really required just because you have time at the end of the schedule. I worked at a company where we had a software package that transformed Word documents into web pages, along with some transformation of that content for different security levels and groups. I argued passionately for a REST API so that we could deploy a server for our customers, and then they could just make simple API calls into it and embed the content directly in their company websites. It was a good idea, but over the next eight years that I supported it, no customer ever used it, not even one. Not even the companies that were sophisticated enough to set up complex single sign‑on applications with our systems to avoid having to use that API. I had failed to adequately identify value and my pet REST API was waste. Principle one, eliminate waste. We'll spend the entire next section with a magnifying glass on software waste.
```

## Notes
Identifying waste in software development can be challenging because waste often hides behind activities that may seem necessary or valuable at first glance. Waste in software development can be defined as anything that does not add value to the end product or the development process. To identify waste effectively, it's crucial to think in terms of value and what contributes to it. The opposite of waste is value, and the goal is to maximize value while minimizing waste.

Some common examples of waste in software development include:

1. **Partially completed features:** Features that are started but not finished, often due to changing requirements or constant context-switching.

2. **Overly complex tools:** Spending resources on tools or technologies that do not significantly improve the development process or end product.

3. **Excessive documentation:** Creating extensive documentation that may become outdated quickly or is not needed for the intended audience.

4. **Gold plating:** Adding unnecessary features or functionalities that are not requested by users or stakeholders.

5. **Unused code:** Writing code that is never used in the final product.

6. **Waiting:** Developers waiting for approvals, feedback, or resources, leading to idle time.

7. **Bugs and defects:** Fixing defects and issues that could have been prevented earlier in the development process.

To adhere to Lean principles, the goal is to eliminate these types of waste and focus on activities that directly contribute to the value of the software product. The next section will delve deeper into identifying and addressing software waste.