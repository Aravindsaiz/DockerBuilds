--build  
* docker buildx build --platform linux/amd64 -t yt-downloader:0.1 .
--run 
* docker run -it --mount type=bind,src=<>,dst=/wordir/local yt-downloader:0.1 sh