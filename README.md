# iOS8 and iOS11 Demo Day

## Requirements

1. Fork and clone the repository
2. Create a pull request (PR) and tag your TL and instructor

**Add your:**

1. Slide deck (4 required slides in Keynote)
2. Add your links
3. Answer all the questions (Replace placeholders with your answers)
4. Video demo (2 minutes max), share YouTube video link

The video demo is for sharing your work on your portfolio, but it is also a fallback if you have a technical issue during demo time.

## Links (Add your links)

* Code: https://github.com/Go-Lyrics/SetMate
* Trello/Github Project Kanban: https://trello.com/b/ICehQPb8/setmate
* Test Flight: `<insert beta signup link here>`
* YouTube demo video: `<insert video url here>`

## Questions (Answer indented below)

1. What was your favorite feature to implement? Why?

    Marlon: PDFViewer & documentPicker, new and challenging
    Jeff: working with splitViews & the fetchedResultsController

2. What was your #1 obstacle or bug that you fixed? How did you fix it?

    Marlon: Working with splitViews, sending info from the master to detailed. Delegates/Protocols helped
    Jeff: same
  
3. Share a chunk of code (or file) you're proud of and explain why.

    Marlon: 
    Jeff: Used it to make the link between splitViews all over the app
        private func prepareDelegate() {
            let splitViewController = self.splitViewController
            let detailsVC = (splitViewController?.viewControllers.last as? UINavigationController)?.topViewController as? SetListDetailsVC
            delegate = detailsVC
        }
  
4. What is your elevator pitch? (30 second description your Grandma or a 5-year old would understand)
    
    For live musicians, setMate is your digital binder for storing all your music sheets and lyrics to be organized for live performances
  
5. What is your #1 feature?

    PDFViewer
  
6. What are you future goals?

    Release on the iPad store as a paid app, introduce iCloud, add filters for sets/songs, etc.....

## Required Slides (Add your Keynote to your PR)

1. App Name / Team Slide
2. Elevator Pitch
3. Your #1 Feature (Customer facing — what can I do with your app?)
4. Future Goals

## Slide Requirements

1. 50 pt font minimum
2. Be concise — don't write sentences/paragraphs (put these in your slide notes for speaking)
3. 3-6 bullets maximum per slide
4. Do the squint test (can you read the text if you squint, if so, make the font bigger)
6. Images are always welcome
7. Do the Grandma Test (Would your Grandma understand you?)

### Optional Slides

1. Blooper: What's a funny bug or blooper? (screenshots/GIFs please)
2. Revenue Model: If the app was your sole source of income, how would you monetize it?

## Presentation Format

**7 minutes/team**

* 4 minute presentation (5 minute hard cap)
* 3 minutes of questions

We have ~12 teams presenting today — please practice your presentation with a timer (as a team), and make sure you fit within the time limit.

Plan on having one person present the slides and live demo. Please practice your presentation in front of a mirror or with your team 2-5 times. Have the app running and visible in QuickTime so you can quickly transition between slides and live demo.

* App Name / Team Slide (30 seconds)
* Elevator Pitch Slide (30 seconds)
* Your #1 Feature (30 seconds)
* Live Demo (2 minutes)
* Future Goals (30 seconds)
* Questions (3 minutes)
