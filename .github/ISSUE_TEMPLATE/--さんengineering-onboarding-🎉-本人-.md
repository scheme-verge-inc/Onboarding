---
name: "○○さんEngineering Onboarding \U0001F389【本人】"
about: A welcome task for onboarding the offshore engineers
title: "○○さんEngineering Onboarding\U0001F389 Day1 【本人】"
labels: Onboarding実施
assignees: ''

---

Hi, Thank you for joining our team!
This is a list of welcome tasks for your onboarding.
Once you check all the subtasks, you can close this issue yourself :+1:
If you can't access any tool, please comment to this issue and change assignee to @khamida-schemeverge :bow:
If you have some questions about the workflow, repositories and etc., please comment to this issue with the detailed explanation of your problem and change assignee to @ttygtd :bow:

## How to use board & create issues
- [ ] Check this video about board & issue: https://drive.google.com/file/d/1Ref8KYMnLZ_5QH5EOuBb0oLB_6DLDpRQ/view?usp=drivesdk
- [ ] Please use #400_engineering_general channel on Slack
- [ ] Please avoid communicating via Slack DM except for some specific cases such as negotiating rates, private matters or problems related to the security issues.
If you have any other questions, please mention the relevant person in charge or let us know in the appropriate channel.
- [ ] Please check email every day to notice mentions and assignments on github
  - you can use Github app instead of email
  - you can use dashboard instead of email
- [ ] Did you move this issue to "In progress" column? 

To assistant role
- PR is pull request of source code. Engineers make PR to create or update our application. It's engineer's flow, so please mind just the word `PR`. ref: [What is pull request](https://www.google.com/search?q=what+is+pull+request)

Contents
- How to see our board.
- Filter of board.
- Top is higher priority and bottom is lower priority.
- When you start doing issue, move to "In progress" column.
- When you close the issue, not move to "Done", please click "Close Issue" .

Join
- [ ] figjam: https://www.figma.com/figjam/
  - scheme verge's white board  :bow:

## Access check
- [ ] [Can access GitHub projects](https://github.com/orgs/scheme-verge-inc/projects/4)
- [ ] Can access Repositories
  - [ ] [horai](https://github.com/scheme-verge-inc/horai)
  - [ ] [horai_os](https://github.com/scheme-verge-inc/horai_os)
  - [ ] [horai_flutter_new](https://github.com/scheme-verge-inc/horai_flutter_new)
  - [ ] [horai_ops](https://github.com/scheme-verge-inc/horai_ops)
  - [ ] [Setogei](https://github.com/scheme-verge-inc/setogei)
- [ ] [Can access slack ](https://horai-dev.slack.com/archives/CMG7JJKFZ)
- [ ] [Can access Google Drive 400.Eng ](https://drive.google.com/drive/folders/1bvNelIsAyKNs09briLMANjDJC0xUBjzc)
- [ ] [Can access firebase console](https://console.firebase.google.com/project/horai-dev-scheme-verge-v2/overview)
- [ ] [Can access google cloud platform](https://console.cloud.google.com/appengine/services?project=horai-dev-scheme-verge-v2)

##Member List 
- [ ] Please add your data to Member list
  - [ ] name
  - [ ] github
  - [ ] slack
  - [ ] email (We can use this email to invite meetings on google calendar)
- [ ] Please check email everyday because we'll send invitation to you for meeting on google calendar
- [ ] Please share your work shift for this week with the time in UTC.

Member list: https://docs.google.com/spreadsheets/d/1bDlVq19sW8RrztIGl-YxOcqNtIQEdcn7/edit#gid=269665135
- Leader
  - CEO & Designer: Tatsuki Yamanami
  - CFO: Kazuya Tanaka
  - BizDev: Eitaro Suda
  - Eng: Tatsuya Gotoda 

## Repository Structure
- horai_web
- horai_flutter_new
- horai_os
- horai
- DDD
- TDD
- Clean architecture
- Micro service architecture

## Workflow
https://console.cloud.google.com/sql/instances/api-services/overview?project=horai-dev-scheme-verge-v2
```
username:postgres
password: tsyzIhuBjJn6O7bb
```

Contents:
- milestones (we use milestones only for issues with a deadline :scream:)
- labels
  - question
  - only share
  - ops
  - team:*
  - we-are:winner (with milestone)
  - we-are:excellent-winner (with milestone)

- Daily workflow
  1. check "question" labeled issue(because someone needs your help)
  1. check "only share" labeled issue(because it's new information)
  1. check PR review(it's very important, so please review before you start your task)
  1. start resolving issue

- Workflow about issue
  1. Filter issues on board
  1. Move top issue to "In progress" from "To do" (to record the timestamp because we can know you start working)
  1. Commit changes with "Smart commit" commit message ex) `git commit -m'feat(api/coupon): add SampleUsecase / close #111' # close #issue_number is smart commit`
    - https://docs.github.com/en/github/managing-your-work-on-github/linking-a-pull-request-to-an-issue#closing-multiple-issues
  3. Create draft PR and assign yourself after first commit
  4. Move issue to "Waiting column" and put "Will close automatically by PR" label (because PR card and issue card both is in "In progress" column, it's noisy a little bit.)
  5. After resolve issue and pass CI check, please remove "Draft" mark from PR using "Ready for review" button. (to record you finish the task because we can know you finish working the task)
  6. Assign PR to reviewer (not only "reviewer" because we'll filter by assignee.)
  7. Move PR to "To do" (because the PR isn't "In progress"(means in reviewing) for reviewer just now);


- When you have question or problem
  1. Please comment to the issue
  1. Put "question" label
  1. change asignee
- When you have information to share, notice any problem or you face any troubles in the system 
  - please create an issue, (add "only share" label if you just want to share the info)
  - or contact us on slack :+1: (creating an issue must be fastest way to get the reply though)

## For Flutter only
- [ ] Check this video: https://drive.google.com/file/d/1S31fR7yDLjORr1fzWLxDJIYnCCsVfxXm/view?usp=drivesdk
- [ ] Research about clean architecture

Contents
- horai_flutter_new
- clean architecture
- CI
- horai/ui/admin

Horai app
- [ ] Setup horai_flutter_new development environment to local
- [ ] Run app locally
- [ ] Update README bow (maybe you'll face many trouble & error, please improve our document bow)

### Admin console
- [ ] Setup admin (in ui directory in horai repository) development environment to local
- [ ] Run app locally
- [ ] Update README bow (maybe you'll face many trouble & error, please improve our document bow)

## For Node Js only 

- [ ] Reserch now about clean architecture (maybe you need 2 or 3 hours for thus issue)

Contents
- horai_os
- horai
- clean architecture
- test
- CI
- coverage

horai_os
- [ ] Setup horai_os development environment to local
- [ ] Run test and pass all on your local machine
- [ ] Update README :bow: (maybe you'll face many trouble & error, please improve our document :bow:)

horai repository
- [ ] Setup coupon (it's in api directory in horai repository) development environment to local
- [ ] Run test and pass all on your local machine
- [ ] Check coverage
- [ ] Update README :bow: (in case you find troubles& errors, please improve our document :bow:)



You finished all welcome-tasks 🎉
Thank you!

- [ ]  Give us some feedback about those welcome tasks please 🙇
After comment to this issue, please change assignees to @ttygtdgs, 🙇
Next step: please check your board, maybe we assigned new issues to you.

Welcome to scheme verge!
