# EDO Ranked — OCG & TCG

**[Trang chủ & bảng xếp hạng](https://edorank.top)**

**[TẢI BẢN WINDOWS](https://github.com/IplayIshare/edo-ranked/releases/latest/download/EDO-Ranked-Windows-x64.zip)**

Dành cho Windows 10/11 64-bit. Giải nén toàn bộ rồi mở **Play-EDO.cmd**.
Không cần cài Python riêng.

**Từ bản 0.1.6:** launcher mở màn hình đăng nhập tại **http://edorank.localhost:7926**.
Đây là cửa sổ trên máy bạn để đăng nhập và vào trận, kết nối đến máy chủ Ranked.
Mở bằng **Play-EDO.cmd** trước khi truy cập địa chỉ này. Trang **edorank.top** dành
cho tải game và xem bảng xếp hạng công khai. Không cần sửa DNS hay file hosts.

**Đang dùng bản cũ v0.1.1 trở lên?** Tải [gói bật tự động cập nhật](https://github.com/IplayIshare/edo-ranked/releases/latest/download/EDO-Ranked-Enable-AutoUpdate.zip).
Đóng game, giải nén 3 file vào thư mục EDO Ranked hiện có (cùng chỗ với
`Play-EDO.cmd`), đồng ý ghi đè rồi mở **Play-EDO.cmd**. Không cần tải lại cả bộ game.

**Từ bản 0.1.5:** launcher tự kiểm tra và tải các bản vá còn thiếu mỗi khi mở.
Deck, replay và cài đặt được giữ nguyên. Giữ file `FILES.sha256` để nhận diện phiên bản.
Khi game đang chạy, cập nhật sẽ được hoãn; đóng game và mở launcher để cập nhật.
Nếu mất mạng hoặc file tải bị hỏng, bản hiện tại được giữ lại để thử lại lần sau.

Dữ liệu bài gồm đủ 100 lá của **Beyond the Brave** theo TCG, bao gồm
**Hey, Space Trunade!** (tên cũ: Spatial Trunade), tên/nội dung bài và 16 mã bài
chính thức thay cho mã tạm. Deck cũ được chuyển mã khi mở bằng bản mới.
Các đợt cập nhật card sẽ theo sản phẩm TCG chính thức; rank OCG vẫn giữ luật riêng.

**Bản 0.1.7** sửa 32 lá **Magnificent Monsters** đã phát hành TCG nhưng còn bị
gắn OCG-only, gồm **Assault Blackwing - Kusanagi the Gathering Storm**. Đã đồng bộ
máy chủ, biến thể ảnh, tên và nội dung TCG. Đóng game rồi mở lại **Play-EDO.cmd**
để nhận bản vá; bài chưa phát hành TCG vẫn bị chặn theo luật.

Đăng nhập tài khoản cũ; không cần đăng ký lại, điểm số được giữ nguyên.

## Vào chơi

1. Mở **Play-EDO.cmd** và chọn **Tạo tài khoản** nếu chơi lần đầu.
2. Đăng nhập, chọn **Thi đấu OCG** hoặc **Thi đấu TCG**.
3. Trong game: **Servers / Online → EDO Ranked - Dang nhap → Refresh → phòng Ranked → Join**.
4. Chọn deck và **Ready**. Cần hai người cùng thể thức để bắt đầu.

Tạo deck trong Deck Edit hoặc chép file `.ydk` của bạn vào `game/deck`.
Giữ launcher chạy trong lúc chơi. Điểm OCG/TCG và lịch sử tự cập nhật trên trang hồ sơ.
BO3, Master Rule 5, 8000 LP; rời trận/đang side deck sẽ bị xử thua.

## Nếu chưa vào được

- Giải nén trước khi chạy; đặt trong thư mục có quyền ghi, tránh Program Files.
- Chỉ mở một bản EDO Ranked mỗi máy. Kiểm tra Internet rồi mở lại Play-EDO.cmd.
- Nếu chưa thấy phòng, bấm Thi đấu OCG/TCG trên trang hồ sơ rồi Refresh trong game.
- Có phòng nhưng chưa đấu: chờ người thứ hai và cả hai bấm Ready.
- Luôn mở bằng **Play-EDO.cmd** để nhận cập nhật. Các file `EDO-Update-...zip`
  trong Assets dành cho launcher, không cần tải/giải nén bằng tay.
- Chưa hỗ trợ tự đặt lại mật khẩu qua email; dùng mật khẩu riêng cho game.

[Các bản tải](https://github.com/IplayIshare/edo-ranked/releases) · [Nguồn gốc và giấy phép](THIRD_PARTY.md)

Kho này chỉ cung cấp bản tải và hướng dẫn dành cho người chơi. Trong mục Assets,
hãy chọn **EDO-Ranked-Windows-x64.zip**; các gói “Source code” GitHub tự tạo chỉ chứa tài liệu.
