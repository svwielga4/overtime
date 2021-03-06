# Overtime App

### Key requirement: company needs documentation that salaried employees did or did not get overtime each week

## Models

- [x] Post -> date:date rationale:text
- [x] User -> Devise
- [x] AdminUser -> STI

## Features:

- [] Approval Workflow
- [] SMS Sending -> link to approval or overtime input
- [x] Administrate admin dashboard
- [x] Block non admin and guest users
- [] Email summary to managers for approval
- [] Needs to be documented if employee did not log overtime

## UI:

- [x] Bootstrap -> formatting
- [] Icons from font awesome
- [x] Update styles on the form

## Refactor TODOS:

- [x] Refactor user association in integration test in post_spec
- [] Add full name method for users
- [] Refactpr posts/\_form form admin user with status
- [] Fix post_spec.rb:82 to user factories
- [] Fix post_spec.rb:52 to have correct user reference and not require update
