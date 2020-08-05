<p align="center">
  <b>
    <span style="font-size:larger;">closewait</span>
  </b>
  <br />
   <a href="https://travis-ci.com/detailyang/closewait"><img src="https://travis-ci.com/detailyang/closewait.svg?token=thDZbmEQtVwYMM6yT8Dv&branch=master"/></a>
   <a href="https://ci.appveyor.com/project/detailyang/closewait"><img src="https://ci.appveyor.com/api/projects/status/drc2xk4kcoiydr0x?svg=true" /></a>
   <br />
   <b>closewait close closed-wait sockets via procfs</b>
</p>

# Purpose

Kill the close-wait sockets via [procfs](https://man7.org/linux/man-pages//man5/procfs.5.html) in low version kernel which is do not have [SOCK Destory](https://lwn.net/Articles/666592/) feature.

# Usage

## oneline

`closewait -p pid`

```bash
```

# Install

1. cargo install closewait
2. Download the binary from [closewait/releases](https://github.com/detailyang/closewait/releases)

> only support linux

# License
closewait is under the [MIT license](/LICENSE). See the [LICENSE](/LICENSE) file for details.
