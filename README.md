# News Transition

This module aims to assist with content transitioning between states 'Sticky at top of list' and 'Promoted to front'.

## Use case
Consider you have a news website where you need to label a piece of content as 'Headline'. When you post another story which needs to be the 'Headline', what happens to the older one? 

Usually, that content would get filtered out or would need manual intervention to 'demote' the state in some way.

Rather than wasting time trying to locate the old one, why not have an automatic process which handles the state change. Enter *News Transition*.

## User guide

### Prerequisites

This module is designed to work with Drupal 9.4^ | 10^

### Configure Permissions
This module is really simple. When installed the only thing you need to do is configure the permissions to say who can use the module.

To change permissions, navigate to:
*admin/people/permissions/module/news_transitions*