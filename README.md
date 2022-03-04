<div id="top"></div>

<!-- PROJECT LOGO -->
<br />
<div align="center">

  <h3 align="center">Midtrans Integration for flutter</h3>

  <p align="center">
   Integrate midtrans into flutter using REST API
   
  </p>
</div>

<!-- GETTING STARTED -->
## Getting Started

This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.

### Prerequisites

Make account in https://midtrans.com/, if you have already account, you can skip this step.
For getting started with midtrans you can see in https://api-docs.midtrans.com/, see at Getting Started and follow these instruction.

Get ApiKey for Authorization, you can see in https://api-docs.midtrans.com/#authorization/, if you have already apikey you can skip this step.


This is an example of how to list things you need to use the software and how to install them.
* pub
  ```sh
  not ready yet
  ```
* dependencies
  ```
  midtrans_integration::
    git:
      url: https://github.com/hendriks96/midtrans_integration.git
  ```

* or you can run with the specific branch in dependencies
  ```
  midtrans_integration::
    git:
      url: https://github.com/hendriks96/midtrans_integration.git
      ref: main # branch name
  ```
* import into your project
  ```
  import 'package:midtrans_integration/midtrans_integration.dart';
  ```

<!-- USAGE EXAMPLES -->
## Usage

Use this space to show useful examples of how a project can be used.
* Initialize
  ```
  MidtransIntegration midtransIntegration = MidtransIntegration();
  ```
* Set environment into PRODUCTION, if you dont call this function the default environment is set to SANDBOX

  ```
  midtransIntegration.setMidtransProduction(true);
  ```
* Set your apikey acces base64 encode from midtrans, and you have already to use this plugin

  ```
  midtransIntegration.setApiKeyAccess('change this with your base64 encode');
  ```

<p align="right">(<a href="#top">back to top</a>)</p>

<!--GET STATUS ORDER -->
## Get Status Order

Used this function to get status order.
* Set your apikey acces base64 encode from midtrans, and you have already to use this plugin

  ```
  await MidtransIntegration.getStatusOrder('your order id');
  ```

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=for-the-badge
[contributors-url]: https://github.com/othneildrew/Best-README-Template/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/othneildrew/Best-README-Template.svg?style=for-the-badge
[forks-url]: https://github.com/othneildrew/Best-README-Template/network/members
[stars-shield]: https://img.shields.io/github/stars/othneildrew/Best-README-Template.svg?style=for-the-badge
[stars-url]: https://github.com/othneildrew/Best-README-Template/stargazers
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=for-the-badge
[issues-url]: https://github.com/othneildrew/Best-README-Template/issues
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=for-the-badge
[license-url]: https://github.com/othneildrew/Best-README-Template/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/othneildrew
[product-screenshot]: images/screenshot.png
