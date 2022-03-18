[Skip to main content](#Main)
[Back to previous page](#)

---

###### Menu
Main navigation
- [menu item](#)
- [menu item](#)
- [menu item](#)
- [menu item](#)

---

###### Tab Navigation
Secondary navigation
- [My Team](#)
- [My manager](#)
- [Others](#)

---

<a name="Main"></a>
###### Main 

# Check-ins with my team

You have a list of 5 people - sorted alphabetically:

[Sort chronologically](#)

- [Jenny Woon](#)
    - No events 
- [John Allen](#)
    - [upcoming tomorrow](#)
    - [5 action items](#) 
- [John Barry](#)
- [Paul Atherton](#)
- [Sylvia Park](#)

<label for="name">Name (4 to 8 characters):</label>

<input type="text" id="name" name="name" required minlength="4" maxlength="8" size="10">

- type: dropdown
    id: Level
    attributes:
      label: What kind of level is this tip?
      description: What level of developer do you tthink this tip is aimed at?
      options:
        - Beginner
        - Intermediate
        - Advanced
    validations:
      required: true
