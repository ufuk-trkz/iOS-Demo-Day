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

* Github Code: `<https://github.com/ufuk-trkz/BW-Unit4-orange-pages/compare?expand=1>`
* Github Proposal: `<insert Proposal Pull Request here>`
* Trello/Github Project Kanban: `<https://github.com/ufuk-trkz/BW-Unit4-orange-pages/projects/1>`
* Test Flight Signup (Recommended): `<insert beta signup link here>`
* YouTube demo video (Recommended): `<insert video url here>`

## Hero Image

`<Post one screenshot in an iPhone Simulator frame or an iPhone 11 Pro render using placeit.com>`

## Questions (Answer indented below)

1. What was your favorite feature to implement? Why?

`<Adding other users to the favorites. I wanted to learn about how users communicate with other users on the server.>`

2. What was your #1 obstacle or bug that you fixed? How did you fix it?

`<I was checking if the user is logged in on the SceneDelegate and if not the app should show the Login screen on the Login storyboard. That worked but it was presenting the view from the button. I changed from presenting the NavigationController to show(loginView).>`
  
3. Share a chunk of code (or file) you're proud of and explain why.

`< // 
func downloadImage(from urlString: String, completed: @escaping (UIImage?) -> Void) {
    guard let url = URL(string: urlString) else {
        completed(nil)
        return
    }
    let dataTask = URLSession.shared.dataTask(with: url) { data, response, error in
        guard  error == nil, let response = response as? HTTPURLResponse, response.statusCode == 200, let data = data, let image = UIImage(data: data) else {
                completed(nil)
                return
        }
        completed(image)
    }
    dataTask.resume()
}>`

`<If a user sets a profile image we are just saving the url of the image. to show the profileimage we have to download it using the url on the server.>`
  
4. What is your elevator pitch? (30 second description your Grandma or a 5-year old would understand)

`<The main function of the app is searching for other users and getting their contact information (Favorite restaurant, dentist, gym etc.). Every user can share their name (or business name), phone number, their email they are signed in with and a short info (e.g. opening hours) -> Business cards. The user can add the contacts they searched for to their favorites. >` 
  
5. What is your #1 feature?

`<Searching for other users>`
  
6. What are you future goals?

`<Deleting favorites>`
`<Adding a feed view for posts to make it like twitter.>`

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
