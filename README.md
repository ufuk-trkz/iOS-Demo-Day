# iOS Demo Day

## Requirements

1. Fork and clone the repository
2. **Add your presentation content**
    1. Slide deck (4 required slides)
    2. Links
    3. Answer all questions 
    4. YouTube demo video (1-2 min max)
3. Polish your Github Code repository
    1. Add screenshots and an overview to your GitHub Code Repository
    2. You should make that repository the "Public Portfolio" for your project
    3. Look at [John Sundell's Splash project](https://github.com/JohnSundell/Splash) for inspiration (code, images, GIFs)
4. Create a pull request (PR) and **tag your TL and Instructor**

## Links

* Github Code: `<https://github.com/ufuk-trkz/UnitConverter/blob/master/README.md>`
* Github Proposal: `<insert Proposal Pull Request here>`
* Trello/Github Project Kanban: `<https://trello.com/b/MLDbMhl0/unit-converter>`
* Test Flight Signup (Recommended): `<insert beta signup link here>`
* YouTube demo video (Recommended): `<insert video url here>`

## Hero Image

`<Post one screenshot in an iPhone Simulator frame or an iPhone 11 Pro render using placeit.com>`

## Questions (Answer indented below)

1. What was your favorite feature to implement? Why?

    `<The number buttons>`

2. What was your #1 obstacle or bug that you fixed? How did you fix it?

`<When I tried to change the title of the fromCurrency button it also changed the title of the toCurrency button. I fixed that by seperating the segue identifiers and creating two delegates.>`
  
3. Share a chunk of code (or file) you're proud of and explain why.

    `< @IBAction func numbersTapped(_ sender: UIButton) {
           
           if fromCurrencyTF.isEditing {
               fromCurrencyTF.text! += (String(sender.tag))
           } else if toCurrencyTF.isEditing {
               toCurrencyTF.text! += (String(sender.tag))
           }
       }>`

`< It isn't very complex but I did it by my own and found out that you can connect multiple buttons to one action.>`
  
4. What is your elevator pitch? (30 second description your Grandma or a 5-year old would understand)

    `< The App can be used to convert different kind of currencies, length units and weight units. It allows you to chage between the Unit Converters with a tab bar. You can select the currency you want to convert from and the currency you want to convert to and type in the amount into a text field using the number buttons on the screen. By tapping the equal button, the second text field shows the conveted amount. >`
  
5. What is your #1 feature?

`< Converting currencies, length and weight units.>`
  
6. What are you future goals?

`< Time-zone converter
Button to change fromUnit <-> toUnit
Allow basic calculation on text field (e.g. (100 + 50)USD = 134.55 EUR>`

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

Plan on having one person present the slides and live demo. Please practice your presentation in front of a mirror or with your team 2-5 times. Have the app running and visible (Simulator or QuickTime) so you can quickly transition between slides and live demo.

* App Name / Team Slide (30 seconds)
* Elevator Pitch Slide (30 seconds)
* Your #1 Feature (30 seconds)
* Live Demo (2 minutes)
* Future Goals (30 seconds)
* Questions (3 minutes)
