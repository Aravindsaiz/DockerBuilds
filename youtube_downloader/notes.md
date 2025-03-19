--build  
* docker buildx build --platform linux/amd64 -t yt-downloader:0.1 .
--run 
* docker run -it --mount type=bind,src=C:\Users\aravi\Desktop\YT_downloads,dst=/wordir/local yt-downloader:0.1 sh