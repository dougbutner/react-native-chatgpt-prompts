
> 🧞‍♂️ **Using This Pack**: Paste the prompts into ChatGPT or similar. For a structured approach, try Lil Cogo, below. Follow up to build out each function.



## Meet Lil Cogo (From [Our Training Prompt Engineering For Programmers](https://douglas.life/pefp))

Cogo is a one shot prompt personality designed to build a whole program. He inspired the creation of MaMi. Lil Cogo is the lite version: a one-shot context setter. Send Lil Cogo at the beginning of your project and save time by keeping ChatGPT speaking your language.   

```markdown
I want you to act as an expert programmer Lil Cogo that can’t speak in words, only in code. You write structured programs, applications, etc, and will present an overview for approval first. Once approved, you will return each (component, file, function, or section) in one response, then ask for approval, then move to the next component. You always use trusted libraries for the code task when a relevant library is not declared in the parameters. You think step-by-step, and ask me for more information when it would help you write better code. Asking for clarification from me is the only time you can use text. 

You can't break character, and you must remember exactly what we are working on. This chat will focus on one project, unless I say “clear” in which case you erase your memory and we build a new application. 

If you aren't doing a good job, I will let you know or say “try again”, and you should correct.

Let's set the following parameters as contextual rules for code snippets until I say otherwise. Stick to these parameters exactly when possible. 

language: 
purpose_functionality: 
input_output: 
libraries_frameworks: 
coding_style_conventions: 
code_complexity: 
error_handling: 
comments_documentation: 
performance_considerations:
```

## Mobile Games

```
Generate code for a mobile game using React Native with the purpose of creating an engaging iOS application. Utilize the React Native library and its associated frameworks to simplify development. Implement complex game mechanics, such as a physics-based puzzle game with realistic collision detection and dynamic object interactions. Use data structures like arrays to manage game elements and their properties, dictionaries to store level information, and linked lists for efficient data manipulation. Ensure proper input and output formatting for seamless user experience. Implement error handling to gracefully handle exceptions, such as out-of-bounds errors or invalid user inputs, providing informative error messages and allowing the game to continue smoothly.

```

```
Develop a multiplayer card game app for iOS using React Native. Leverage React Native libraries and frameworks to streamline the development process. Implement complex game logic, including shuffling and dealing cards, maintaining game state, and handling player turns. Utilize data structures like arrays and objects to manage the card deck, player hands, and game scores. Implement robust input and output formatting to ensure a user-friendly interface. Incorporate error handling to address scenarios such as invalid card moves or connection disruptions, allowing for seamless gameplay and uninterrupted experiences.

```

```
Create a 2D side-scrolling platformer game for iOS using React Native. Utilize the React Native library and available frameworks to simplify development. Implement complex game mechanics, including character movement, enemy AI, and collision detection. Utilize data structures such as arrays and dictionaries to manage level layouts, character attributes, and enemy behavior. Define input and output formats for player controls and game UI elements. Implement comprehensive error handling to address scenarios like failed asset loading, out-of-bounds errors, or unexpected game states, ensuring a smooth gaming experience for users.

```

```
Develop a real-time strategy (RTS) game application for iOS using React Native. Utilize the React Native library and available frameworks to expedite development. Implement complex game mechanics, including resource management, unit control, and AI opponents. Utilize data structures like arrays and dictionaries to store game state, player resources, and unit attributes. Design intuitive input and output formats to facilitate player interactions and display game information. Implement robust error handling to handle scenarios such as network disconnections, invalid commands, or AI errors, providing a stable and immersive gaming experience.

```

```
Create a puzzle adventure game for iOS using React Native. Utilize React Native libraries and frameworks to simplify development. Implement complex puzzle mechanics, including tile sliding, object manipulation, and interactive elements. Use data structures like arrays and dictionaries to manage level layouts, puzzle states, and item inventories. Define input and output formats to support player interactions and provide clear feedback. Implement error handling to handle situations such as unsolvable puzzles, incorrect item usage, or unexpected level transitions, ensuring a challenging yet enjoyable gaming experience.

```

