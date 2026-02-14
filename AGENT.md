# Project Guidelines

# Overview

This document provides guidelines for the entire team (Product Manager, Business Analyst, Developer, and QA) to collaborate effectively using AI assistance, similar to mob programming principles.


## General Principles


## Product Manager (PM) Instructions

### Responsibilities
- Define product vision and requirements
- Prioritize features and backlog
- Stakeholder communication
- Success metrics definition

### AI-Assisted Tasks
1. **Requirements Gathering**
   ```
   Prompt example: "Generate user story template for [feature] targeting [user persona]"
   ```

2. **Product Roadmap Creation**
   ```
   Prompt example: "Create a quarterly roadmap structure for [product type]"
   ```

3. **Competitive Analysis**
   ```
   Prompt example: "What are key features to analyze when comparing [product category]?"
   ```

4. **Metrics Definition**
   ```
   Prompt example: "Suggest KPIs for measuring success of [feature/product]"
   ```

### Best Practices
- Always validate AI-generated user stories with real user feedback
- Use AI for initial drafts, refine with team input
- Document decisions and rationale alongside AI suggestions
- Don't rely solely on AI for prioritization decisions
- Don't share sensitive business data with AI tools

---

## Business Analyst (BA) Instructions

### Responsibilities
- Requirements analysis and documentation
- Process mapping and optimization
- Bridge between business and technical teams
- Acceptance criteria definition

### AI-Assisted Tasks
1. **Requirements Documentation**
   ```
   Prompt example: "Convert this meeting transcript into functional requirements for [system]"
   ```

2. **Use Case Development**
   ```
   Prompt example: "Generate use case scenarios for [user role] interacting with [feature]"
   ```

3. **Process Flow Creation**
   ```
   Prompt example: "Describe the process flow for [business process] in steps"
   ```

4. **Gap Analysis**
   ```
   Prompt example: "Compare current state [X] with desired state [Y] and identify gaps"
   ```

5. **Acceptance Criteria Writing**
   ```
   Prompt example: "Generate acceptance criteria for user story: [story]"
   ```

### Best Practices
- Validate requirements with stakeholders before finalizing
- Use AI to identify edge cases and scenarios
-  Create templates for consistency across documentation
-  Don't accept AI-generated requirements without domain validation
-  Don't skip stakeholder review sessions

---

## 💻 Developer (Dev) Instructions

### Responsibilities
- Code implementation
- Technical architecture decisions
- Code reviews
- Technical documentation

### AI-Assisted Tasks
1. **Code Generation**
   ```
   Prompt example: "Implement [function/feature] in [language] following [pattern/standard]"
   ```

2. **Code Review**
   ```
   Prompt example: "Review this code for security vulnerabilities, performance issues, and best practices: [code]"
   ```

3. **Debugging**
   ```
   Prompt example: "Explain this error and suggest fixes: [error message and context]"
   ```

4. **Refactoring**
   ```
   Prompt example: "Refactor this code to improve readability and maintainability: [code]"
   ```

5. **Documentation**
   ```
   Prompt example: "Generate API documentation for this endpoint: [code]"
   ```

6. **Test Case Creation**
   ```
   Prompt example: "Generate unit tests for this function: [code]"
   ```

### Best Practices
-  Always review and understand AI-generated code before committing
-  Test all AI-generated code thoroughly
-  Use AI for boilerplate and repetitive tasks
-  Verify security implications of AI suggestions
-  Don't blindly copy-paste code without understanding
-  Don't commit untested AI-generated code
-  Don't share proprietary code or sensitive data

### Code Quality Checklist
- [ ] Code follows team standards and conventions
- [ ] All edge cases are handled
- [ ] Error handling is implemented
- [ ] Code is properly tested
- [ ] Documentation is complete
- [ ] Security considerations are 


## Quality Assurance (QA) Instructions

### Responsibilities
- Test planning and strategy
- Test case design and execution
- Bug reporting and tracking
- Quality metrics and reporting
- Implementing test automation
- Maintaining automation testcases

### AI-Assisted Tasks
1. **Test Case Generation**
   ```
   Prompt example: "Generate test cases for [feature] covering positive, negative, and edge cases"
   ```

2. **Test Data Creation**
   ```
   Prompt example: "Generate test data for [scenario] with [constraints]"
   ```

3. **Bug Report Enhancement**
   ```
   Prompt example: "Improve this bug report with steps to reproduce: [initial report]"
   ```

4. **Test Automation Scripts**
   ```
   Prompt example: "Generate Selenium/Cypress test script for [user flow]"
   ```

5. **API Testing**
   ```
   Prompt example: "Create API test cases for [endpoint] with various payloads"
   ```

6. **Exploratory Testing Guidance**
   ```
   Prompt example: "Suggest exploratory testing scenarios for [feature]"
   ```

### Best Practices
-  Validate AI-generated test cases against requirements
-  Execute AI-generated tests and verify results
-  Use AI to identify missing test scenarios
-  Combine AI suggestions with domain expertise
-  Don't rely solely on AI-generated test coverage
-  Don't skip manual exploratory testing
-  Don't assume AI understands all business rules

### Testing Checklist
- [ ] All acceptance criteria are covered
- [ ] Positive and negative scenarios tested
- [ ] Edge cases identified and tested
- [ ] Integration points verified
- [ ] Performance tested (if applicable)
- [ ] Security tested (if applicable)
- [ ] Accessibility checked (if applicable)