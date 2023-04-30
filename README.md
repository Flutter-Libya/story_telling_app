# Destini App Overview

<img src="Simulator%20Screen%20Shot%20-%20iPhone%2014%20Pro%20-%202023-05-01%20at%2000.08.04.png" alt="App Screenshot" width="200">

The Destini app is an interactive story app built using Flutter and Dart. The app features a story with multiple choices that lead to different story paths based on user decisions.

## Main Components

### MaterialApp

The MaterialApp widget sets up the app with a dark theme.

### StoryPage

This StatefulWidget represents the main screen of the app, containing the story text and choice buttons.

### Background Image

A background image is set as the decoration for the Container widget, providing a visually appealing backdrop for the story.

### Story Text

The story text is displayed in a Text widget with a font size of 25.0.

### Choice Buttons

There are two choice buttons in the app, with the text for each button being provided by the `getChoice1()` and `getChoice2()` methods from the StoryBrain class. The buttons have different background colors and font sizes.

#### Visibility

The second choice button's visibility is controlled by the `buttonShouldBeVisible()` method from the StoryBrain class. The button is hidden when it's not needed.

### StoryBrain Class

The StoryBrain class contains the logic for managing the story, choices, and navigation. It has a list of Story objects that represent the different story paths and choices.
