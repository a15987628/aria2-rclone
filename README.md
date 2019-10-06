# aria2-rclone
Aria2 + rclone upload file to google dirve automatically
```
docker run --name aria2-rclone \
-p 6800:6800 -p 6880:80 -p 6888:8080 \
-v /RCLONE_CONF_DIR:/root/.config/rclone \
-e SECRET=YOUR_SECRET_CODE johnshh/aria2-rclone
```
