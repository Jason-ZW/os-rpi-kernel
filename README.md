# OS RaspberryPI Kernel
![GitHub release](https://img.shields.io/github/v/release/Jason-ZW/os-raspberrypi.svg)

This repo used to build rancheros raspberrypi. Fetch all resource files from the upstream repositories:
- [https://github.com/raspberrypi/linux](https://github.com/raspberrypi/linux)
- [https://github.com/raspberrypi/firmware](https://github.com/raspberrypi/firmware)

## Prepare
- `docker`
- `go get -u -v github.com/rancher/dapper`

## How to run
```shell
make
```

## License
Copyright (c) 2014-2019 [Rancher Labs, Inc.](http://rancher.com)

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

[http://www.apache.org/licenses/LICENSE-2.0](http://www.apache.org/licenses/LICENSE-2.0)

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
