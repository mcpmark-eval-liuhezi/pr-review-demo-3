# Reviewer Guide

A one-pager for anyone asked to review a pull request in this repo.

## How to approach a review

- Read the PR description first, then the diff, before looking at any comments — you want your own read on the change before absorbing other people's.
- Review the change, not the person. Keep comments about the code and about specific lines, and phrase requests as questions where you can.
- Prioritise feedback: block on correctness and security, suggest on style, and let the small stuff go unless the team has agreed otherwise.
- Give context, not just verdicts — "this loop can be O(n^2) if the list is large" is more useful than "this is slow".
- Check that the checklist in `docs/review-checklist.md` was actually followed before approving.

## What to do with your review

- Approve when you would be comfortable maintaining the code yourself.
- Request changes when something must be fixed before merge — and say what those somethings are.
- Comment when you have non-blocking thoughts you still want on the record.

Happy reviewing!
