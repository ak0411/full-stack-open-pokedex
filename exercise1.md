# Exercise 11.1
_Think about a hypothetical situation where we have an application being worked on by a team of about 6 people. The application is in active development and will be released soon._

_Let us assume that the application is coded with some other language than JavaScript/TypeScript, e.g. in Python, Java, or Ruby. You can freely pick the language. This might even be a language you do not know much yourself. Answer or discuss some of the points below:_

#### Some common steps in a CI setup include linting, testing, and building. What are the specific tools for taking care of these steps in the ecosystem of the language you picked? You can search for the answers by google.
The application is coded in Python. For CI setup including linting, testing, and building. The team can use tools like Pylint, Flake8, and Mypy for linting. Testing can be done with pytest, an all-purpose testing framework, which means that it supports unit testing, functional testing, and more. As for the build tool, Python itself is an interpreted language, and for many simple projects, the team might not need an explicit build tool. However, as projects grow in size and complexity, incorporating a build tool can become beneficial, in that case, the team can explore using PyBuilder.

#### What alternatives are there to set up the CI besides Jenkins and GitHub Actions? Again, you can ask google!
An alternative to Jenkins and GitHub Actions, the team can use CircleCI, which supports both self- and cloud-hosted setups. According to Wikipedia, CircleCI is one of the world's most popular CI/CD platforms and has been utilized by large companies such as Facebook and Spotify in 2019.

#### Would this setup be better in a self-hosted or a cloud-based environment? Why? What information would you need to make that decision?
Choosing between self-hosted and cloud setups depends on the project. A team of 6 coding a small to medium project might prefer a cloud-based setup due to its ease of setup and cost-effectiveness, as there is no hardware or software infrastructure to maintain. In contrast, larger projects with increased resource needs might find a self-hosted setup more suitable for enhanced control and resource allocation, but it also means more technical work to set up.
