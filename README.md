- https://www.youtube.com/watch?v=ZXW6Jn6or1w

- `npx create-react-app --template=typescript react-eslint`
- `npm init @eslint/config`
- `npm i -D eslint-config-airbnb-typescript`
- add ```"jest": true``` in env of eslintrc.json and replace "extends" to this
    ```json
    "extends": [
    "react-app",
    "react-app/jest",
    "airbnb",
    "airbnb-typescript",
    "plugin:import/typescript"
    ],
    ```
