## Wireframe Child Components

### Signed Out Header

- My Stories
- About
- Signup/Login
- Avec-Vous

### Signed In Header

- My Stories
- Avec-Vous
- About
- Invites
- Profile

### About

- Intro
- Team
- Assorted Background Info

### Profile

- User Data Update
  - Username
  - Email
  - Password
  - Profile Pic

### Signup/Login

- Tabs for
  - Sign Up [default]
  - Log In

### Stories Page

- Tab to select
  - Stories In Progress [default]
  - Completed Stories
- sorted by recency

### My Stories Page

- Tab to select
  - My Turn [default]
  - All
  - Edited By Me
- sorted by recency

### A Story On A Page

- a truncated version of the story
  - from the end for in-progress stories
  - from the start for completed stories
- title if completed

### Story Details Page

- writers
- editor
- text
- title (if completed)
- whose turn it is
- if the story is the logged-in user's story
  - button to invite another user (if not a completed story)
  - button to mark story complete (if not a completed story)
  - sentence addition field (if user's turn)

### Invite A User

- text of story so far (from beginning)
- search box
- Search button
- "Search By" choices
  - username
  - email

### Invites

- List of invites
  - for incoming invites:
    - arrow in/mailbox icon/some other indicator
    - "from [username]" [with link to user]
    - "for [story title]" [with link to story]
    - buttons to accept/decline
      - when declined, incoming invite goes away
      - when accepted, button changes to link to story
  - for outgoing invites:
    - arrow out/sent mail icon/some other indicator
    - "to [username]" [with link to user]
    - "for [story title]" [with link to story]
    - button to cancel
      - when canceled, invite disappears

## User Stories

#### As a user, I want to:

- [ ] sign up
- [ ] log in
- [ ] view all stories
- [ ] view a particular story
- [ ] start a story

#### As a logged-in user, I want to:

- [ ] log out
- [ ] see my stories
- [ ] see which stories it's my turn in
- [ ] take a turn in an existing story
- [ ] invite a user to a story
- [ ] accept an invite to a story
- [ ] decline an invite to a story
- [ ] mark my story complete (no further sentences can be added)
- [ ] title a complete story