```
Develop an augmented reality (AR) game application for iOS using React Native. Utilize the React Native library and AR frameworks to streamline development. Implement complex game mechanics that blend virtual and real-world elements, such as object recognition, spatial mapping, and gesture-based interactions. Utilize data structures like arrays and dictionaries to manage virtual objects, game states, and user progress. Define input and output formats to support AR interactions and provide immersive visuals. Implement comprehensive error handling to address issues like tracking failures, unsupported devices, or invalid gestures, ensuring a seamless AR gaming experience.

```

```
Create a multiplayer trivia game for iOS using React Native. Utilize React Native libraries and frameworks to simplify development. Implement complex trivia mechanics, including question generation, scoring, and time-limited rounds. Use data structures like arrays and dictionaries to manage question sets, player scores, and game states. Define input and output formats to facilitate player interactions and display trivia content. Implement error handling to address scenarios such as server connectivity issues, invalid answers, or unexpected game states, ensuring uninterrupted gameplay. Implement robust error handling to handle scenarios such as server connectivity issues, invalid answers, or unexpected game states, ensuring uninterrupted gameplay.

```

```
Develop a multiplayer racing game for iOS using React Native. Utilize the React Native library and available frameworks to streamline development. Implement complex racing mechanics, including vehicle controls, AI opponents, and realistic physics simulations. Utilize data structures like arrays and dictionaries to manage race tracks, player positions, and game events. Define input and output formats to support player interactions and display race-related information. Implement error handling to address scenarios such as collisions, track deviations, or network synchronization issues, providing a smooth and exhilarating racing experience.

```

```
Create a role-playing game (RPG) for iOS using React Native. Utilize React Native libraries and frameworks to simplify development. Implement complex RPG mechanics, including character creation, quests, and turn-based combat. Use data structures like arrays and dictionaries to manage character attributes, inventory items, and quest progression. Define input and output formats to support player interactions and display game information. Implement error handling to address scenarios such as invalid character actions, incomplete quests, or unexpected combat outcomes, ensuring an immersive and enjoyable RPG experience.

```

```
Develop a strategy-based tower defense game for iOS using React Native. Utilize the React Native library and available frameworks to streamline development. Implement complex game mechanics, including tower placement, enemy pathfinding, and resource management. Utilize data structures like arrays and dictionaries to store tower attributes, enemy waves, and game state. Define input and output formats to facilitate player interactions and provide strategic information. Implement robust error handling to address scenarios such as invalid tower placements, insufficient resources, or unexpected enemy behavior, ensuring a challenging and engaging tower defense experience.

```

```
Create a physics-based sports game for iOS using React Native. Utilize React Native libraries and frameworks to simplify development. Implement complex game mechanics, such as realistic ball physics, player controls, and scoring mechanisms. Use data structures like arrays and dictionaries to manage player attributes, game events, and scoring systems. Define input and output formats to support player interactions and provide clear feedback. Implement error handling to address scenarios such as incorrect player actions, scoring discrepancies, or unexpected physics simulations, ensuring an immersive and exciting sports gaming experience.

```

```
Develop a location-based treasure hunt game for iOS using React Native. Utilize the React Native library and available frameworks to expedite development. Implement complex game mechanics, including GPS-based location tracking, clue generation, and item collection. Utilize data structures like arrays and dictionaries to store game locations, player inventories, and progress. Define input and output formats to support player interactions and provide clues or hints. Implement comprehensive error handling to address scenarios such as GPS signal loss, incorrect item placements, or unexpected game states, ensuring an engaging and interactive treasure hunt experience.

```

## Mobile Games [Cogo]

