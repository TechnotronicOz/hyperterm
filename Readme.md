# hyperterm

## TODO

- [ ] Warn upon quit
- [ ] Implement memory for tab navigation like in Chrome
- [ ] Clone `pwd` when opening a new tab (as the first plugin?)
- [ ] Implement cmd+K to clear
- [ ] Listen on `resize` event *coming* from the pty.
- [ ] Make sure all popular shells work well, and that we detect
      "url commands" appropriately for them.
- [ ] Figure out process title extraction on other platforms.
- [ ] Define extensibility surface and APIs
- [ ] Define approach to conf management (`~/.hyperterm.json` ?)
- [ ] Admit Ctrl+C as a way of closing webview
- [ ] When webview is shown, replace title of tab with webview's title
- [ ] Linkify urls in stdout. If clicked, inline webview. If cmd+clicked, default browser.
- [ ] Show icon that triggers contextmenu in tab, when hovered.
  - [ ] "Open in default browser" option in webview mode
  - [ ] Close
- [ ] Test on Windows, Linux
- [ ] Investigate startup time improvements
  - [ ] Optimistic (mosh-style) prompt that memoizes PS1
  - [ ] Smaller bundle (ie: uglify, but currently doesnt work with ES6)
  - [ ] Inline all the CSS/JS in the page instead of extra file
