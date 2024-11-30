# 3D deployed websites of a user

This project is a 3D representation of deployed GitHub Pages websites using A-Frame and the GitHub API. Users can navigate through a virtual space, view previews of the websites, and click on them to open in a new tab.

## Features

- 3D environment built with A-Frame
- Fetches and displays GitHub Pages websites
- Interactive cubes representing each website
- Previews of websites displayed on planes
- WASD controls for movement and mouse for looking around
- Collision detection for realistic interactions

## How to Use

1. Clone the repository:# Disco Website 3D

This project is a 3D representation of deployed GitHub Pages websites using A-Frame and the GitHub API. Users can navigate through a virtual space, view previews of the websites, and click on them to open in a new tab.

## Features

- 3D environment built with A-Frame
- Fetches and displays GitHub Pages websites
- Interactive cubes representing each website
- Previews of websites displayed on planes
- WASD controls for movement and mouse for looking around
- Collision detection for realistic interactions(hasn't worked yet)

## How to Use

1. Clone the repository:
    ```sh
    git clone https://github.com/itsmehecker/disco_website_3d.git
    ```
2. Navigate to the project directory:
    ```sh
    cd disco_website_3d
    ```
3. Edit `index.html` in your code/text editor
    find const response = await fetch('https://api.github.com/users/itsmehecker/repos');
    replace itsmehecker for your own username
4.  Open `index.html` in your browser or host it on github pages 


## Controls

- **WASD keys**: Move around the scene
- **Mouse**: Look around
- **Click on a cube**: Open the corresponding website in a new tab

## Dependencies

- [A-Frame](https://aframe.io/releases/1.6.0/aframe.min.js)
- [A-Frame Physics System](https://cdn.rawgit.com/donmccurdy/aframe-physics-system/v3.3.0/dist/aframe-physics-system.min.js)

