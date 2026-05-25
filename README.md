# The Software Engineer's Guidebook
This is my book summary of the book "The Software Engineer's Guidebook" by Gergely Orosz

<img width="350" height="500" alt="image" src="https://github.com/user-attachments/assets/ffd5e5b1-8061-4e88-bb62-371c471f6b12" />
 

## Foundational Skills 

1. **Learn one language very well.** Go deep into its boring topics. Then, when you learn a second language, you still get better at the first one, but you also understand its strengths and weaknesses compared with others.

2. **Understand debugging.** Learn debugging tools. Read code line by line. Put logs and see the result, but also take time to learn and use debuggers. Investigate how experienced engineers debug. Use paper debugging too — draw diagrams, flows, and charts.

3. **Refactoring is essential.** Define the scale of your refactoring. The smaller the safer. Refactor tests as well.

4. **Set up and understand your local development environment.** Learn the powers of your IDE: the shortcuts, code compiling, running the project. These can save a lot of time spent on redundant tasks. Set up shortcuts, color scheme, text size, and configure formatting and linting. Find out how you can run the app easily and compile it fast.

5. **Learn Git from the terminal:** branching, rebasing, resolving conflicts and merging, cherry-picking.

6. **Basic SQL is a must.** You will use it when trying to get data from the DB and during development.

7. **Create a productivity spreadsheet** for the tools the company has for specific cases — links, docs, commands. These help a lot.

8. **Understand the CI/CD.** Learn how it works, what it does in the case of your app, and how to debug it.

9. **Know how to access production logs and dashboards.** Learn how to filter logs for certain users, and how to access crash dumps and errors.

10. **Make small changes in your PRs when possible.** The smaller and more specific the change, the easier it is for a developer to review it.

## The Well-Rounded Senior Engineer

Software engineering is more than just software development. It includes gathering requirements, planning a solution by analyzing the tradeoffs between approaches, building the software, shipping to production, monitoring the solution, extending it to new use cases, and migrating to other solutions.

A software engineer should be invested in the long-term impact of their work, not just the short term. When fixing a bug, ask:

1. How do we ensure this bug will not occur again? (Solution: automated testing.)
2. How do we make sure a similar issue can be detected quickly? (Improve monitoring, logs, and alerting.)
3. Is the fix easy to maintain in the future? (Maybe we should write documentation.)

## Get Things Done

This is the universal important rule regardless of your role. And also: communicate the work you have done.

1. **Communicating your work is crucial, and communicating it well is essential.** Tell what you have done. Bring numbers and data as proof to explain your work in a quantifiable way. Present the problem, then your solution, then the details. Over-deliver and over-communicate.

2. **Deliver consistently.** One of the best ways to be perceived as someone who gets things done is to deliver as much as you can — and sometimes more. And doing it consistently. Though be careful how much more you take on, as sometimes you can bite off more than you can chew and not meet the deadlines.

3. **Notify about blockers soon**, so you can get rid of them soon. Be responsible for unblocking yourself — offer ways you can unblock yourself, like cutting the project's requirements, or having somebody else solve the problem that will unblock you.

4. **Get things done properly**, so when it is done it is really done and working properly.

5. **Push back on starting work** until you have a full understanding of how things should work from the product and customer's point of view.

6. **Sketch a test plan** — how are you going to test your developed feature? Unit tests, local manual testing from the UI. Also, pinpoint if there are any parts that can be tested only in production and how we should test these in QA.

7. **Do not take QAs for granted.** Sit with them and test your task with them instead of waiting for them to do it. It will save a lot of time, but most importantly you will learn from QA about how testing works, so later you can apply those skills yourself before sending the task to QA. In the future, you might not have a dedicated QA and you will be responsible for testing your task — the skills will come in handy here and you will ship higher quality work.

8. **Ship code to production often, likely every day.** Break problems into shippable chunks and ship them. Small problems are easier to solve, easier to review, and easier to deploy.

9. **Write documentation.** When you need to explain a new feature or something you have built, you can lead people to a document instead. Nowadays, with AI, writing documentation has become very easy and fast — but their worth still remains the same.

## Understanding the Business

The most productive engineers aren't always the ones who write code fast and have deep knowledge of computer science. What they frequently are is engineers who are good enough at engineering but excellent at understanding the product, customers, and the business. This helps them come up with smart tradeoffs, build less complex engineering solutions, ship faster, and solve the customers' real problems.

1. **Build a strong relationship with your product manager.** Seek frequent feedback from them.

2. **Understand the business.** As software engineers, we are not paid to write code — we are paid to solve problems for the business, frequently by writing code. So understand the business, what it cares about, and how the software you build helps the company achieve its business goals.

## Collaboration and Teamwork

### Code Reviews

1. **The tone of your review matters.** Reviews with a harsh tone can create an unnecessarily hostile and tense environment and can be seen as micro-aggression. In contrast, a friendly, moderate, and professional tone contributes to gaining good knowledge and having a healthy environment.

2. **Recognize the work done by an engineer.** If they have spent good effort in designing a certain solution, praise them for that and offer your improvement suggestions if any. Remember, the engineer has done work — if you genuinely see a nice solution, applaud them for it. This contributes to a positive environment.

3. **Be tolerant with new joiners.** Good code reviewers are empathetic toward new joiners, as they might not know all the coding guidelines and the unwritten informal rules inside the community. Good code reviewers also put extra effort into explaining preferred approaches and directing them to examples through links, code samples, names, and so on.

4. **Ask questions before giving feedback.** If something is wrong or missing, do not jump into highlighting that the engineer did not do this or that. Instead, reframe it into a question. A question gives the opportunity to share more context, which may clear a misunderstanding you did not know of when doing the review.

5. **The goal of your feedback is to help the other person improve.** As long as you offer feedback that is encouraging and not discouraging, you help them grow.
