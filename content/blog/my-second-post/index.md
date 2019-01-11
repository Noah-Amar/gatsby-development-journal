---
title: The Untimely Death of Kyle Meltzer, Library Heaven, and the Git Labyrinth
date: '2019-01-08T23:46:37.121Z'
---
![labyrinth](https://www.ancient-origins.net/sites/default/files/styles/large/public/extremely-complex-labyrinth.jpg?itok=XPW0xsaH)

Wow! I love blogging so much already.

Today at approximately 10:42am(CST), we learned that Kyle was no longer with us.
Known by some, respected by many, and loved by all... he will be missed.

Most noticeably by the back-end team.

He left behind a Labs9 team brimming with potential that must continue their journey without him.*

After mourning for most of the day, I and the remaining members of the team decided to update the technical design document to more accurately display our awesomeness, as well as discuss how we will proceed to divvy up roles and tasks without Kyle. Through this discussion, we concluded that based upon the mvp requirements and our overall vision for a fantastic product, this project will likely involve more frontend work than backend and thus we can plan out our focus that way. Shannon, AJ, and I will lead the frontend portion, taking ownership of different components and features to build out, while Brian will lead the backend, creating the database and schemas needed for our user accounts. We estimate that the backend will take a quarter of the time it takes to build the frontend and as soon as the necessary functionality is finished, we will have all hands on deck working on completing the frontend.

We are continuing to wait on our request to be approved to grant access for continuous integration with Github using Zeit's deployment service and it's amazing Now feature, which makes deployment as simple as adding a new file to our repository with an empty object inside, marking it to be deployed. More about this tool can be found [here](https://zeit.co/docs/v2/integrations/now-for-github/).

Building upon our plan from yesterday, we compiled a list of libraries and tools best suited to achieve maximum coolness and ease of development while we work to develop the best product possible in the time that we have allotted. 

![go team](http://capitalregioncanstruction.alannajkellogg.com/wp-content/uploads/2015/01/Go-Team-1.jpg)

+ [uppy.io](https://uppy.io/docs/) 
+ [passportjs](http://www.passportjs.org/)
+ [stripe](https://stripe.com/docs/api?lang=node)
+ [npm csv](https://www.npmjs.com/package/csv)
+ [react-chartjs-2](https://www.npmjs.com/package/react-chartjs-2)
+ [node mailer](https://www.npmjs.com/package/nodemailer)
+ [react-spring](https://github.com/react-spring/react-spring)
+ [styled-components](https://www.styled-components.com/)
+ [material-ui](https://material-ui.com/)
+ [react-materialize](https://react-materialize.github.io/#/)
+ [react-strap](https://reactstrap.github.io/)
+ [react-bootstrap](https://react-bootstrap.github.io/getting-started/introduction)
+ [react-router-bootstrap](https://github.com/react-bootstrap/react-router-bootstrap)
+ [react-router-dom](https://reacttraining.com/react-router/web/guides/quick-start)

While we likely will not rely heavily on some of the more generalized (and maybe seemingly redundant) component libraries, and will rather compare them for a wider selection to find the best use case, we agreed it would be useful to come up with a list of tools available to us beforehand and have them all in one place to easily access as well as having all the dependencies in mind that we will need to install.

Continuing with the account of today's progress, my team and I addressed pressing questions to our Project Manager and took a few components each to start building out, later troubleshooting dependency issues that arose.

Sometime later despite walking through our git workflow and what it should look like, AJ entered the Git Labyrinth. We reluctantly followed him inside.

![labyrinth](http://ronkkowatches.fi/wp-content/uploads/2014/05/LABY_Dark.png)

As we focused all of our attention onto finding our way out of the dark abyss, the Labyrinth shifted and morphed, presenting new problems and confusion. Along the way we dropped our spool of thread and hope of finding a way out disappeared. It seems as though we will have to spend the night in this cold, dark place until it is merciful enough to spit us back out. Regardless, this will certainly not be our last encounter with the Maze and though today it was AJ, tomorrow it may be one of us. We will continue to learn and help each other avoid the traps and pitfalls of Git, so that eventually the Labyrinth may swallow no one.


*Note to reader: Kyle did not actually pass into the next life, but rather was compelled to postpone Labs due to unforeseen personal circumstances