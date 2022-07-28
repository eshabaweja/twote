


<!-- PROJECT LOGO -->
<br />
<div align="center">

  <h3 align="center">Twote the Twitter bot</h3>

  <p align="center">
  Trying out Selenium to make a bot that posts a random quotation to Twitter if my internet speed is too slow.
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
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
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

Woke up yesterday feeling like hmmm I just HAVE to try Selenium, so here's something I made with it. 

Here's what it does:
* Check your if your internet speed is good enough
* If it's too slow, it gets a random quotation from [zenquotes](https://zenquotes.io/)
* It logs into the twitter account you saved in the .env file
* It Tweets the quotation and the quotee's name.

**Note**: The bot was supposed to Tweet a complaint but I replaced it with random quotations because I like them better.

<p align="right">(<a href="#top">back to top</a>)</p>

### Built With
 ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
 ![Selenium](https://img.shields.io/badge/-selenium-%43B02A?style=for-the-badge&logo=selenium&logoColor=white)
 ![Twitter](https://img.shields.io/badge/Twitter-%231DA1F2.svg?style=for-the-badge&logo=Twitter&logoColor=white)

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple example steps.

### Prerequisites
Click on the links to download and install prerequisites, and copy the code snippets into a terminal to check if installed.
* [python](https://www.python.org/downloads/)
    ```sh
    python --version
    ```
* [selenium](https://pypi.org/project/selenium/)
    ```sh
    pip install selenium
    ```
* drivers for your browser (I used Firefox)
<table>
<colgroup>
<col>
<col>
</colgroup>
<tbody>
<tr><td><strong>Chrome</strong>:</td>
<td><a href="https://chromedriver.chromium.org/downloads" rel="nofollow">https://chromedriver.chromium.org/downloads</a></td>
</tr>
<tr><td><strong>Edge</strong>:</td>
<td><a href="https://developer.microsoft.com/en-us/microsoft-edge/tools/webdriver/" rel="nofollow">https://developer.microsoft.com/en-us/microsoft-edge/tools/webdriver/</a></td>
</tr>
<tr><td><strong>Firefox</strong>:</td>
<td><a href="https://github.com/mozilla/geckodriver/releases" rel="nofollow">https://github.com/mozilla/geckodriver/releases</a></td>
</tr>
<tr><td><strong>Safari</strong>:</td>
<td><a href="https://webkit.org/blog/6900/webdriver-support-in-safari-10/" rel="nofollow">https://webkit.org/blog/6900/webdriver-support-in-safari-10/</a></td>
</tr>
</tbody>
</table>


### Installation

Follow these steps now:

1. Create your Twitter account at [https://twitter.com/](https://twitter.com/)
2. Clone the repo
   ```sh
   git clone https://github.com/eshabaweja/twote
   ```
3. Create a .env file inside the repo
   ```sh
   touch .env
   ```
4. Save the following in `.env`
   ```sh
    TWITTER_USERNAME = 'your_twitter_username'
    TWITTER_PASSWORD = 'your_twitter_password'
   ```
5. (Optionally) change the speeds to your need in `main.py`:
  ```python
  PROMISED_UP = your_up_speed
  PROMISED_DOWN = your_down_speed
  ```
<p align="right">(<a href="#top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage

I created this project as a learning experience for myself. The twitter API is obviously an easier alternative to post tweets. However, you may modify this project to scrape the data of your choice and tweet accordingly.

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


<!-- CONTACT -->
## Contact

Esha Baweja - [@eshcapist](https://twitter.com/eshcapist)

Twote: [https://github.com/eshabaweja/twote](https://github.com/eshabaweja/twote)

<p align="right">(<a href="#top">back to top</a>)</p>
