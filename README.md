Nutrition Label Component
This repository contains an HTML and CSS implementation of a nutrition label, styled according to the common format found on food products. The component is designed with responsive web design practices and a clean layout using basic CSS.

Project Overview
The goal of this project is to create a visually accurate and cleanly structured nutrition label using HTML and CSS. The label includes information like servings, calories, fats, proteins, vitamins, and other nutritional data, formatted to match standard food packaging labels.

Features
Structured layout: The HTML is structured with clear sections such as header, calories information, daily values, and a note at the bottom.
Stylized Dividers: The label uses multiple divider styles (large, medium, and small) to visually separate the sections.
Flexible Design: The label's container is styled to maintain consistent dimensions and margins, while remaining flexible to adjust to different screen sizes.
Custom Fonts: The project uses the 'Open Sans' font for a clean and professional look.
Responsive Layout: The design adjusts to various display sizes for better readability on different devices.
HTML Structure
The HTML file consists of:

A <header> that includes the title "Nutrition Facts", serving information, and serving size.
A section for calorie information.
A section for daily nutritional values, including fats, cholesterol, sodium, carbohydrates, and more.
A note explaining the percentage of daily values.
Key Elements:
.label: Main container that holds the entire nutrition label content.
.divider: Used to visually separate sections.
.bold: Applies bold styling to important text.
.calories-info: Contains the amount of calories per serving.
.daily-value: Contains the daily nutritional values, formatted with percentages.
CSS Styling
The CSS file defines the styling for the nutrition label. Key points include:

Responsive typography: Font sizes are relative to the base html size (16px).
Flexbox layout: Used in several places to align content, especially in the calorie section.
Custom styling for dividers: Different heights and background colors for .large, .medium, and .divider classes, to create distinct visual sections.
Indentation: The .indent and .double-indent classes are used to create nested list-like formatting for nutritional details such as fats and sugars.
Font scaling: The CSS uses scaling for the calorie text, making the number stand out prominently on the label.
<img width="454" alt="flexbox" src="https://github.com/user-attachments/assets/6618b75d-6988-4e4f-938b-b75a36b6bff6">

