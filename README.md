[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![pull][pull-requests-shield]][pull-requests-url]
[![Issues][issues-shield]][issues-url]
<a href=#><img src="/16.gif"></a>
<br>
<h1 align="center"> <strong> 🗺️Naviquest </strong> </h1> 
<h1 align="center"><a href="https://thowfeeksalim.github.io/naviquest/">Live Demo</a></h1>

<!-- PROJECT LOGO -->
<br />
<p align="center">

  <h3 align="center">Naviquest</h3>

  <p align="center">
    Navigate your world with ease with the Naviquest app by your side.
    <br />
    <a href="#about-the-project"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://thowfeeksalim.github.io/naviquest/">View Demo</a>
    ·
    <a href="https://github.com/thowfeeksalim/naviquest/issues">Report Bug</a>
    ·
    <a href="https://github.com/thowfeeksalim/naviquest/issues">Request Feature</a>
  </p>
</p>

<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgements">Acknowledgements</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->

## About The Project

<img src="/ss.png">

Naviquest is a vanilla JavaScript application that interacts with the Leaflet library and display Map. This app uses modern JavaScript tools, such as Webpack to bundle the modules, and Babel to convert ES6, ES7 and ES8 back to ES5. The user can add workouts for running and cycling and these are stored via local storage.

###   Details

1.  It defines two classes, Workout and its child classes Running and Cycling, to represent workout sessions.

2.  Workout has properties such as date, id, clicks, coords, distance, and duration.

3.  Running and Cycling classes inherit the properties and methods of Workout, and they also have their unique properties such as cadence for Running and elevationGain for Cycling.

4.  The code defines an App class to handle the entire application's functionality, including getting user's location, loading a map, handling user input, and saving and retrieving data from local storage.

5.  It uses the Leaflet library to render a map and allows users to click on the map to add a new workout session.

6.  The code validates user inputs before creating a new workout session and checks if they are all positive numbers.

### Built With

This app is built with pure vanilla JavaScript along with HTML and SCSS. It uses webpack as module bundler and NPM as package manager.

- [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [SCSS](https://sass-lang.com/)
- [JavaScript](https://developer.mozilla.org/en-US/docs/Web/javascript)
- [Webpack](https://webpack.js.org/)
- [NPM](https://www.npmjs.com/)

<!-- GETTING STARTED -->

## Getting Started

To get started with project just simply fork this repo or download locally on your System.

To get a local copy up and running follow these simple example steps.

### Prerequisites

-Have a pc running Linux, MacOS or Windows.

Start with the latest version of NPM to avoid any errors:

- npm
  ```sh
  npm install npm@latest -g
  ```

### Installation

1. Get Leaflet library [Leaflet](https://leafletjs.com/)
2. Clone the repo
   ```sh
   git clone https://github.com/thowfeeksalim_/naviquest.git
   ```
3. Install NPM packages
   ```sh
   npm install
   ```

<!-- USAGE EXAMPLES -->

## Usage

1. Add workouts near to your Geo location.

2. Add workouts to bookmarks to view it later.

3. Click on workouts to see it's location.

<!-- ROADMAP -->

## Roadmap

See the [open issues](https://github.com/thowfeeksalim/naviquest/issues) for a list of proposed features (and known issues).

### Proposed features

1. Ability to edit a workout.

2. Ability to delete a workout.

3. Ability to delete all workouts.

4. Ability to sort workouts by a certain field (e.g. distance).

5. Re-build Running and Cycling objects coming from Local Storage.

6. More realistic error and confirmation messages.

7. Ability to position the map to show all workouts.

8. Ability to draw lines and shapes instead of just points.

9. Geocode location from coordinates (“Run in Shoghi, Shimla).

10. Display weather data for workout time and place.


## Deployment

Deployed Website:  https://thowfeeksalim.github.io/naviquest/
<img src="/logo.png">


<!-- CONTRIBUTING -->

## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<!-- LICENSE -->


## License

![License](https://img.shields.io/badge/license-MIT%20License-blue.svg)
<p align="center">
This project is licensed under the MIT License.

Copyright (c) 2023 Thowfeek Salim

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.


## Author

👤 **Thowfeek Salim**

- GitHub: [@Thowfeeksalim](https://github.com/thowfeeksalim)
- Twitter: [@Thowfeeksalim06](https://twitter.com/thowfeeksalim6) 
- LinkedIn: [Thowfeeksalim](https://www.linkedin.com/in/thowfeek-salim-294760211) 

<!-- ACKNOWLEDGEMENTS -->

## Acknowledgements

- [Img Shields](https://shields.io)
- [Netlify](https://www.netlify.com/)
- [Webpack](https://webpack.js.org/)
- [Google Fonts](https://fonts.google.com/)

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[contributors-shield]: https://img.shields.io/github/contributors/thowfeeksalim/naviquest?color=green&style=for-the-badge
[contributors-url]: https://github.com/thowfeeksalim/naviquest/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/thowfeeksalim/naviquest?style=for-the-badge
[forks-url]: https://github.com/thowfeeksalim/naviquest/network/members
[pull-requests-shield]: https://img.shields.io/github/issues-pr/thowfeeksalim/naviquest?style=for-the-badge
[pull-requests-url]: https://github.com/thowfeeksalim/naviquest/pulls
[issues-shield]: https://img.shields.io/bitbucket/issues/thowfeeksalim/naviquest?style=for-the-badge
[issues-url]: https://github.com/thowfeeksalim/naviquest/issues
[license-shield]: https://img.shields.io/apm/l/vim-mode?label=LICENSE&style=for-the-badge
[license-url]: https://github.com/thowfeeksalim/naviquest/blob/master/LICENSE.txt
<img src="/ss.png">
