# 🎭 Meme Picker

A fun meme picker project built with vanilla JavaScript! This project allows users to select an emotion and get a matching cat meme. I learned how to build this from Scrimba, and this README explains everything about the project. 🎉


## 🚀 Features
- Select an emotion from a set of radio buttons 🎭
- Choose whether to display only GIFs 🎞️
- Click a button to generate a meme 🐱
- Get a random meme if multiple match the criteria 🎲
- A modal popup to display the selected meme 🖼️


## 🏗️ How It Works

### 📌 Setting Up Event Listeners
- `highlightCheckedOption(e)`: Highlights the selected emotion.
- `closeModal()`: Closes the modal when the close button is clicked.
- `renderCat()`: Displays a meme based on user selection.

### 🔍 Filtering the Data
- `getSingleCatObject()`: Retrieves a single cat meme from the filtered data.
- `getMatchingCatsArray()`: Filters the available memes based on the selected emotion and GIF preference.

### 📡 Generating the Emotion Options
- `getEmotionsArray(cats)`: Extracts unique emotions from the dataset.
- `renderEmotionsRadios(cats)`: Dynamically creates radio buttons for emotions.

### 🖼️ Displaying the Meme
- Once an emotion is selected and the button is clicked, an image is displayed inside a modal.


## 🛠️ Technologies Used
- JavaScript (ES6+)
- HTML & CSS


## 🎓 What I Learned
- Manipulating the DOM dynamically with JavaScript.
- Handling user interactions with event listeners.
- Filtering data from an array based on multiple conditions.
- Using modals to display content dynamically.


## 🎖️ Acknowledgements
A huge shout-out to **Scrimba** for their amazing learning platform! 🏆 This project was a great way to practice JavaScript fundamentals while having fun. 🚀



