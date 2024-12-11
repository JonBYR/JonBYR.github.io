<video width = "1280" height = "720" controls loop = "">
  <source src = "https://github.com/JonBYR/JonBYR.github.io/raw/refs/heads/main/docs/assets/Portfoliovideofixed2.mp4">
</video>

# About Me
Hello, my name is Jonathan Byrne. I have recently completed the last year of my MComp Games Computing degree at the University of Lincoln. I am interested in programming in C++, C#, Python and Java. I have experience using Github and am currently developing a game for the Playdate system. I also have experience using the game engines Unity and Unreal and have participated in game jams during my studies at university. Below you will find some of the projects I have created, together with the links to their repositories. You can find the repositories for all my work [here](https://github.com/JonBYR).

## QuadTree-2024
![The fully created QuadTree shown in SDL](/assets/QuadTree.png)

This was the creation of a QuadTree, which can be used in collision detection to reduce the number of collision calculations by splitting the scene into seperate quadrants. This means that the collision checks between particles only need to be carried out in each quadrant rather than for the entire scene. I developed this Quadtree as I had been taught the theory and was curious to see how one would look in code. I decided to implement one to better understand how a Quadtree works in practice. This was visualized in SDL and converted into C++ code from a tutorial using Javascript. The repo is shown [here](https://github.com/JonBYR/QuadTree-For-Collisions).

## MComp Dissertation-2024
![A gif to show the MComp experimental game](/assets/MCompDiss.gif)

This was my MComp dissertation project, which involved creating two rhythm games, one as a control game incorporating only tempo as a gameplay mechanic and the other an experimental game that uses tempo, volume and key, with key affecting colour and louder songs spawning more difficult enemies. I particularly wanted to develop a rhythm game as it allowed me to link my interest in rhythm games with my interest in music. The aim was to compare both games to see if the use of musical features other than tempo could lead to a more immersive rhythm game experience. Both rhythm games were inspired by Crypt of the NecroDancer. Undertaking this dissertation allowed me to learn more about the game development process, such as how to compose a good game design document. I also learnt how to incorporate feedback from playtesting to enhance juiciness and game feel using features such as particle effects. Another skill learnt was how to use python code to access Spotify's API to extract JSON files containing song information required for the games. Based on player feedback this game will be further refined to include an improved visual cue other than the current slider found in the bottom right corner. The full dissertation can be read [here](/assets/MCompDiss.pdf) with the control repo shown [here](https://github.com/JonBYR/Year4ProjectControlGame) and the experimental repo is shown [here](https://github.com/JonBYR/Year4Project). 

## Superformula-2024
![Superformula with parameters 3, 4.5, 10 and 10](/assets/SuperformulaWeb.png)

This project uses C++ to generate complex shapes using polar coordinates, generated from a formula devised by Johan Gielis which is described in more depth [here](https://en.wikipedia.org/wiki/Superformula). I wanted to create this project due to my background in mathematics. Having learnt a new mathematical formula I was keen to try and implement a visual solution in code. In order to display this formula SDL was used to render the complex shapes created. This involved converting from polar coordinates to SDL coordinates, which was an interesting challenge as it required setting the polar coordinates into a cartesian form and then converting the cartesian form to SDL coordinates. Going forward I would like to implement threading in this project to try and reduce the compilation time and achieve more precise intervals of theta. [Repo](https://github.com/JonBYR/Superformula).

## Fractal Noise-2024
![Fractal Noise using SFML](/assets/Fractal.png)

This project was a creation of fractal noise, this being multiple iterations of perlin noise stacked upon one another. This was undertaken in order to refresh my knowledge on the theory behind perlin noise whilst also learning how to create more refined noise by using fractal patterns, with each iteration of perlin being further split into smaller cells. It was useful to revisit the concepts surrounding perlin noise such as frequency and amplitude which was achieved through online research. This was completed in C++ using the SFML library to display the fractal noise as I wanted to utilise a library other than SDL. [Repo](https://github.com/JonBYR/Fractal-Noise).

## Mandelbrot Set-2024
![Mandelbrot Set](/assets/Mandelbrot.png)

This project demonstrates the implementation of the mandelbrot set, a series of finite complex numbers that do not converge to infinity. This is achieved via the formula Zn+1 = Zn^2 + C. I undertook this project as I wished to learn more about fractals, a concept in procedural content generation. When displayed on an argand diagram, a fractal pattern is shown with parts of the set appearing as smaller versions of the entire set. The complex numbers were calculated in C++ and rendered with the SDL library. The real and imaginary components were manually calculated in the code and I particularly enjoyed determining how to calculate both compenents as this allowed me to further understand how the set operates. [Repo](https://github.com/JonBYR/MandelbrotSet).

## RGB Game Jam-2023
![Spelunky Type Game](/assets/RGB.gif)

This was a game with the theme of RGB created in Unity for a 24 hour game jam. It was a solo project with the aim of better understanding the algorithm behind the game Spelunky which causes the game to procedurally generate its levels, as I was interested in learning different methods of procedural content generation. This was done by following an online tutorial. It was initially difficult to understand the code but by rewriting the code line by line I began to understand the inner complexities of the algorithm and found this particularly rewarding. Going forward I'd like to improve the AI of the enemy by using a pathfinding algorithm such as A*. [Repo](https://github.com/JonBYR/RGB-Game-Jam).

## 8 Hour Game Jam-2023/2024
![8 Hour Game](/assets/Blondes.gif)

This was a game created in Unity and was another solo project. The main aims of this game were to understand how to change the post processing effects of Unity within a script and also to understand how users could input text into Unity during gameplay. The game objective was for players to try and guess a password to access a God mode cheat whilst also avoiding the enemies. This project was then adapted using an SDK package so that it would work on the university Arcade machines. The opportunity was also taken to erradicate various bugs. One example was, if a player picked up a tile and launched it at an enemy when in God mode, the tile would launch from a different position to the player. This was rectified by making the tile a child of the player. This game is now available to be played on the university arcade machines. [Repo](https://github.com/JonBYR/8HourGameJam2023/tree/main).

## Year 3 Project-2023
![A gif of the project in action](/assets/Year3Video.gif)

This was my third year dissertation project which involved looking at the most common shot sequences in different film genres and then importing this common shot sequence into Unity. The idea was for this to be a tool for those interested in film development, used to visualise how different shots would appear on screen, potentially suggesting a shot sequence that could be used for their own films. As I have a great interest in film, I was very keen to explore how games technologies could be incorporated into the film industry. The project required learning how to extend the user interface of Unity itself, shown by adding a new tools tab with a section genre generation, opening a new window to allow users to type the genre they would like to visualise. Users are also able to move the camera in Unity should they wish to experiment with different shots. This project also allowed me to learn and implement the software framework MVC (Model View Controller). Please note that this dissertation was made in Unity 2021.3.9f1 and issues have been discovered when running on later Unity versions. Going forward I would like to implement a machine learning model to generate the common shot sequence rather than utilising a database system. The full dissertation can be downloaded [here](/assets/Year3ProjectPDF.pdf). [Repo](https://github.com/JonBYR/Year3Dissertation).

## Roots Game-2023
![A screenshot from the game made in a team](/assets/Tree.gif)

This was created during Global Game Jam 2023 in a two person team, achieving second place in the university. This game involved experimenting with procedural content generation, which I was excited to do as I was keen to start learning more about this game design concept. This was achieved by implementing perlin noise to determine the type of biome based on values for height, moisture and heat. In this game I also created scripts for a visible timer, level loading, camera perspective, instantiating new objects, separate gamemodes, high scores, generating sprites and a pause menu. [Repo](https://github.com/JonBYR/RootsGame/tree/main).