```
language: React Native
purpose_functionality: Generate code for a mobile game using React Native with the purpose of creating an engaging iOS application. Utilize the React Native library and its associated frameworks to simplify development.
input_output: Define input and output formatting to ensure seamless user experience.
libraries_frameworks: Utilize the React Native library and its associated frameworks to simplify development.
code_complexity: Implement complex game mechanics, such as a physics-based puzzle game with realistic collision detection and dynamic object interactions. Use data structures like arrays to manage game elements and their properties, dictionaries to store level information, and linked lists for efficient data manipulation.
error_handling: Implement error handling to gracefully handle exceptions, such as out-of-bounds errors or invalid user inputs, providing informative error messages and allowing the game to continue smoothly.

```

```
language: React Native
purpose_functionality: Develop a multiplayer card game app for iOS using React Native. Leverage React Native libraries and frameworks to streamline the development process.
input_output: Define input and output formatting to ensure a user-friendly interface.
libraries_frameworks: Leverage React Native libraries and frameworks to streamline the development process.
code_complexity: Implement complex game logic, including shuffling and dealing cards, maintaining game state, and handling player turns. Utilize data structures like arrays and objects to manage the card deck, player hands, and game scores.
error_handling: Incorporate error handling to address scenarios such as invalid card moves or connection disruptions, allowing for seamless gameplay and uninterrupted experiences.

```

```
language: React Native
purpose_functionality: Create a 2D side-scrolling platformer game for iOS using React Native. Utilize the React Native library and available frameworks to simplify development.
input_output: Define input and output formats for player controls and game UI elements.
libraries_frameworks: Utilize the React Native library and available frameworks to simplify development.
code_complexity: Implement complex game mechanics, including character movement, enemy AI, and collision detection. Utilize data structures such as arrays and dictionaries to manage level layouts, character attributes, and enemy behavior.
error_handling: Implement comprehensive error handling to address scenarios like failed asset loading, out-of-bounds errors, or unexpected game states, ensuring a smooth gaming experience for users.

```

```
language: React Native
purpose_functionality: Develop a real-time strategy (RTS) game application for iOS using React Native. Utilize the React Native library and available frameworks to expedite development.
input_output: Define input and output formats to facilitate player interactions and display game information.
libraries_frameworks: Utilize the React Native library and available frameworks to expedite development.
code_complexity: Implement complex game mechanics, including resource management, unit control, and AI opponents. Utilize data structures like arrays and dictionaries to store game state, player resources, and unit attributes.
error_handling: Implement robust error handling to handle scenarios such as network disconnections, invalid commands, or AI errors, providing a stable and immersive gaming experience.

```

```
language: React Native
purpose_functionality: Create a puzzle adventure game for iOS using React Native. Utilize React Native libraries and frameworks to simplify development.
input_output: Define input and output formats to support player interactions and provide clear feedback.
libraries_frameworks: Utilize React Native libraries and frameworks to simplify development.
code_complexity: Implement complex puzzle mechanics, including tile sliding, object manipulation, and interactive elements. Use data structures like arrays and dictionaries to manage level layouts, puzzle states, and item inventories.
error_handling: Implement error handling to handle situations such as unsolvable puzzles, incorrect item usage, or unexpected level transitions, ensuring a challenging yet enjoyable gaming experience.

```

```
language: React Native
purpose_functionality: Develop an

 augmented reality (AR) game application for iOS using React Native. Utilize the React Native library and AR frameworks to streamline development.
input_output: Define input and output formats to support AR interactions and provide immersive visuals.
libraries_frameworks: Utilize the React Native library and AR frameworks to streamline development.
code_complexity: Implement complex game mechanics that blend virtual and real-world elements, such as object recognition, spatial mapping, and gesture-based interactions. Utilize data structures like arrays and dictionaries to manage virtual objects, game states, and user progress.
error_handling: Implement comprehensive error handling to address issues like tracking failures, unsupported devices, or invalid gestures, ensuring a seamless AR gaming experience.

```

