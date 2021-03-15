## [1.0.2](https://github.com/xops/openrpc-cli/compare/1.0.1...1.0.2) (2021-03-15)


### Bug Fixes

* add npm publishConfig ([365f5c1](https://github.com/xops/openrpc-cli/commit/365f5c1c4543d5bf4e618435c92e84a99f4444cc))

## [1.0.1](https://github.com/xops/openrpc-cli/compare/1.0.0...1.0.1) (2021-03-15)


### Bug Fixes

* tsconfig ([d2a5449](https://github.com/xops/openrpc-cli/commit/d2a5449d1604873dc6c89db61257ec3f17f869ef))

# 1.0.0 (2021-03-15)


### Bug Fixes

* don't print success message if outputting to stdout ([adbc72c](https://github.com/xops/openrpc-cli/commit/adbc72cab76b0bdb726ce7fb1eaff87fa37298da))
* don't use `process.exit` to exit program ([7d98a77](https://github.com/xops/openrpc-cli/commit/7d98a77312f1921375332a6ca1b5ef291727087c))
* linting ([3394f9e](https://github.com/xops/openrpc-cli/commit/3394f9ea47a07773a7144d05d340eed1c7d812d7))
* properly resolve URL on the 'inspect' command ([0b1f58f](https://github.com/xops/openrpc-cli/commit/0b1f58ff2d01671d2b9555b1709d9b9115afcd21))
* resolve file paths correctly ([0f8a3ef](https://github.com/xops/openrpc-cli/commit/0f8a3efdfc6a10940e759ee4163a77061cdbb199))
* resolve the output file path correctly ([41fa971](https://github.com/xops/openrpc-cli/commit/41fa97113bb099483c32e50c06d706af101629ae))
* update meta-schema + add circleci configs ([b9b47dd](https://github.com/xops/openrpc-cli/commit/b9b47dd76c64974d242f76de7bea34aa4c658c25))


### Features

* add OpenRPC parser ([864b1b7](https://github.com/xops/openrpc-cli/commit/864b1b75c9c526ebe44e8fc5e6d9351d10f4a2a1))
* add OpenRPC validator ([f1a1a36](https://github.com/xops/openrpc-cli/commit/f1a1a365d595f85f100741f5fcd00a4c3f1bfc6f))
* add support for bundling YAML files ([4954e89](https://github.com/xops/openrpc-cli/commit/4954e89d17178f45362467b212a293fe9bc2e7e7))
* add support for YAML when validating and inspecting ([80a6c0d](https://github.com/xops/openrpc-cli/commit/80a6c0dad820c6835083d8c316963825923fc88a))
* add the 'format' flag on 'bundle' ([4888e78](https://github.com/xops/openrpc-cli/commit/4888e78b92cdd603c9cc99f599fd5cb9d2245a47))
* add the 'substitute' flag on 'bundle' ([ceaeabe](https://github.com/xops/openrpc-cli/commit/ceaeabe63e7999d180478ffcbf37112c954d86ef))
* add the ability to repeat calling methods ([299e0e5](https://github.com/xops/openrpc-cli/commit/299e0e52584b7b90d0136066cc0f08d897377c82))
* add web socket support on the CLI inspector ([5b2292e](https://github.com/xops/openrpc-cli/commit/5b2292eafbc6162bd5c0a7425bb485bac2f18759))
* apply syntax highlighting on JSON RPC response ([88636e2](https://github.com/xops/openrpc-cli/commit/88636e2d04bf9904288f57f75c5dfa864c28812e))
* change output format based on output file extension ([9ffe3a6](https://github.com/xops/openrpc-cli/commit/9ffe3a653f40c9e2043ccddf4d749698878ddcf5))
* implement command line inspector ([b1a4a90](https://github.com/xops/openrpc-cli/commit/b1a4a90d1eb88f7621f766c9f4259cc83d599144))
* implement OpenRPC bundling ([afc5c0d](https://github.com/xops/openrpc-cli/commit/afc5c0d47fb0670a7472af17f5310ad33bdfaa15))
* implement OpenRPC validation ([f7da6ef](https://github.com/xops/openrpc-cli/commit/f7da6ef87c9eefa997f180298dedc1ae20bf5ffd))
* output styled strings ([b9c6038](https://github.com/xops/openrpc-cli/commit/b9c6038a73e5b44c277d17dfa8a0797863b63001))
* print to stdout if the 'output' flag is not provided ([ea2a9a3](https://github.com/xops/openrpc-cli/commit/ea2a9a37fb4632509ca46d37be8396a54eb6d924))
* use `console.table` to display validation errors ([3c95e42](https://github.com/xops/openrpc-cli/commit/3c95e422aace51641249ad5a31db7e1b0b55ba80))
* use a 'confirm' prompt when an output file already exists ([df9090c](https://github.com/xops/openrpc-cli/commit/df9090c5938eda35d65c0559ed3820adf80944e5))
