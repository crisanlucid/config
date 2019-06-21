# Config 

configuration files for Visual Studio Code<br>
https://github.com/crisanlucid/config/tree/feature/project-config/VScode

# Git - best practice for the team
https://github.com/crisanlucid/config/wiki/Git-Flow


# Trello - (Management Tool)
for a technical ticket insert *branche name from github*  in description


# Structure Directories for React (in progress...) 

modularize application

```
Module App

components
├── Modal
|    └── ...
└── App
     ├── Config.json
     ├── App.css       
     ├── App.js
```

# Class-based and Functional Component only (React)

**Filename**: Use PascalCase for filenames. `E.g., ReservationCard.js` <br>
you can prefix filename based on company name (optional `E.g. ZertifyButton`).<br>

links:<br>
PascalCase: [here](https://www.quora.com/What-is-the-difference-between-Pascal-Case-and-Camel-Case)

# CSS
user BEM convention
* https://seesparkbox.com/foundry/bem_by_example
* http://getbem.com/introduction/

Example BEM:
```
<form class="form form--theme-summer form--simple">
  <input class="form__input" type="text" name="email"/>
  <button
    class="form__submit form__submit--disabled"
    type="submit" >
    Submit
  </button>  
</form>
```

# GIT HOOKS
https://drive.google.com/file/d/1Ststqocl-B5CqgZSLCnC2l1gM5R0r6yl/view?usp=sharing