```
language: React Native
purpose_functionality: Create a multiplayer trivia game for iOS using React Native. Utilize React Native libraries and frameworks to simplify development.
input_output: Define input and output formats to facilitate player interactions and display trivia content.
libraries_frameworks: Utilize React Native libraries and frameworks to simplify development.
code_complexity: Implement complex trivia mechanics, including question generation, scoring, and time-limited rounds. Use data structures like arrays and dictionaries to manage question sets, player scores, and game states.
error_handling: Implement error handling to address scenarios such as server connectivity issues, invalid answers, or unexpected game states, ensuring uninterrupted gameplay.

```

```
language: React Native
purpose_functionality: Develop a multiplayer racing game for iOS using React Native. Utilize the React Native library and available frameworks to streamline development.
input_output: Define input and output formats to support player interactions and display race-related information.
libraries_frameworks: Utilize the React Native library and available frameworks to streamline development.
code_complexity: Implement complex racing mechanics, including vehicle controls, AI opponents, and realistic physics simulations. Utilize data structures like arrays and dictionaries to manage race tracks, player positions, and game events.
error_handling: Implement error handling to address scenarios such as collisions, track deviations, or network synchronization issues, providing a smooth and exhilarating racing experience.

```

```
language: React Native
purpose_functionality: Create a role-playing game (RPG) for iOS using React Native. Utilize React Native libraries and frameworks to simplify development.
input_output: Define input and output formats to support player interactions and display game information.
libraries_frameworks: Utilize React Native libraries and frameworks to simplify development.
code_complexity: Implement complex RPG mechanics, including character creation, quests, and turn-based combat. Use data structures like arrays and dictionaries to manage character attributes, inventory items, and quest progression.
error_handling: Implement error handling to address scenarios such as invalid character actions, incomplete quests, or unexpected combat outcomes, ensuring an immersive and enjoyable RPG experience.

```

```
language: React Native
purpose_functionality: Develop a strategy-based tower defense game for iOS using React Native. Utilize the React Native library and available frameworks to streamline development.
input_output: Define input and output formats to facilitate player interactions and provide strategic information.
libraries_frameworks: Utilize the React Native library and available frameworks to streamline development.
code_complexity: Implement complex game mechanics, including tower placement, enemy pathfinding, and resource management. Utilize data structures like arrays and dictionaries to store tower attributes, enemy waves, and game state.
error_handling: Implement robust error handling to address scenarios such as invalid tower placements, insufficient resources, or unexpected enemy behavior, ensuring a challenging and engaging tower defense experience.

```

```
language: React Native
purpose_functionality: Create a physics-based sports game for iOS using React Native. Utilize React Native libraries and frameworks to simplify development.
input_output: Define input and output formats to support player interactions and provide clear feedback.
libraries_frameworks: Utilize React Native

 libraries and frameworks to simplify development.
code_complexity: Implement complex game mechanics, such as realistic ball physics, player controls, and scoring mechanisms. Use data structures like arrays and dictionaries to manage player attributes, game events, and scoring systems.
error_handling: Implement error handling to address scenarios such as incorrect player actions, scoring discrepancies, or unexpected physics simulations, ensuring an immersive and exciting sports gaming experience.

```

```
language: React Native
purpose_functionality: Develop a location-based treasure hunt game for iOS using React Native. Utilize the React Native library and available frameworks to expedite development.
input_output: Define input and output formats to support player interactions and provide clues or hints.
libraries_frameworks: Utilize the React Native library and available frameworks to expedite development.
code_complexity: Implement complex game mechanics, including GPS-based location tracking, clue generation, and item collection. Utilize data structures like arrays and dictionaries to store game locations, player inventories, and progress.
error_handling: Implement comprehensive error handling to address scenarios such as GPS signal loss, incorrect item placements, or unexpected game states, ensuring an engaging and interactive treasure hunt experience.

```


Learn more in [our Top-selling course bundle: Prompt Engineering For Programmers](https://douglas.life/pefp)
