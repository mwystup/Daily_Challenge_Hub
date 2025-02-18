# :boom: Daily Challenge Hub - automated tests of the web application [Playwright] :boom:

I created simple automated tests for the Daily Challenge Hub website using Playwright. I built this website specifically for these tests.

The website includes:
- [Home Page](#home_page)
- [Fitness Challenge page](#fitness_challenge_page)
- [Mindfulness Challenge page](#mindfulness_challenge_page)
- [Reading Challenge page](#reading_challenge_page)

✔️ [all screenshots on Google Drive](https://drive.google.com/drive/folders/1sF15h14FHi5rGmTyuoLfKhBrkHLqovJh?usp=sharing)


I used Playwright Inspector (debugger) and Playwright UI Mode.
![Playwright Inspector](https://github.com/mwystup/Daily_Challenge_Hub/blob/images/playwright_inspector.png)

![Playwright UI Mode](https://github.com/mwystup/Daily_Challenge_Hub/blob/images/playwright_ui_mode.png)

I checked whether the tests were correctly written by, for example, changing the selector as shown below, which resulted in the test failing.
![Failed Tests_1](https://github.com/mwystup/Daily_Challenge_Hub/blob/images/failed_tests_1.png)

![Failed Tests_2](https://github.com/mwystup/Daily_Challenge_Hub/blob/images/failed_tests_2.png)

## :sparkles: Test scope:
- Checking the most important elements on pages - smoke tests.
- Checking the operation of buttons, links.

## :sparkles: Screenshots:

### <a id="home_page"> ✔ Homepage </a> [[🔼 scroll up 🔼](#top)]
This is the home page of the Daily Challenge Hub, created for these tests. The page is simple, with a few elements.
![Home Page](https://github.com/mwystup/Daily_Challenge_Hub/blob/images/home_page.png)

* Tests - <i> home_page_tests.spec.ts </i>
![Home Page Tests_1](https://github.com/mwystup/Daily_Challenge_Hub/blob/images/home_page_tests_1.png)
![Home Page Tests_2](https://github.com/mwystup/Daily_Challenge_Hub/blob/images/home_page_tests_2.png)

* Page - <i> home_page.ts </i>
![Home Page_1](https://github.com/mwystup/Daily_Challenge_Hub/blob/images/home_page_1.png)
![Home Page_2](https://github.com/mwystup/Daily_Challenge_Hub/blob/images/home_page_2.png)
_______________
### <a id="fitness_challenge_page"> ✔ Fitness Challenge Page </a> [[🔼 scroll up 🔼](#top)]
The page that we can access by clicking the "Fitness Challenge" option on the Home Page.
![Fitness Challenge Page](https://github.com/mwystup/Daily_Challenge_Hub/blob/images/fitness_page.png)

* Tests - <i> fitness_challenge_page_tests.spec.ts </i>
![Fitness Challenge Page Tests_1](https://github.com/mwystup/Daily_Challenge_Hub/blob/images/fitness_page_tests_1.png)

* Page - <i> fitness_challenge_page.ts </i>
![Fitness Challenge Page_1](https://github.com/mwystup/Daily_Challenge_Hub/blob/images/fitness_page_1.png)
_______________
### <a id="mindfulness_challenge_page"> ✔ Mindfulness Challenge Page </a> [[🔼 scroll up 🔼](#top)]
The page that we can access by clicking the "Mindfulness Challenge" option on the Home Page.
![Mindfulness Challenge Page](https://github.com/mwystup/Daily_Challenge_Hub/blob/images/mindfulness_page.png)

* Tests - <i> mindfulness_challenge_page_tests.spec.ts </i>
![Mindfulness Challenge Page Tests_1](https://github.com/mwystup/Daily_Challenge_Hub/blob/images/mindfulness_page_tests_1.png)

* Page - <i> mindfulness_challenge_page.ts </i>
![Mindfulness Challenge Page_1](https://github.com/mwystup/Daily_Challenge_Hub/blob/images/mindfulness_page_1.png)
_______________
### <a id="reading_challenge_page"> ✔ Reading Challenge Page </a> [[🔼 scroll up 🔼](#top)]
The page that we can access by clicking the "Reading Challenge" option on the Home Page.
![Reading Challenge Page](https://github.com/mwystup/Daily_Challenge_Hub/blob/images/reading_page.png)

* Tests - <i> reading_challenge_page_tests.spec.ts </i>
![Reading Challenge Page Tests_1](https://github.com/mwystup/Daily_Challenge_Hub/blob/images/reading_page_tests_1.png)

* Page - <i> reading_challenge_page.ts </i>
![Reading Challenge Page_1](https://github.com/mwystup/Daily_Challenge_Hub/blob/images/reading_page_1.png)
