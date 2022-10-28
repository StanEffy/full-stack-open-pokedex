## Some common steps in a CI setup include linting, testing, and building. What are the specific tools for taking care of these steps in the ecosystem of the language you picked? You can search for the answers by google.

For linting I use eslint (tslint) with seven billions over plugins. Honestly speaking I am fine with prettier as I dont have any preferences for the code style if we speak about trailing commas, tabs vs spaces etc. But I guess it is important when you work with the team simply to distinct what is the difference between commits. As for tests it is usually jest, mocha, cypress and sometimes some additional libs like react-t-l, which is built on Jest. And for building we used mostly webpack/snowpack and some more efficient bundlers.



## What alternatives are there to set up the CI besides Jenkins and GitHub Actions? Again, you can ask google!


TeamCity.
Bamboo.
Buddy.
GitLab CI.
CircleCI.
TravisCI. And many others.

## Would this setup be better in a self-hosted or a cloud-based environment? Why? What information would you need to make that decision?

It depends on many factors. If you want to get your hands dirty - it is much better to do a self-hosted decision and dive as deep as possible to the depth of pain. But if you want to make it smooth and easy - youd better use cloud-based environment which is usually less customizable but more robust. 