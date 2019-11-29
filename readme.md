# NTS Radio downloader

Downloads [NTS](https://www.nts.live) episodes (with metadata!) for offline listening.

## Installation

First install all the requirements.

```sh
pip3 install -r requirements.txt
```

## Usage

Just paste the episode url and it will be downloaded in your Downloads folder at `~/Downloads`.

```sh
python3 nts.py https://www.nts.live/shows/lee-gamble/episodes/lee-gamble-7th-october-2019
```

Alternatively, you can pass a show/host url to download all its episodes.

```sh
python3 nts.py https://www.nts.live/shows/team-sesh
```

If you have multiple urls, write them into a file line by line and pass the file to the script.
Show urls will be expanded and downloaded as well.

```sh
python3 nts.py links.txt
```
