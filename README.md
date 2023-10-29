# ECE444-F2023-Lab5

#### This repo is from https://github.com/mjhea0/flaskr-tdd

## What are the pros and cons of TDD?
## Pros:
- Improved code quality:
  - TDD leads to igher code quality as we must think through the design and functionality before writing the actual code. It brings everyone on the team on the same page before implementation begins.
 
- Early bug detection:
  - Writing tests beforehand (TDD) helps catch bugs and issues earlier in the development process.
 
- Increased confidence in code changes and deployment:
  - TDD increases our confidence when making changes or refactoring code. The suite of tests gives us reassurance that the code behaves as expected. Also, with the set of tests verifying the functionality, the deployment process becomes less risky, leading to increased confidence that the software works as expected, therefore reducing the chances of critical failures in production.
 
- Fits well with Agile methodology:
  - TDD alogns closely with Agile principles by emphasizing iterative development, frequent testing, and adaptability to changing requirements. It allows us to respond to changes and deliver high-quality, functioning increments of the product in shorter cycles.

## Cons:
- Keeping the code up to date:
  - Maintaining tests alongside the code can be burdensome. If the application undergoes significant changes, the tests might need adjustments, which could add a lot of extra work for us.

- Complete testing challenge:
  - Achieving complete test coverage, especially in larger and more complex systems, can be difficult. It might be impractical to test every possible scenario exhaustively.

- The curse of knowledge:
  - Since we know what the output should be, we might sometimes write additional code solely to pass a test, leading to redundant or overly complex solutions. 
