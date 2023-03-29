# 100 Days Of Code - Log

### Day 19: Tuesday, March 28, 2023

**Today's Progress:** Realised that Discord has switched to an SDK for the rich presence instead of the RPC API, and now it's a lot more difficult to just make a Node app integrated with it. Oh well. Since I can't be spending too much time on that, Electron is on the backburner now, focusing on other stuff. Started making a "project details" page for my portfolio.

**Link to work:** [Dev branch of my portfolio](https://github.com/mai-soup/portfolio/tree/development)

### Day 18: Monday, March 27, 2023

**Today's Progress:** More work on Electron, more work on my portfolio (also got a custom domain name for it!). Got file opening to work in Mark.

**Link to work:** [Mark](https://github.com/mai-soup/mark)

### Day 17: Saturday, March 25, 2023

**Today's Progress:** Spent a few hours studying Electron (read: trying to figure out how to do the things my textbook wants me to do with the newest version of Electron). Finally got the "bookmarker" app to work, so now moving onto the markdown editor project.

**Thoughts:** Decided to call it Mark. Upon a quick search I couldn't find an editor that already exists with that name, though it might just be because of the overlap of search terms. Oh well. Hope it's alright for a practice project.

**Link to work:** [Mark](https://github.com/mai-soup/mark)

### Day 16: Friday, March 24, 2023

**Today's Progress:** Finished my portfolio site, added smooth scroll and made the hover effect darker red instead of blue. Overall very pleased, used the rest of the day to revamp my CV design (to not have much of a design since now I have a portfolio to show off) and study Electron as well as for my Azure exam.

**Thoughts:** As I figure out various tricks, CSS feels more and more intuitive.

**Link to work:** [Portfolio](https://portfolio-mai-soup.vercel.app/)

### Day 15: Thursday, March 23, 2023

**Today's Progress:** Made a bunch of progress on the revamped version of my own portfolio page! Figuring out form validation + manually sending POST requests in React.

**Thoughts:** I feel like one of the things I could do to really make it feel fun to scroll through is add tiny animations here and there. Trying to figure out what colour I want for button hover and form focus effect - I don't think I like the blue I'm using at the moment after all. Smoothing out jumps to the contacts section might be another thing to consider, as well as adding a hover effect for the social buttons. Will seek out some more inspiration regarding this and advice from people more experienced in design than I am.

**Link to work:** [Portfolio](https://portfolio-mai-soup.vercel.app/)

### Day 14: Wednesday, March 22, 2023

**Today's Progress:** Continued with Electron, spent a large portion of the day trying to understand why the sample code in _Electron in Action_ didn't work with the newest versions of the packages (and the sample code on GitHub didn't even launch). Managed to get it working by the end of the day, discovered that now you have to use `preload` scripts and `contextBridge` to access the Node API from inside an Electron renderer.

**Thoughts:** I really do wish that when textbook authors say they are committed to keeping the code up to date and they'll post errata in READMEs they.... would actually at least make a README in the repo. And keep the code up to date, instead of the first and last commit being 6 years ago. Oh well.

### Day 13: Tuesday, March 21, 2023

**Today's Progress:** Worked more on the single-page portfolio and fixed some issues with z-index, spacing. Did some design work for my own portfolio.

**Link to work:** [Single Page Developer Portfolio](https://single-page-developer-portfolio-jade.vercel.app/)

### Day 12: Monday, March 20, 2023

**Today's Progress:** Continued work on the single-page developer portfolio, started learning Electron in order to finally finish a small project that's been half-finished for a couple years now.

**Thoughts:** Learned a lot today, including about how the `hr` tag is now defined in semantic terms! I remember it being taught as a visual separator when I started learning HTML as a child, only learned of the difference while browsing MDN docs and asking for advice on Slack. Just goes to show that even for the things I thought I knew, I might still have to catch up with some changes.

**Link to work:** [Single Page Developer Portfolio](https://single-page-developer-portfolio-jade.vercel.app/)

### Days 10-11: Friday, March 17, and Saturday, March 18, 2023

**Today's Progress:** Read up on JavaScript, did a few quizzes, set up Neovim on my old ThinkPad so I can keep coding while on the go (which I will have to the next week).

**Thoughts:** Vim is actually a _lot_ less scary than vi, which I had tried before.

### Day 9: Thursday, March 16, 2023

**Today's Progress:** Finished the interactive rating component, looked over the next Frontend Mentor project I'll be doing, fixed the mobile `100vh` issue (my solution - using`dvh`, though from what I saw, using JavaScript to calculate the visible space is also a common option). Oh, also made those bash aliases I talked about yesterday and updated my dotfiles. Spent a bit more time on life admin stuff, so didn't get a massive amount of coding done.

**Thoughts:** Set up Figma on my machine and it looks scary but fun. Can't wait to use it more tomorrow.

**Link to work:** [Interactive Rating Component](https://interactive-rating-component-mai-soup.vercel.app/)

### Day 8: Wednesday, March 15, 2023

**Today's Progress:** Spent most of the day applying for jobs and revising my CV now that I am out of university to better reflect my achievements as a developer, not academic ones. Nevertheless, did a few hours of coding - signed up to Frontend Mentor, completed one challenge and started another.

**Thoughts:** Getting more comfortable with Tailwind. Some of the "shortened" class names still trip me up every time, e.g. how the `align-items` property corresponds to the `items-` classes, not `align-`, but I'm sure with more practice this problem will go away. Could make bash aliases for creating a new Vite project and installing Tailwind dependencies, since I'm going to be using those two a lot, so might as well save some typing.

**Link to work:** [QR Code Component](https://github.com/mai-soup/qr-code-component)

### Day 7: Tuesday, March 14, 2023

**Today's Progress:** Attempted to make the Hangman game's design responsive so the game is all visible on smaller screen sizes. Ran into a problem with the image refusing to shrink past its original size, spent a few hours trying to find a bug in my code, since with a `div` the flexbox worked properly. Turns out I hadn't exactly made a mistake in my code, I just wasn't aware of [a default setting in flexbox regarding minimum size](https://stackoverflow.com/a/36247448). I couldn't find this information initially because I was focused on the `img` element specifically and not on minimum size in flexbox in general.

**Thoughts:** Debugging is a lot more difficult without a more senior dev to ask for an opinion after hitting a wall doing it alone. I tried asking for help on a Discord community after a couple hours of fiddling around, but received no response - can't figure out why. Wish there was someone I could text directly when running into things like this, but oh well. Google and extra time spent will have to do for now.

**Link to work:** [Hangman](https://hangman-two-psi.vercel.app/)

### Day 6: Monday, March 13, 2023

**Today's Progress:** Implemented the base functionality for the Hangman app, added some styling. Need to ensure it's responsive, as well as add the option to play using keyboard input.

**Thoughts:** Had a weird bug where a change to a `Set` in state wouldn't cause the children to update until a hot reload? Fixed by using an array instead, but will have to look if it's intended or if I messed something up.

**Link to work:** [Hangman](https://hangman-two-psi.vercel.app/)

### Days 4-5: March 10-11, 2023

**Today's Progress**: Polish up the app, fix known bugs, all that's left is to address design problems in mobile (it's functional and responsive, but the logo looks a bit weird and the "copied" text appears somewhere offscreen.

**Thoughts:** React is actually a lot more fun to work with than I imagined it would be.

**Link to work:** [Colour Palette App](https://react-colour-picker.vercel.app)

### Day 3: March 9, 2023

**Today's Progress**: Pulled a 30-hour study session to finish the bootcamp, keep working on app.

**Thoughts:** Going to sleep now.

**Link to work:** [Colour Palette App](https://react-colour-picker.vercel.app)

### Days 1-2: March 7-8, 2023

**Today's Progress**: Keep going through the React bootcamp, work on colour palette app.

**Link to work:** [Colour Palette App](https://react-colour-picker.vercel.app)
