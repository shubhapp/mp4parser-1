ffmpeg -re -i all.mp4  -c:v copy -c:a copy -map 0:0  -f rtp rtp://127.0.0.1:5000/  -c:v copy -c:a copy  -map 0:1  -f rtp rtp://127.0.0.1:5001/ -c:v copy -c:a copy  -map 0:2  -f rtp rtp://127.0.0.1:5002/  -c:v copy -c:a copy  -map 0:3  -f rtp rtp://127.0.0.1:5003/  -c:v copy -c:a copy  -map 0:4  -f rtp rtp://127.0.0.1:5004/  -c:v copy -c:a copy  -map 0:5  -f rtp rtp://127.0.0.1:5005/

ffmpeg -re -i all.mp4  -c:v copy -c:a copy -map 0:0  -f rtp rtp://192.168.255.255:5000/  -c:v copy -c:a copy  -map 0:1  -f rtp rtp://192.168.255.255:5001/ -c:v copy -c:a copy  -map 0:2  -f rtp rtp://192.168.255.255:5002/  -c:v copy -c:a copy  -map 0:3  -f rtp rtp://192.168.255.255:5003/  -c:v copy -c:a copy  -map 0:4  -f rtp rtp://192.168.255.255:5004/  -c:v copy -c:a copy  -map 0:5  -f rtp rtp://192.168.255.255:5005/