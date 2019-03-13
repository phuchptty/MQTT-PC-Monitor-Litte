# Home Assistant MQTT PC Monitor Lite Version
Cập nhật trạng thái máy tính lên Home Assistant qua MQTT

## Cài đặt

Tải về tại Tab [Releases](https://github.com/phuchptty/MQTT-PC-Monitor-Lite/releases) hoặc dùng Git:

```bash
git clone https://github.com/phuchptty/MQTT-PC-Monitor-Litte.git
```
Lưu ý: Dùng Git sẽ không có tự động khởi chạy !

## Thiết lập MQTT
Vào file config.json trong thư mục cài đặt mặc định và chỉnh sửa.

```text
{
  "mqtt" : {
    "broker" : "192.168.1.00", # Broker MQTT
    "username" : "mqtt",  # Tài khoản Broker (bỏ trống nếu không có)
    "password" : "", # Mật Khẩu Broker (bỏ trống nếu không có)
    "port" : "1883"  # Công Kết Nối Broker
  },

  "customPCName" : "pc", # Tên PC

  "channel" : {
    "ram" : "/ram",
    "cpu" : "/cpu",
    "disk" : "/disk",
    "battery" : "/batt"
  }
}

```

## Đóng Góp
Nếu bạn muốn đóng góp vui lòng lập 1 pull request. 

Mọi thắc mắc vui lòng để trong tab [issue](https://github.com/phuchptty/MQTT-PC-Monitor-Litte/issues)

## Bản Quyền
Thuộc về [Đặng Phúc](https://www.facebook.com/hoangphuchotboy).

Được chia sẻ trong Group [Smarthome Việt](https://www.facebook.com/groups/784535325063755/?fref=nf).

## License
[GPLv3](https://choosealicense.com/licenses/gpl-3.0/)