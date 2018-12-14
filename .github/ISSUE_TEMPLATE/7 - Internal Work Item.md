---
name: Internal Work Item
about: For use by Project Maintainers Only
labels: Type - Maintenance
---

Acceptance Criteria
-------------------------------------------
Given: I am on a certain page

When: I click a button

Then: An action should occur



Keyboard Acceptance Criteria
-------------------------------------------
Given: I am navigating the site using only my keyboard

When: I tab to the button

Then: I should see the button highlighted on focus

And When: I press enter on a highlighted button
Then: An action should occur



Screenreader Acceptance Criteria
-------------------------------------------
Given: I am using a screenreader to navigate the site

When: I tab to the button

Then: I should hear the label of the button

And When: I press enter

Then: I should hear that an action has occurred


