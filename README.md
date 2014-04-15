# rspec-trello

Some integrations with trello in rspec

## TODO

- `pending` in card

    The idea is to create an additional param to set the card number for `pending` tests. Then, when I have a `pending` with the card setted, and the card was moved to done or somethig like this, the `pending` must raise an error. This way we can detect pendings without a card to fix them. 
