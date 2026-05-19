
# Lab 7 

kathy charry

### Expose 

1. **Within a GitHub Action that runs whenever code is pushed.** This automatically checks that the project still works every time new code is pushed. It ensures consistency as everyone's code is tested the same way before being pushed and saves times compared to manually running tests. It is also much more reliable than waiting until the end of development to test everything as mistakes are caught incrementally rather all at once at the end.

2. **No**. E2E tests are meant to test full user workflow and interaction, not individual functions. While you may be checking the outputs of various functions during E2E testing, it is not the main goal.

### Explore

1. Navigation mode analyzes the page while it loads and measures overall performance, while snapshot mode analyzes the page in its current state and mainly checks things like accessibility issues.
2. Three ways to improve the CSE 110 shop site based on Lighthouse:
    - Avoid chaining critical requests by reducing the length of chains, reducing the download size of resources, or   deferring the download of unnecessary resources to improve page load.
    - Improve accessibility by adding `[lang]` attribute to `<html>` element
    - Add a meta description to the document.
    