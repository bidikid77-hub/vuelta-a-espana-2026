# Vuelta a España 2026

Lịch chặng **Vuelta a España 2026** dạng **ICS / WebCal** để đăng ký trên iPhone, Apple Calendar, Google Calendar, Outlook.

## Nguồn

- Official route: https://www.lavuelta.es/en/overall-route

## File trong repo

| File | Mục đích |
|---|---|
| `vuelta-a-espana-2026.ics` | file lịch chính để subscribe |
| `index.html` | landing page GitHub Pages |
| `route-source.json` | dữ liệu nguồn đã parse |
| `lavuelta-overall-route.html` | HTML nguồn chính thức lưu để đối chiếu |

## Cách dùng trên iPhone / Apple Calendar

Mở landing page GitHub Pages rồi bấm nút **Đăng ký trên iPhone**.

WebCal URL:

```text
webcal://bidikid77-hub.github.io/vuelta-a-espana-2026/vuelta-a-espana-2026.ics
```

HTTPS fallback:

```text
https://bidikid77-hub.github.io/vuelta-a-espana-2026/vuelta-a-espana-2026.ics
```

## Nội dung lịch

- 23 event
- 21 chặng + 2 ngày nghỉ
- Dạng all-day để ổn định trên iOS khi nguồn không công bố giờ xuất phát chi tiết

## GitHub Pages

Landing page:

```text
https://bidikid77-hub.github.io/vuelta-a-espana-2026/
```

ICS:

```text
https://bidikid77-hub.github.io/vuelta-a-espana-2026/vuelta-a-espana-2026.ics
```

## Build từ source

Dữ liệu nguồn đã được parse từ trang chính thức La Vuelta và lưu trong `route-source.json`.

Nếu cần làm lại:
1. cập nhật nguồn
2. regenerate `vuelta-a-espana-2026.ics`
3. commit cùng `index.html` và `README.md`

## Lưu ý

- `index.html` phải giữ đúng repo path.
- Nếu Pages chưa hiện ngay, chờ vài phút rồi refresh.
