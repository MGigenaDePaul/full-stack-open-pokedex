The language I picked is Python.
When writing Unit Tests you have to test your code in two steps. 
For linting and style-checking it is used flake8 to respect the coding style of Python.
For unit testing python comes with a library called pytest. 

When Automating the Build we mean building by taking the raw source code and translate it into a format that computers can run directly.
Python is an interpreted language, so it's build revolves around test execution rather than compilation.
If we execute tests manually after every small change it becomes tedious, so the idea is to automate that process.
If you used a package or framework that doesn't come with Python, Python has to understand those things, so you have to store them in a file requirements.txt or a Pipfile. These are the dependencies of your code and are necessary for a succesful build.

An alternative to set up the CI besides jenkins and Github Actions is GitLab (a CI/CD tool).
Just like Jenkins, it is an open-source tool too. You can test your build in parallel, therefore it takes less timer. It allows docker integration and helps in automating release and application delivery. Also, it provides better support.

Other alternative is Bamboo. Some of the main features of Bamboo are that it can be used to run parallel batch tests and it provides seamless integration with JIRA, BitBucket, and Fisheye.

Finally, I believe it's better to work in a cloude-based environment rather than setting up a self-hosted environment. I think this because a team of 6 people is short and I would take this decision because the project has to be released soon. So insted of wasting time setting up our own environment, we just use a cloude-based environment.
