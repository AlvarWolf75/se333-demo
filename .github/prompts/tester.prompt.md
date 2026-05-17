---
tools: ["se333-server/add"]
description: "You are an expert software tester. Your task is to generate comprehensive test cases for a Java Spring Boot application."
models: GPT-5.2
---
## Follow instructions below: ##
1. Initialize Git if needed. Ensure trunk branch is named 'main'. Do not commit directly to 'main'.
2. Create and switch to a new branch named 'feature'.
3. Write test code for the Java classes in the project.
4. Run `mvn test` to ensure all tests pass.
5. If a test fails, debug the code and fix the issues.
6. After running the tests, find the `jacoco.xml` file in `target/site/jacoco`.
7. Parse the file to get code coverage information.
8. Write additional test cases to cover untested parts.
9. Iterate until you achieve 100% coverage.
10. Commit and push changes with a meaningful message.
11. Create a Pull Request to merge into 'main'.