# React Task List

A React state-management exercise for adding and removing tasks. This is the `React2` snapshot.

## Run locally

Install Node.js and npm, then:

```sh
git clone https://github.com/CyberTekena/React2.git
cd React2
npm install
npm run start
```

Open the local URL printed by the development server.

## Implementation

[App.js](src/App.js) renders [TodoList.js](src/TodoList.js). The component uses `useState` for input text and the task array, then renders a delete control for each entry.

## Scope and limitations

Tasks are stored only in component state. There is no persistence or backend, and empty input is not explicitly rejected. The related REACT, NewReact, and React2 repositories preserve iterations of the same exercise.

## Next improvements

Add input validation, persistent storage, stable task identifiers, and task-focused interaction tests.
## Verification

Documentation was checked against the source and package scripts. Runtime behavior and deployment have not been certified by this documentation pass.

## Author

Tekena Ajuzieogu · [GitHub](https://github.com/CyberTekena)
