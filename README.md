# fluent-plugin-tail_path

## About

This is an extension of fluentd in\_tail plugin to add `path` field which tells the log path being tailed

## Parameters

Basically same with in\_tail plugin. See http://docs.fluentd.org/articles/in_tail

Following parameters are additionally available: 

- path_key

    Add `path` field which tells the log path being tailed. Specify the field name. 

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new [Pull Request](../../pull/new/master)

## ChangeLog

See [CHANGELOG.md](CHANGELOG.md) for details.

## Copyright

* Copyright (c) 2014- @szhem
* Copyright (c) 2014- Naotoshi Seo
* See [LICENSE](LICENSE) for details.