VOODO
=====

Video / Audio Downloader.
See [**supported 1500+ sites**](https://github.com/yt-dlp/yt-dlp/blob/master/supportedsites.md).

### Usage

	Usage:
	  ./voodo [OPTIONS] -u <URL> | -i <FILE>
	  ./voodo -f mp4 -s 1080 -u <URL> -r 1-2,5
	  ./voodo -f mp3 -i favs.txt
	
	Options:
	  -u    Input URL
	  -i    Input file
	  -f    Format mp3,mp4,subtitle (default:mkv)
	  -s    Video resolution 480,720 (default:highest)
	  -r    Playlist range 1,2-6
	  -h    Print this help
	  -v    Print version

### Installation

```bash
python3 -m pip install -U yt-dlp
apt install ffmpeg
chmod +x voodo
./voodo
```

-----
