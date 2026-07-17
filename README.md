# secure-coding-preflight-rules
A reusable security checklist for coding assistants, IDE agents, classroom projects, and software-development workflows.

# Secure Coding Preflight Rules

A reusable set of security rules for coding assistants, IDE agents, classroom
projects, and software-development workflows.

These rules are designed to be applied before coding begins. They require the
developer or coding tool to inspect the relevant codebase, identify security
risks, document findings, follow secure implementation practices, and report
what was tested.

## Purpose

Fast development should not come at the cost of security.

This repository provides a practical pre-coding security checklist that helps
developers identify and prevent common problems involving:

- Authentication
- Authorization
- User input
- API endpoints
- Password storage
- Secrets and environment variables
- Database queries
- User-generated content
- File uploads
- Sessions and tokens
- Error handling
- Logging
- Third-party dependencies
- Deployment and production access

The rules are intended for educational projects, prototypes, demonstrations,
assignments, and production applications.

## How to Use

1. Open `SECURITY_RULES.md`.
2. Copy the rules into the instruction area of the coding tool.
3. Add the current development task at the bottom of the document.
4. Require the pre-coding review before any files are modified.
5. Review the reported findings and implementation plan.
6. Approve the proposed changes before continuing when the task affects
   sensitive systems or data.
7. Verify the final security report and test results.

## Example

Add the task below the rules:

```text
Current task:

Create a user registration and login system using Node.js and PostgreSQL.
Users must be able to register, sign in, sign out, and reset their passwords.
