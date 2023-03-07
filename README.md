# volumetric-shit-compressor
*Your shit is* apart, *and it's rather unbecoming of a cop and a human being. It's supposed to be the opposite of that: *together*. Compressed in a small area. To achieve a solid level of shit-compression, squeeze your butt-cheeks together for 30 minutes. Do something similar with the two hemispheres of your brain. Talk to people, maybe that will help.*

The Volumetric Shit Compressor is a participant system for larps

# CS
`.php` PSR-12

# Git flow
`main` is protected (ie only accepts merges from PRs. Work in branches, PR to `dev`. After merges to dev, bump `.version` (major, minor or patch), push to dev, make a `release/<version>` branch based on dev, PR to master.

- `feature/<desc>` for features
- `fix/<desc>` for bug fixes, typo corrections etc

# Todo for 0.1.0:
## API
### Userland
- [ ] Register a user to the system
  - [ ] Dupe checking
  - [ ] Validation
  - [ ] Email validation
  - [ ] SSO?
  - [ ] ReCaptcha (or variants?)
- [ ] Log in
  - [ ] Forgot password
  - [ ] 2FA?
  - [ ] SSO?
- [ ] Manual log out
- [ ] List events (ACL?)
- [ ] List my applications (and status)
- [ ] List application queues for events (ACL)
- [ ] "Apply" for an event
## Admin
- [ ] Create event
- [ ] Cancel event
  - [ ] Trigger notifications for already registered users?
- [ ] Edit event
- [ ] View applications
- [ ] Approve applied user
- [ ] Reject applied user
## Other
- [ ] Data model for content (ie "pages" and rich media etc)
- [ ] ACL model for content, actions and users
- [ ] Backend framework: Laravel, lumen, leaf, symfony, frameworkless?

