<!--

Please use the content below as a template for your pull request.
Feel free to remove sections which do not make sense.

-->

## Scope

<!-- Brief description of WHAT you’re doing and WHY. -->

## Implementation

<!--

Some description of HOW you achieved it. Perhaps give a high level description of the program flow. Did you need to refactor something? What trade-offs did you take? Are there things in here which you’d particularly like people to pay close attention to?

-->

## Checks (development)

- [ ] Open API specs up to date
- [ ] All API handlers unit tested
- [ ] All processor methods unit tested
- [ ] Proxies contain no business logic
- [ ] Custom errors are caught in handlers
- [ ] API POST request formats are validated in handler using middleware
- [ ] Entitlements and principal for handlers are correct and are in `proxima.auth.access`
- [ ] Proper HTTP response codes are sent back in handlers

## How to test

<!--

A straightforward scenario of how to test your changes could help colleagues that are not familiar with the part of the code that you are changing but want to see it in action.

A "How To Test" section can look something like this:

- Sign in with a user with tracks
- Activate `show_awesome_cat_gifs` feature (add `?feature.show_awesome_cat_gifs=1` to your URL)

-->

## Entitlement Changes

<!-- List of entitlements being introduced or updated -->

## Cleanup Tasks (production deployments)

### All Production Deployments

- [ ] Feature branch(es) removed from repository
- [ ] AWS feature branch resoures removed (Cloud Formation stack for APIs, preview deploy for web apps)
- [ ] All tech debt added and labelled in Shortcut
- [ ] Documentation up to date
- [ ] Applies all [Serverless upgrades](https://docs.google.com/spreadsheets/d/11wLrZ_MK5maaTpUfn7olxZIxOS731FdFNUcwgVyX1s4/edit#gid=1604261873) in "Implement" stage

### Initial Production Deployments

- [ ] Branch protection rules implemented
- [ ] Repository configured in Swarmia
- [ ] Monitors and alerts configured on DataDog (future)

## Links

<!-- Links to Miro boards or Figma design -->
