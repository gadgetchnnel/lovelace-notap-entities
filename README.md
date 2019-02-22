# lovelace-notap-entities
A card similar to the built-in entities card, which doesn't display the more-info card when tapping an entity.
This can be useful if the more-info card may conflict with functionality of one of the entities (e.g. the entity has a hyperlink and clicking on it also displays the more-info card) or if you just want a cleaner look.

This also requires [card-tools](https://github.com/thomasloven/lovelace-card-tools) from thomasloven to be installed.

Using this is just like the built-in entities card:

    type: custom:notap-entities
    entities:
      - switch.television
      - light.bedroom_light
