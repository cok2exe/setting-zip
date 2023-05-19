# eslint-zip

새 프로젝트 시작시 필요한 eslint, prettier 설정 파일 모음zip

React, Next 기준 필요한 packages

- eslint
- eslint-config-next
- eslint-config-prettier
- eslint-config-react
- eslint-config-react-app
- eslint-plugin-import
- eslint-plugin-jsx-a11y
- eslint-plugin-prettier
- eslint-plugin-react
- eslint-plugin-react-hooks
- eslint-plugin-sonarjs
- eslint-plugin-storybook
- eslint-plugin-unused-imports
- prettier

## with husky

husky와 함께 사용하면 커밋 전, 푸시할 때 등 제한을 둘 수 있음

- husky
- lint-staged

```json
"lint-staged": {
  "src/**/*.{tsx,ts,jsx,js}": [
    "eslint --fix",
    "prettier --write"
  ]
},
```