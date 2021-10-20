- [] Feature: Initial software landing page
  As a user, I want to see the homepage of the explorer with latest blocks and network information.

  - [] Scenario: First visit of the website
    Given a user opens the software
    When the user did not previously select data using the software.
    Then the homepage should be displayed and information read from the default node.

  - [] Scenario: Connected node was changed
    Given a user opens the software
    When the user previously changed the connected node on the software.
    Then the homepage should be displayed and information read from the changed node.

  - [] Scenario: Language was changed
    Given a user opens the software
    When the user previously changed the language of display on the software.
    Then the homepage should be displayed in the selected language.
