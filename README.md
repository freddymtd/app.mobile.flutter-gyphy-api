[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT Licence][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]

# Gyphy API - Flutter App

<p align="center">
<a href="#"><img src="https://developers.giphy.com/branch/master/static/header-logo-8974b8ae658f704a5b48a2d039b8ad93.gif"></a>
</p>
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">💻 About The Project</a>
      <ul>
        <li><a href="#packages">Packages we are using</a></li>
        <li><a href="#fonts">Fonts we are using</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">📓 Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#contributing">🚧 Contributing</a></li>
    <li><a href="#license">📝 License</a></li>
    <li><a href="#contact">📞 Contact</a></li>
  </ol>
</details>


## 💻 About The Project

<div style="text-align: center">
  <table>
    <tr>
      <td style="text-align: center">
        <a href="#"><img src="lib/assets/readme/screen1.gif"></a>
      </td>
      <td style="text-align: center">
        <a href="#"><img src="lib/assets/readme/screen2.gif"></a>
      </td>
      <td style="text-align: center">
        <a href="#"><img src="lib/assets/readme/screen3.gif"></a>
      </td>
    </tr>
  </table>
</div>

There are two pages, you can call it home page and details. On the home page, you can view a list of de most twenty trending gifs in the gyphy api. After that if on tap a gif model you will be taken to the details page. Lastly, at the bottom you got a botton if you click you will reload the state with twenty gifs.


### Packages

* [Material](https://api.flutter.dev/flutter/material/material-library.html)
* [Http](https://pub.dev/packages/http)

### Fonts

* [Fonts](https://api.flutter.dev/flutter/material/material-library.html)



<!-- GETTING STARTED -->
## 📓 Getting Started
This is an example of how you may give instructions on setting up your project locally. To get a local copy up and running follow these simple example steps.

### Prerequisites

First, you need get your API Key on [GIPHY Developers](https://developers.giphy.com/docs/sdk/) to run the project.

or use
- The public beta/test key is "dc6zaTOxFJmzC”

You need to set followings key-values in `lib/ui/home_page`.
The values are read at [here](https://github.com/yt-tkhs/superheroes/blob/master/shared/data/build.gradle.kts).

| Key | Value |
|:----|:------|
| `yourApiKey` | Public key for Gyphy API  |


Example:
```
yourApiKey = 'Enter your key';
```

### Installation

1. Get a free API Key at step prerequisites
2. Clone the repository
   ```sh
   git clone https://github.com/freddymtd/app.mobile.flutter-gyphy-api.git
   ```
3. Get the dependecies
   ```sh
   flutter pub get
   ```
4. Enter your API in `home_page.dart`
   ```JS
   const yourApiKey = 'Enter your key';
   ```
   



<!-- CONTRIBUTING -->
## 🚧 Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request


<!-- LICENSE -->
## 📝 License

Distributed under the MIT License. See `LICENSE` for more information.



<!-- CONTACT -->
## 📞 Contact

Freddy Zenteno - freddy-zenteno@hotmail.com

Project Link: [https://github.com/freddymtd/app.mobile.flutter-gyphy-api](https://github.com/freddymtd/app.mobile.flutter-gyphy-api)


<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[stars-shield]: https://img.shields.io/github/stars/freddymtd/app.mobile.flutter-gyphy-api.svg?style=for-the-badge
[stars-url]: https://github.com/freddymtd/app.mobile.flutter-gyphy-api/stargazers
[issues-shield]: https://img.shields.io/github/issues/freddymtd/app.mobile.flutter-gyphy-api.svg?style=for-the-badge
[issues-url]: https://github.com/freddymtd/app.mobile.flutter-gyphy-api/issues
[license-shield]: https://img.shields.io/github/license/freddymtd/app.mobile.flutter-gyphy-api.svg?style=for-the-badge
[license-url]: https://github.com/freddymtd/app.mobile.flutter-gyphy-api/blob/main/LICENSE
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/freddy-ramos-zenteno-816492181
