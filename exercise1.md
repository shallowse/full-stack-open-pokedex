# Warming up

**Chosen language: Python**

## What are the specific tools for linting, testing and building?

**Linting**

A Google search for ```best python linter``` results in the following [Python Code Quality: Tools & Best Practices](https://realpython.com/python-code-quality/) web page. According to the web page some popular linters for Python include [Flake8](https://flake8.pycqa.org/en/latest/), [Pylint](https://www.pylint.org/) and many more.

**Testing**

A Google search for  ```best python testing framework``` results in the following [Top 6 BEST Python Testing Frameworks](https://www.softwaretestinghelp.com/python-testing-frameworks/) web page. According to the web page some popular test frameworks for Python include [Robot Framework](https://robotframework.org/), [pytest](https://docs.pytest.org/en/stable/) and many more.

**Building**

Packaging of Python projects for distribution is covered in various Tutorials found from [Python Packaging User Guide](https://packaging.python.org/)
  

## What alternative are there to Jenkins and GitHub Actions?

A Google serach for ```popular CI tools``` result in the following [20 Best Continuous Integration(CI) Tools in 2020](https://www.guru99.com/top-20-continuous-integration-tools.html), [Top 7 Best CI/CD Tools you should get your hands on in 2020](https://medium.com/devops-dudes/top-7-best-ci-cd-tools-you-should-get-your-hands-on-in-2020-832c29db936a) web pages. CI tools other than Jenkins or GitHub Actions include e.g. 
  - [GitLab](https://about.gitlab.com/)
  - [CircleCI](https://circleci.com/)
  - [Bamboo](https://www.atlassian.com/software/bamboo)
  - [Travis CI](https://travis-ci.org/)

Atlassian's web page has also a comparison of various [CI solutions](https://www.atlassian.com/continuous-delivery/continuous-integration/tools).

## Self-hosted or a cloud-based environment?

According to [Atlassian](https://www.atlassian.com/continuous-delivery/continuous-integration/tools) using on-premises CI tool means that one's team is responsible for configuring and managing the CI system. According to Atlassian this option can be beneficial for privacy and security reasons, and in addition on-premises instances may offer broaded customization and configuration options compared to Cloud based environments which are hosted by a third party vendor.

According to [Atlassian](https://www.atlassian.com/continuous-delivery/continuous-integration/tools) choosing to use Cloud based environments means to outsource the management of the CI tool to a third party vendor which handles uptime, support and scaling of the CI tool allowing one's team to focus only on core business needs.

So the answer for what environment is best for one's team is that it depends what the team's requirements for the CI tool are: What kind of competencies the team has for configuring and maintaining the chose CI tool? What kind of capacity the team has to allocate for maintaining the CI tool? etc.
