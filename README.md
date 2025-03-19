# tl;dr: Travel Info

A dump of concise and organized information for urban survival. Focus on food, shelter, transportation, and staying out of jail.

Not a source of mainstream tourist attractions, but a more sober companion for [Tripadvisor](https://www.tripadvisor.com/).

Production instance: <https://tldrtravel.info>

## Content Policy

- No ads.
- No affiliate links.
- No sponsored content.
- Strive for [accessibility for neurodivergent](https://www.wypartnership.co.uk/application/files/3716/4735/6437/making-information-accessible-for-neurodivergent-people-final-v2-20.04.21.pdf).
- External links should be deep as much as possible.
- External links should lead to english version if available.

## Design Policy

- Accessibility and Readability are the highest priority.
- Formatting should be simple, functional and [responsive](https://www.w3schools.com/css/css_rwd_intro.asp).
- Website must perform well on older mobile devices over slow and unreliable internet connection.
- Do not interfere with any ways of copying and saving content for offline use.

## Development environment tips

- Don't forget to update git submodules: `git submodule update --init`
- Make sure to install _extended_ build of Hugo: gohugoio/hugoDocs#1152
- Use bind parameter to test on mobile devices: `hugo server --bind 0.0.0.0`
  - `Ctrl+Shift+B` in VSCode will run this command
