<div align="center" id="top"> 
  <img src="https://www.horoscope.com/images-US/signs/virgo.png" alt="Pyhoroscope" />

  &#xa0;

  <!-- <a href="https://pyhoroscope.netlify.app">Demo</a> -->
</div>

<h1 align="center">Pyhoroscope</h1>

<p align="center">
  <img alt="Github top language" src="https://img.shields.io/github/languages/top/fahad-programmer/pyhoroscope?color=56BEB8">

  <img alt="Github language count" src="https://img.shields.io/github/languages/count/fahad-programmer/pyhoroscope?color=56BEB8">

  <img alt="Repository size" src="https://img.shields.io/github/repo-size/fahad-programmer/pyhoroscope?color=56BEB8">

  <img alt="License" src="https://img.shields.io/github/license/fahad-programmer/pyhoroscope?color=56BEB8">

  <img alt="Github issues" src="https://img.shields.io/github/issues/fahad-programmer/pyhoroscope?color=56BEB8" />

  <img alt="Github forks" src="https://img.shields.io/github/forks/fahad-programmer/pyhoroscope?color=56BEB8" />

  <img alt="Github stars" src="https://img.shields.io/github/stars/fahad-programmer/pyhoroscope?color=56BEB8" />
</p>

<!-- Status -->

<!-- <h4 align="center"> 
	🚧  Pyhoroscope 🚀 Under construction...  🚧
</h4> 

<hr> -->

<p align="center">
  <a href="#dart-about">About</a> &#xa0; | &#xa0; 
  <a href="#sparkles-features">Features</a> &#xa0; | &#xa0;
  <a href="#rocket-technologies">Technologies</a> &#xa0; | &#xa0;
  <a href="#white_check_mark-requirements">Requirements</a> &#xa0; | &#xa0;
  <a href="#checkered_flag-starting">Starting</a> &#xa0; | &#xa0;
  <a href="#test_tube-how-to-use">How TO</a> &#xa0; | &#xa0;
  <a href="#hammer_and_wrench-functionalities">Functions</a> &#xa0; | &#xa0;
  <a href="#memo-license">License</a> &#xa0; | &#xa0;
  <a href="https://github.com/{{fahad-programmer}}" target="_blank">Author</a>
</p>

<br>

## :dart: About ##
This is a simple and lightweight module that you can use to get the horoscope reading for your
sign. The data is scraped from the horoscope.com site and code is optimized for performance.

## :sparkles: Features ##

:heavy_check_mark: Feature Get Daily, Weekly, Monthly And Yearly Horoscope Reading;\
:heavy_check_mark: Feature Get Love And Carrer Specific Readings;\
:heavy_check_mark: Feature Get What To Watch Recommendations Based On Your Sign ;

## Installing

Use the Following command in your terminal to install the module.
```bash
$ pip install PyHoroscope
```

# Contributions

## :rocket: Technologies ##

The following tools were used in this project:

- [Beautiful Soap](https://pypi.org/project/bs4/)
- [Python Request Module](https://github.com/psf/requests)
- [Python](https://python.org)

## :white_check_mark: Requirements ##

Before starting :checkered_flag:, you need to have [Python](https://python.org), [Beautiful Soap](https://pypi.org/project/bs4/) And [Python Request Module](https://github.com/psf/requests)  installed.

## :checkered_flag: Starting ##

```bash
# Clone this project
$ git clone https://github.com/fahad-programmer/pyhoroscope

# Access
$ cd pyhoroscope

# Install dependencies
$ pip install -r requirements.txt

# Run the project
$ python horoscope.py

```

## :test_tube: How To Use ##

```bash
# You Can Do This By Simple Importing The Module
$ from pyhoroscope.horoscope import Horoscope

# Then Create A Class Object Like This
$ horoscope = Horoscope("Name Of Sign")

# Then You Can Use The Following Functions

# Gets Daily Horoscope For The Sign
$ print(horoscope.daily_horoscope())

```

## :hammer_and_wrench: Functionalities

- Gets Tomorrow Horoscope For The Sign  
  ```python
  tomorrow_horoscope()
  ```

- Gets weekly Horoscope For The Sign  
  ```python
  weekly_horoscope()
  ```

- Gets The Daily Love Horoscope For The Sign  
  ```python
  daily_love()
  ```

- Gets The Tomorrow Love Horoscope For The Sign  
  ```python
  love_tomorrow()
  ```

- Gets The Weekly Love Horoscope For The Sign  
  ```python
  love_weekly()
  ```

- Get's Daily Carrer Horoscope For The Sign  
  ```python
  daily_carrer()
  ```

- Get's tomorrow Carrer Horoscope For The Sign  
  ```python
  tomorrow_carrer()
  ```

- Get's weekly Carrer Horoscope For The Sign  
  ```python
  weekly_carrer()
  ```


## :memo: License ##

This project is under license from MIT. For more details, see the [LICENSE](LICENSE.md) file.


Made with :heart: by <a href="https://github.com/fahad-programmer" target="_blank">Fahad Malik</a>

&#xa0;

<a href="#top">Back to top</a>
