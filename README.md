# iOS Demo Day

## Requirements

1. Fork and clone the repository
2. Create a branch for Unit1 or Unit4
3. Add your Team Name / Team Members and make a commit
4. Create a pull request (PR) and **tag your TL and Instructor**
5. **Add your presentation content**
    1. Slide deck (4 required slides)
    2. Links
    3. Answer all questions 
    4. YouTube demo video (1-2 min max)
6. Polish your Github Code repository
    1. Add screenshots and an overview to your GitHub Code Repository
    2. You should make that repository the "Public Portfolio" for your project
    3. Look at [John Sundell's Splash project](https://github.com/JohnSundell/Splash) for inspiration (code, images, GIFs)


## Links

* App Name: `<insert team name / app name>`
* Team: `<insert team members here>`
* Github Code: `<insert Github repository link here>`
* Github Proposal: `<insert Proposal Pull Request here>`
* Trello/Github Project Kanban: `<insert trello board here>`
* Test Flight Signup (Recommended): `<insert beta signup link here>`
* YouTube demo video (Recommended): `<insert video url here>`

## Hero Image

`<Post one screenshot in an iPhone Simulator frame or an iPhone 11 Pro render using placeit.com>`

## Questions (Answer indented below)

1. What was your favorite feature to implement? Why?

    `Mutliple Selection on a CollectionView was interesting because of the code paths that diffrent combinations open up for exploration.

2. What was your #1 obstacle or bug that you fixed? How did you fix it?

   Making coreData populate my views. Usually I use structs that I genereate along side coreData to update views and keep them both consistent in the background. Taking this new approach took more research and learning more about / relearning about FetchRequests, Predicates. 
  
3. Share a chunk of code (or file) you're proud of and explain why.

These functions belong to a feature in progress that will make selecting multiple categories for one entry seamless.

   //    func multipleCategories ()   {
//        let alert = UIAlertController(title: "Multiple Categories Selected: How much did you spend on \(chosenCategories[0])", message: "How much did you spend on your first selected category", preferredStyle: .alert)
//        alert.addAction(UIAlertAction(title:"Cancel", style: .cancel, handler: nil))
//
//        alert.addTextField { (textField) in
//            textField.placeholder = "\(self.chosenCategories[0])"
//
//        }
//
//        alert.addAction(UIAlertAction(title: "Enter Amount", style: .default, handler: { (action) in
//
//            if let amount = (alert.textFields?.first?.text) {
//                guard let doubleAmount = Double(amount) else {return}
//                self.knownAmountofFirstPurchase = doubleAmount
//            } else { print("Returning on line 75"); return}
//        }))
//        self.present(alert, animated: true, completion:nil)
//        print("Inside MultipleCategories knownAmounofFirstPurchase: \(knownAmountofFirstPurchase)")
//
//    }
//
//
//    func multipleCategoriesPartTwo(){
//        print("Inside MultipleCategoriesPartTwo knownAmounofFirstPurchase: \(knownAmountofFirstPurchase)")
//        entryController.createEntry(amountSpent: knownAmountofFirstPurchase ?? 2.22, category: chosenCategories[0], date: Date(), note: nil)
//
//        guard let purchase = (purchaseTextField.text) else { return }
//        guard let doublePurchase = Double(purchase) else {return}
//
//        let totalForSecondCategory =   divideTotalOfTwoCategories(total: doublePurchase, knownAmountOfOneCategory: knownAmountofFirstPurchase ?? 2.22)
//
//        entryController.createEntry(amountSpent: totalForSecondCategory, category: chosenCategories[1], date: Date(), note: nil)
//    }
  
4. What is your elevator pitch? (30 second description your Grandma or a 5-year old would understand)

   How many times have you tediously entered the details of a purchase into a checkbook, only to have to manually re-check them for errors later when balancing. This app solves that problem by making purchases easy to track with no learning curve for the software itself. 
  
5. What is your #1 feature?

    The ability to easily add custom categories. 
  
6. What are you future goals?

   Assign more than one category to a purchase and then do the math for the user so they have to enter the least information possible for maximum results. Partly implemented now. 

## Required Slides (Add your Keynote to your PR)

1. App Name / Team Slide
2. Elevator Pitch
3. Demo
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
* Elevator Pitch Slide (60 seconds)
* Live Demo (2 minutes)
* Future Goals (30 seconds)
* Questions (3 minutes)
