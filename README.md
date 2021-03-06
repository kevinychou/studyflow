## Website Summary

*Problem:* StudyFlow addresses the productivity and mental health difficulties of studying at home; it's a Pomodoro Timer with multiple features → An integrated flashcard app, extra fun buttons, and the ability to poke your friends!

*Inspiration:* The idea came from one of our own needs; we wanted a tool that enables you to practice flashcards more consistently, while also encouraging you to study. By merging the timer and flashcards into a single website, it reduces the friction the typical student faces when deciding to study or to relax.

*But wait, there's more!*

*Further Functions:* Humans are social creatures - it's unsurprising that so many of us have felt demotivated during COVID-19 and working from home. And so, our website has a range of extra functions to keep things entertaining! A meme button (which generates and displays a funny meme or a cute dog), an exercise button (which suggests a random short exercise to keep your physical body engaged), and finally, our poke button. Although we weren't able to implement this in our current website as the API for Facebook poking requires whitelisting, the idea is that you can poke your friends during your breaks so that you can show off that you've finished a study session!

And of course, in both the spirit of Easter and internet culture, we've added a few little easter eggs to the website 🙂

## How we Built It

Our team is composed of four 2nd year students who have a computer science background; except only in the languages of Python, C and R. None of us had any experience developing a website, so we had to be efficient, hopeful, and realistic.

*Backend:*  Everything was handled by Firebase; it provided us with hosting servers, the domain name, as well as Facebook/Google login authentication. We used Git as our version control.

*Frontend:* We mainly used react.js with material UI to develop the website. Figma was used for high-fidelity wireframing of advanced features for the future.

## Greatest Challenges & Proudest Moments

Our team all worked on varying aspects of the process - and so our greatest challenges and proudest moments all varied;

Jenn's greatest challenge was learning four languages on the go (HTML, JS, CSS, ReactJS), while also trying to implement meme buttons and exercise routines. She's most proud of how well we worked together as a team!

Much to his dismay, Rayman also had to learn these four languages, as well as typescript. His greatest nightmare was making the Pomodoro timer flip between 'work' and 'rest'. His greatest achievement was also, making the Pomodoro timer flip between 'work' and 'rest'.

Zi Lin, as McEgg's VP of design, was disgusted by the difficulties of alignment and beautifying the website in React (Figma was easier). He felt most accomplished when he got the react code working and started to merge our different codes together.

Kevin had issues with Firebase - unfortunately, website hosting had various issues from time to time, and so he was stuck debugging and wanting to break his slow computer. He's happiest with the Facebook implementation - Although it technically doesn't have any functionality, he thinks it looks beautiful. And he also loves the easter eggs.

## What's next for StudyFlow

Here are some of the other ideas we had for further features;

1. Facebook Poking - Using Facebook API so that clicking the 'Poke' button on our website would send a poke to the relevant friend, or even better, we could set up sessions within our website so that friends could join local lobbies and poke each other.
2. Website blocking - If our website acts as a google extension, it could block out other distracting tabs during the study sessions.
3. User Input to Customise Pomodoro Timer - To improve the timer, it could have extra functionality such as having custom inputs or alternate modes (instead of just the 25min/5min).