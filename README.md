# This whole repo is against Google Colab policy and you shouldn't be using it.
> **Why are hardware resources such as T4 GPUs not available to me?**
The best available hardware is prioritized for users who use Colaboratory interactively rather than for long-running computations. Users who use Colaboratory for long-running computations may be temporarily restricted in the type of hardware made available to them, and/or the duration that the hardware can be used for. We encourage users with high computational needs to use Colaboratory’s UI with a local runtime.
Please note that using Colaboratory for cryptocurrency mining is disallowed entirely, and may result in being banned from using Colab altogether.

<sub>Source: https://research.google.com/colaboratory/faq.html</sub>

# Torrent To Google Drive Downloader
Simple notebook to stream torrent files to Google Drive using Google Colab.

[![](https://img.shields.io/badge/Google%20colab-Open-FFC000.svg?style=for-the-badge&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAA4AAAAOCAMAAAAolt3jAAAABGdBTUEAALGPC/xhBQAAACBjSFJNAAB6JgAAgIQAAPoAAACA6AAAdTAAAOpgAAA6mAAAF3CculE8AAAB8lBMVEUAAAD/7QL/6w7/6gz/6w3/6Qj/6Qj/6wj/6gf/6w//6w7/6xP/7gP/2hr/2xX/2jD/z0j/uHX/1zn/3Sz/3Sv/1zn/r4L/zE3/2jL/4ST/4Cf/0RP//zH/3S//2jL/2jL/2zH/3iv/3in/2zD/2jL/2jL/3C///0b/1B3/yxL/xAj/0SH/2DT/2TX/2TX/3C7/2jP/2DX/2DX/2DX/1zD/zRb/YwD/wgf/wQf/xAr/1iX/3C//3C//2zH/2Db/2jP/3C7/2zD/zBf/wgj/wgf/wgf/wQf/wQf/0ST/2y7/5B3/2TT/2TT/3iv/2y//zSD/wQb/wQf/wgf/wgf/wQf/wQf/zx7/3Cz/4x//2TT/2TX/4TD/zRb/wQf/wgf/wQf/wgf/wgf/wQf/wwr/1iT/3S//3C7/2zH/1zH/zBb/wQT/wgf/wQf/wQf/wgf//4r/xAj/0CD/2DT/2TX/2TX/3C7/zBb/wgj/wQf/wQf/wQf/wgf/xgf/0BL/6Rz/3C//2jL/2jP/2zH/3iz/vwD/wgf/wgf/wgf/wgf/xAf/wgf/2Rr/2hf/2TH/t3f//wD/1D//3S7/wgX/wAf/0wj/uQf/wQf/wwf/wgf/5gX/5h//6BT/5xb/6Q//6RD/xAf/xAf/xQf/xAf/xQf/xAf///9tAmifAAAApXRSTlMAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAATiFmGgWFGaZi0EDAABa6v/5+32y//r/8WoBJ9viYD9wnv+kPlvc5TRg/XsAAArH4yEAAGz+cmL9dgAACsjhHgAAZ/50LOHcUzRbm/+VLUjT6TcAZvH89Pd5uv/x+fRxAgADRJSldRsYcKOVSAQAAAAAAAEAAAAAAQAAAAAAAAAAAAAAAAAAAABydb0CAAAAAWJLR0SlLrlKLwAAAAd0SU1FB+QIEQUaC7jgabcAAAABb3JOVAHPoneaAAAAwUlEQVQI12NgQAOMTMwsrGzsHJxc3DwMDLx8/AKCQsIiomLiEpJSDNIysnLyCopKyiqqauoaDJpa2jq6evoGhkbGJqZmDOYWllbWNrZ29g6OTs4uDK5u7h6eXt4+vn7+AYFBDMEhoWHhEZFR0TGxcfEJDIlJySmpaekZmVnZObl5DPkFhUXFJaVl5RWVVdU1DLV19Q2NTc0trW3tHZ1dDN09vX39EyZOmjxl6rTpMxgYZs6aPWfuvPkLFi5avATdAwCl1jTbaxUL4wAAAF5lWElmSUkqAAgAAAADABIBAwABAAAAAQAAADEBAgANAAAAMgAAAGmHBAABAAAAQAAAAAAAAABQaG90b3MgMi43LjAAAAIAAqAJAAEAAADTAAAAA6AJAAEAAADTAAAAAAAAAJOs9JgAAAAldEVYdGRhdGU6Y3JlYXRlADIwMjAtMDgtMTdUMDU6MjY6MTErMDA6MDBd4jn+AAAAJXRFWHRkYXRlOm1vZGlmeQAyMDIwLTA4LTE3VDA1OjI2OjExKzAwOjAwLL+BQgAAABh0RVh0ZXhpZjpFeGlmSW1hZ2VMZW5ndGgAMjExdjfLjwAAABd0RVh0ZXhpZjpFeGlmSW1hZ2VXaWR0aAAyMTHrqE6dAAAAEnRFWHRleGlmOkV4aWZPZmZzZXQANjTZeQZNAAAAGnRFWHRleGlmOlNvZnR3YXJlAFBob3RvcyAyLjcuMIcagsYAAAAASUVORK5CYII=)](https://colab.research.google.com/github/MoonLGH/torrent-to-google-drive-downloader/blob/master/torrent-to-google-drive-downloader.ipynb)

### Tutorial
Click the badge which says 'Open' above and follow directions there.

### What is the purpose of it?
1. Because of Google Servers' speed, I downloaded 12GB of a file and the average speed was 60MBPS.
2. Because it is in the cloud, by that I mean I can access it anywhere on my phone, tablet, etc without copying files around

### Frequently Asked Questions
1. **How to get more disk space**:

    > Go to Runtime -> Change Runtime and give GPU as the Hardware Accelerator.  
You will get around 384GB to download any torrent you want.

2. **Downloading missing files without re-downloading whole torrent**: If somehow some files are missing try to re-download torrent. Fastresume will check files.

For more questions check [existing issues](https://github.com/FKLC/Torrent-To-Google-Drive-Downloader/issues) or [open a new one](https://github.com/FKLC/Torrent-To-Google-Drive-Downloader/issues/new)
