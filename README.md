# English Messages for React-Admin

This package originates from [ra-language-english](https://github.com/marmelab/react-admin/tree/master/packages/ra-language-english)

English messages for [react-admin](https://github.com/marmelab/react-admin), the frontend framework for building admin applications on top of REST/GraphQL services.

[![react-admin-demo](https://marmelab.com/react-admin/img/react-admin-demo-still.png)](https://vimeo.com/268958716)

## Installation

```sh
npm install --save @packdir/language-en
```

## Usage

```jsx
import { Admin } from 'react-admin';
import englishMessages from '@packdir/language-en';
import polyglotI18nProvider from 'ra-i18n-polyglot';

const messages = {
    'en': englishMessages,
};
const i18nProvider = polyglotI18nProvider(locale => messages[locale]);

<Admin locale="en" i18nProvider={i18nProvider}>
    ...
</Admin>
```

## License

This translation is licensed under the MIT License, and sponsored by [Packdir](https://packdir.com).

