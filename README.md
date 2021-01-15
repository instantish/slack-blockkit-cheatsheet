# Slack Block Kit Cheatsheet
This is a cheatsheat for the [Block Kit API](https://api.slack.com/block-kit), great for referencing when wireframing out Slack interactions.

[_See the live syncing repo_ 🔁](https://github.com/instantish/slack-blockkit-cheatsheet).

## Values to know

### Surfaces

- [50 blocks per message](https://api.slack.com/reference/block-kit/blocks#:~:text=You%20can%20include%20up%20to,in%20modals%20or%20home%20tabs.)

- [100 blocks per modal or in the home tab](https://api.slack.com/reference/block-kit/blocks#:~:text=You%20can%20include%20up%20to,in%20modals%20or%20home%20tabs.)

### Blocks

- 5 elements in an Action Block

- 10 elements in a Context Block

- 150 characters in the `text` field of a Header Block

- 3000 characters in the `image_url` field of an Image Block

- 2000 characters in the `text` field of an Image Block

- 2000 characters in the `hint` field of an Input Block

- 3000 characters in the `text` field of an Section Block

- 10 `Fields` in the `fields` field of an Section Block

### Components

- 10 `Options` in the `options` field of a Checkbox Component

### Other

- 255 characters in a `block_id`
