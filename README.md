# trello-query

query `board`, `members`, `lists` and `cards` from a given board.

optionally filter by `since` and `until` date.

install via `npm i trello-query`

## usage

```js
  const { board, members, lists, cards } = await trelloQuery({ key, token, boardName: 'test' })
```