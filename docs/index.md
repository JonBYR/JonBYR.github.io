<video width = "1280" height = "720" controls loop = "">
  <source src = "https://github.com/JonBYR/JonBYR.github.io/raw/refs/heads/main/docs/assets/Portfoliovideofixed2.mp4">
</video>

# About Me
Hello, my name is Jonathan Byrne. I have recently finished my last year of my MComp Games Computing degree at the University of Lincoln and am interested in programming in C++, C#, Python and Java. I have experience using Github and am currently developing a game for the Playdate system. I also have experience using the game engines Unity and Unreal and have participated in game jams throught my studies at university. Below you will find some of the projects I have created, as well as the links to their repositories. For all of the repositories for all of my work, you can find them [here](https://github.com/JonBYR).

## QuadTree-2024
![The fully created QuadTree shown in SDL](/assets/QuadTree.png)

This was the creation of a QuadTree, which can be used in collision detection to reduce the number of collision calculations, by splitting the scene into seperate quadrants, meaning that the collision checks between particles only need to be checked between particles in each quadrant, rather than for all particles in the entire scene. This was visualized in SDL and converted from a tutorial using Javascript into C++ code. The repo is shown [here](https://github.com/JonBYR/QuadTree-For-Collisions).

## MComp Dissertation-2024
![A gif to show the MComp experimental game](/assets/MCompDiss.gif)

This was my MComp dissertation project, which involved creating two rhythm games, one as a control game that incorporates only tempo as a gameplay mechanic, and one experimental game that uses tempo, volume and key together, with key affecting colour and volume affecting enemy spawning by having more difficult enemies. The aim was to compare both games to see if the use of more musical features other than tempo could lead to more immersive rhythm games, with both rhythm games being inspired by the game Crypt of the NecroDancer. Furthermore, seperate python code was used to access Spotify's API to extract JSON files containing the song information required for the games. Going forward this game will be refined to have a better visual cue than the slider in the bottom right corner. The full dissertation can be read [here](/assets/MCompDiss.pdf) with the control repo shown [here](https://github.com/JonBYR/Year4ProjectControlGame) and the experimental repo is shown [here](https://github.com/JonBYR/Year4Project). 

## Superformula-2024
![Superformula with parameters 3, 4.5, 10 and 10](/assets/SuperformulaWeb.png)

This project was done in my fourth year and used C++ to generate complex shapes using polar coordinates that are generated from a formula devised by Johan Gielis, which can be described in more depth [here](https://en.wikipedia.org/wiki/Superformula). In order to display this formula, SDL was used to render the complex shapes created and involved converting from polar coordinates to SDL coordinates. I'd like to also implement threading in this project to try and reduce the compilation time to achieve more precise intervals of theta. [Repo](https://github.com/JonBYR/Superformula).

## Fractal Noise-2024
![Fractal Noise using SFML](/assets/Fractal.png)

This project was a creation of fractal noise, which is multiple octaves of perlin noise stacked upon one another. This was done in my fourth year of university to refresh myself on perlin noise while also learning how to create more refined noise by using fractal patterns. This was done in C++ using the SFML library to display the fractal noise as this was more suited than SDL to render the results. [Repo](https://github.com/JonBYR/Fractal-Noise).

## Mandelbrot Set-2024
![Mandelbrot Set](/assets/Mandelbrot.png)

This project was the implementation of the mandelbrot set in my fourth year, a series of finite complex numbers that do not converge to infinity via the formula Zn+1 = Zn^2 + C. When displayed on an argand diagram, it displays a fractal pattern as parts of the set look like smaller versions of the entire set. The complex numbers were done in C++ without the complex library to further understand how the set works and rendered in SDL. [Repo](https://github.com/JonBYR/MandelbrotSet).

## RGB Game Jam-2023
![Spelunky Type Game](/assets/RGB.gif)

This was a game created in Unity for a 24 hour game jam in my fourth year of university, with the theme of RGB. This was a solo project and aim was to better understand the algorithm behind the game Spelunky that caused the game to procedurally generate it's levels, which was successfully achieved during the course of the game jam. Going forward I'd like to improve the AI of the enemy. [Repo](https://github.com/JonBYR/RGB-Game-Jam).

## 8 Hour Game Jam-2023/2024
![8 Hour Game](/assets/Blondes.gif)

This was a game created in Unity in the fourth year of university and was another solo project. The main aim of this game was to understand how to change the post processing effects of Unity within a script and how users can input text into Unity. Players needed to try and guess a password to access a God mode cheat while also avoiding the blonde haired enemies. This project was then updated for the Arcadia Game Jam to work for the university Arcade machines using the SDK for these machines, as well as fixing various bugs. This game is now playable as a result on these uni machines. [Repo](https://github.com/JonBYR/8HourGameJam2023/tree/main).

## Year 3 Project-2023
![A gif of the project in action](/assets/Year3Video.gif)

This was my third year dissertation project, which involved looking at the most common shot sequences between different film genres and then mapping this common shot sequence into Unity, as a tool for those interested in film development to use to visualise what different shots would look like and to potentially suggest a shot sequence they could use for their own films, by extending the user interface of Unity itself. This is shown by adding a new tools tab with a section genre generation, which opens a new window allowing users to type a genre they would like to use, in this case a comedy sequence. Users can also move the camera in Unity if they wish to experiment with different shots. Note that this dissertation was made in Unity 2021.3.9f1. Issues were found running on later Unity versions. Going forward I would like to implement a machine learning model to generate the common shot sequence rather than a database system. The full dissertation can be downloaded [here](/assets/Year3ProjectPDF.pdf). [Repo](https://github.com/JonBYR/Year3Dissertation).

## Roots Game-2023
![A screenshot from the game made in a team](/assets/Tree.gif)

This was done during Global Game Jam 2023 in a two person team, which achieved second place in the university and was done in my third year of university. This game involved experimenting with procedural content generation with an algorithm I had developed myself. In this game I also created scripts for a visible timer, level loading, camera perspective, instantiating new objects, seperate gamemodes, high scores, generating sprites and a pause menu. [Repo](https://github.com/JonBYR/RootsGame/tree/main).

## Game Programming Assignment-2022
![A screenshot from the game programming assignment](/assets/Frog.gif)

This was a module in my second year of university to create our own game engine using C++ and SDL, as well as creating our own game within this game engine. This assignment helped to further understand the use of pointers and memory management within game development as well as the components required in a game engine. The game itself has a score that increases every second, however green frogs will double the current score, while red frogs set the score back to zero. [Repo](https://github.com/JonBYR/GameProgrammingAssignment).

## Roach Killer-2019
![Roach Killer](/assets/Roach.gif)

This was the first game jam that I participated in, which was in my first year of university. This was a 24 hour jam and was a solo project, but it helped me to understand the essential concepts in game development such as player and enemy movement as well as Quarternions and UI features such as menus. [Repo](https://github.com/JonBYR/Roach-Killer).
