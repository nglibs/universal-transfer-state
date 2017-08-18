# Change Log
All notable changes to this project will be documented in this file.

## Current iteration
### Breaking changes
- **packaging:** merge public API into a single repository

## v0.4.0-beta.1 - 2017-04-28
### Breaking changes
- **packaging:** rename `@nglibs/universal-express-engine` to `@ngx-universal/express-engine`
- **packaging:** rename `@nglibs/universal-transfer-state` to `@ngx-universal/state-transfer` (closes [#5](https://github.com/fulls1z3/ngx-universal/issues/5))

### Bug fixes
- **express-engine:** add `yarn.lock` to npmignore
- **state-transfer:** add `yarn.lock` to npmignore (closes [#4](https://github.com/fulls1z3/ngx-universal/issues/4))
- **state-transfer:** cannot read property '0' of undefined (closes [#2](https://github.com/fulls1z3/ngx-universal/issues/2))

### Features
- **state-transfer:** add import/export STATE_ID (closes [#6](https://github.com/fulls1z3/ngx-universal/issues/6))
