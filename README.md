# Chinise Messages for React-Admin

English messages for [ra-language-chinese-new](https://github.com/GreatBoy/ra-language-chinese-new), the frontend framework for building admin applications on top of REST/GraphQL services.


## Installation

```sh
npm install --save ra-language-chinese-new
```

## Usage

```jsx
import { Admin } from 'react-admin';
import chineseMessages from 'ra-language-chinese-new';
import polyglotI18nProvider from 'ra-i18n-polyglot';

const messages = {
    'cn': chineseMessages,
};
const i18nProvider = polyglotI18nProvider(locale => messages[locale]);

<Admin locale="cn" i18nProvider={i18nProvider}>
    ...
</Admin>
```

## License

This translation is licensed under the MIT License, and sponsored by [marmelab](https://marmelab.com).
