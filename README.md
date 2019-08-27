
## Setting Up Your Linter

We use linter add-ons in our text editors to help us adhere to these style guides wherever possible. This guide is written assuming that Atom is the user's text editor because that is the common editor in our office.

### Atom Packages

#### Required Packages

- `linter-eslint` JavaScript linter. You may be prompted to install dependent packages as well.
- `linter-sass-lint` SCSS linter.
- `linter-php` PHP linter.

*Avoid using the auto fix features that come with the linters. They are inconsistent and often break your code before they fix your styles.*

`prettier-atom` is recommended, but not required. Prettier can settle most eslint errors relating to spacing with a single command.

### Node Modules

Run the following command inside the `suu-css` project:

```
npm install eslint gulp-eslint eslint-plugin-import eslint-restricted-globals sass-lint gulp-phplint
```
*TODO: This needs to be added to the setup process*

You may need to install peer dependencies if the linter is not working properly:

```
npm install -g install-peerdeps
```
