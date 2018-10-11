# Workflow
  0. Each Task should be break into specific requierments.
    - scope
    - to_the_point_requierement_analysis
    - why do we need this change
    - what will this code affect
    - test cases to perform all the scenario
    - what Data Structures we will use.
    - writing the algorithms for each scenario
    - SOLID
    - Design Pattern
    - writing good documentation
    - PR Review

  1. CI
    ```
    const CI = ci => {
      automated_tests_ci();
      ci_should_perform_deployments();
      deployments_should_be_zero_downtime(); // autopilot
    };
    ```
  2. GIT
    ```
    const git = commit => {
      git-secret-pre-commit-hook();
      two_factor_authentication_for_all_employees();
      use_feature_branches_and_gitflow_as_branch_naming_scheme();
      good_commit_messages_must();
    }
    ```

# Project Setup
  1. Docker
  2. Initialization Checklist
    - LICENSE.md
    - README.md
    - CONTRIBUTING.md
    - CHANGES.md
    - `.gitignore`
    - Unit Test Setup
    - Linter Setup
    - Dependency Files - `requirements.txt`, `package.json`
    - `.env` file
    - Continuous Integration Setup (e.g. `jenkins`, `travis CI`, `circle CI`)
    - Visual Regression Setup (e.g. `Backstop`) [if any]
    - Integration Test Setup (e.g. `Selenium`, )
    - Language version (e.g. `.nvmrc`, `runtime.txt`, `Gemfile`)
    - Code Coverage (e.g. `code climate`)
    - Backend project files if creating a lib (e.g. `.gemspec`, `setup.py`)

  3. Project Management Tool
  4. Continuous Integration Service
