# End-to-End AI PR Test

This document describes an end-to-end AI pull request test.

## Overview

The end-to-end AI PR test validates that the AI coding agent can successfully:

1. Understand a problem statement from a GitHub issue
2. Explore the repository structure
3. Make the required code or content changes
4. Commit the changes with the specified commit message
5. Open or update a pull request with the correct title and description

## Test Steps

1. **Trigger**: A new issue is created with a clear problem statement and instructions.
2. **Agent activation**: The AI coding agent is assigned to the issue and begins working.
3. **Repository exploration**: The agent explores the repository to understand the codebase.
4. **Implementation**: The agent makes the necessary changes (e.g., creating or modifying files).
5. **Validation**: The agent runs any relevant tests or linters to verify correctness.
6. **Commit & push**: The agent commits with the required message and pushes to the PR branch.
7. **Review**: A human reviewer checks the PR to confirm it meets all requirements.

## Success Criteria

- The PR is opened with the correct title.
- All required files are created or modified as specified.
- The commit message matches the required format.
- No unrelated files are changed.
