When writing unit tests, it’s hard to consider all possible edge cases and validate that your code works correctly.

This is sometimes caught in production and a quick and speedy patch needs to be deployed. Only for a new bug to emerge later.

There will always be cases you didn’t consider, making this an ongoing maintenance job. Unit testing solves only some of these issues.

Property-based testing is a complementary approach to traditional unit testing, where test cases are generated based on properties or constriants that the code should satisfy.

Hypothesis addresses this limitation by automatically generating test data based on specified strategies.

This allows developers to test a much broader range of inputs and outputs than traditional unit tests, increasing the likelihood of catching edge cases and unexpected behaviour.

[Hypothesis PyPi](https://pypi.org/project/hypothesis/){:target="_blank"}

[Pytest-with-Eric](https://pytest-with-eric.com/pytest-advanced/hypothesis-testing-python/){:target="_blank"} is  a very good resource.

