# go-xerial-snappy

[![Build Status](https://travis-ci.org/eapache/go-xerial-snappy.svg?branch=master)](https://travis-ci.org/eapache/go-xerial-snappy)
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Fcanv15%2Fgo-xerial-snappy.svg?type=shield)](https://app.fossa.io/projects/git%2Bgithub.com%2Fcanv15%2Fgo-xerial-snappy?ref=badge_shield)

Xerial-compatible Snappy framing support for golang.

Packages using Xerial for snappy encoding use a framing format incompatible with
basically everything else in existence. This package wraps Go's built-in snappy
package to support it.

Apps that use this format include Apache Kafka (see
https://github.com/dpkp/kafka-python/issues/126#issuecomment-35478921 for
details).


## License
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Fcanv15%2Fgo-xerial-snappy.svg?type=large)](https://app.fossa.io/projects/git%2Bgithub.com%2Fcanv15%2Fgo-xerial-snappy?ref=badge_large)