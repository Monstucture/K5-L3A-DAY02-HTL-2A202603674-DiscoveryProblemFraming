# Báo cáo cá nhân — MSSV_HoTen

> Đổi tên file theo quy tắc `MSSV_HoTen.md`, ví dụ `20241234_NguyenVanAn.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Sửa cả dòng tiêu đề phía trên cho khớp.
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).
> Mỗi thành viên một file trong `report/individual/` trên repo nhóm: copy template này thành file mới, điền, rồi commit bằng tài khoản GitHub của bạn. Không viết hộ người khác.

## 1. Thông tin học viên

- Họ tên: Nguyễn Sơn Tùng
- MSSV: 2A202603658
- Email trường (không bắt buộc, repo có thể để public):
- Tên nhóm: HTL
- Link repo nhóm: https://github.com/Monstucture/K5-L3A-DAY02-HTL-2A202603674-DiscoveryProblemFraming/

---


## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
|---:|---|---|---|---|
| 1 | Lặp lại | Mỗi lần tổng hợp thuế cần một cơ chế số hóa các loại giấy tờ dùng bản giấy như phiếu thu, phiếu chi, hóa đơn có đóng dấu từ cty đối tác... | Hành Chính-Kế toán | khoảng 3 tháng/lần, nhân lực nhiều |
| 2 | Cần đọc, tổng hợp nhiều thông tin | Khi có một lượng lớn CV gửi về công ty, cần một danh sách tổng hợp rõ ràng | HR | Tốn thời gian để nhập dữ liệu vào bảng tổng hợp với các trường cố định  *Họ tên, email...*. |
| 3 | Pain từ người khác | Việc xếp lịch phỏng vấn 3 bên thường tốn nhiều vòng email trao đổi. Cần một cơ chế tự động sắp lịch để khớp 3 bên | HR, Ứng Viên, Interviewer |  |
| 4 | Lặp lại | Mỗi tuần cần một bảng báo cáo tổng hợp chi phí hàng tuần báo cáo cấp trên | CEO, Kế toán, trưởng phòng | Hay gặp tình trạng báo cáo trễ, thiếu số liệu các khoản chi |
| 5 | Pain từ người khác | Quy trình trình ký và duyệt chi bị nghẽn do hóa đơn/chứng từ bản cứng chờ sếp duyệt trực tiếp, dẫn đến thanh toán chậm cho nhà cung cấp. | Kế toán, Trưởng phòng, Ban Giám Đốc | Diễn ra liên tục hàng tuần, làm trễ hạn thanh toán và ảnh hưởng đến uy tín với đối tác |
| 6 | Lặp lại | Mỗi khi có nhân viên mới onboard, HR phải tạo thủ công tài khoản email, phân quyền thư mục Google Drive, thêm vào các nhóm chat và gửi chuỗi email chào mừng/hướng dẫn ban đầu.|HR, IT| Mỗi khi có nhân viên mới, tốn khoảng 30–40 phút/nhân sự cho các thao tác lặp đi lặp lại |
| 7 | Cần đọc, tổng hợp nhiều thông tin | Mỗi khi chấm công cuối tháng, HR/Kế toán phải kiểm tra thủ công từng dòng dữ liệu vào/ra từ máy chấm công, đối soát danh sách xin nghỉ phép (giấy/email) để nhập vào bảng công tổng. | HR, Kế toán | 1 tháng/lần, tốn 2-3 ngày làm việc để đối soát và dễ xảy ra sai sót dữ liệu |
| 8 | Cần đọc, tổng hợp nhiều thông tin | Trưởng phòng/Ban giám đốc mất nhiều thời gian đọc và tổng hợp phản hồi (Feedback/Review) từ khách hàng trên nhiều kênh (Facebook, Email, Hotline) để tìm ra các lỗi sản phẩm/dịch vụ phổ biến. | Trưởng phòng CSKH, Ban Giám Đốc | Tốn 4-5 giờ/tuần để đọc thủ công, dễ bỏ sót phản hồi quan trọng hoặc đánh giá thiếu khách quan |

**Nếu có dùng AI để gợi ý thêm:** ý nào AI gợi ý mà bạn giữ lại, ý nào bỏ và vì sao.

- AI gợi ý mục 5, 6, 7, 8. Các mục còn lại tự nghĩ.
 
---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | Khi có một lượng lớn CV gửi về công ty, cần một danh sách tổng hợp rõ ràng để lọc nhanh các ứng viên tiềm năng | CV có nhiều định dạng khác nhau, trường thông tin cố định | Có khả năng áp dụng AI | Không thường xuyên |
| 2 | Mỗi lần tổng hợp thuế cần một cơ chế số hóa các loại giấy tờ dùng bản giấy như phiếu thu, phiếu chi, hóa đơn có đóng dấu từ cty đối tác... | Phải sử dụng AI | Dữ liệu số hóa không rõ ràng |
| 3 | Quy trình trình ký và duyệt chi bị nghẽn do hóa đơn/chứng từ bản cứng chờ sếp duyệt trực tiếp, dẫn đến thanh toán chậm cho nhà cung cấp. | Dễ làm, áp dụng nhanh, không AI | Dữ liệu không rõ ràng, cần đối tác đồng ý |

### Problem Card #1

| Trường | Nội dung |
|---|---|
| Job Story | Khi có một lượng lớn CV gửi về công ty, cần một danh sách tổng hợp rõ ràng để lọc nhanh các ứng viên tiềm năng |
| Actor | HR |
| Thời điểm / bối cảnh | Khi công ty tuyển dụng nhân sự mới |
| Quy trình hiện tại (3–7 bước) | Công ty ra thông báo tuyển dụng. Đợi hết thời gian ứng tuyển. HR đọc CV và nhập liệu. Sàng lọc và tuyển chọn ứng viên |
| Bottleneck (bước nào, mất bao nhiêu phút) | HR đọc CV và nhập liệu. Mỗi CV mất 3 phút => 300CV mất 2-3 ngày làm việc |
| Impact (nếu không giải thì sao) | Bỏ sót ứng viên tiềm năng, mất thời gian làm việc của HR lại chỉ để nhập liệu |
| Success metric (baseline → target) | Giảm thời gian từ 2-3 ngày cho 300CV xuống 10 -15 phút |
| Phương án không dùng AI | Yêu cầu ứng viên nộp CV theo form  mẫu, dùng app nội bộ đọc form |
| Giả thuyết về AI (nếu có) | OCR và/hoặc đọc tài liệu |
| Cảm nhận nhanh | Workflow |

Quy trình nháp hiện tại:

```text
- AI sẽ OCR CV nếu là file ảnh và/hoặc đọc tài liệu (nếu là file doc...) => Json object => Lưu database
```

### Problem Card #2

| Trường | Nội dung |
|---|---|
| Job Story | Mỗi lần tổng hợp thuế cần một cơ chế số hóa các loại giấy tờ dùng bản giấy như phiếu thu, phiếu chi, hóa đơn có đóng dấu từ cty đối tác... |
| Actor |  Hành Chính-Kế toán  |
| Thời điểm / bối cảnh | Mỗi đợt tổng hợp thuế. 3 tháng/lần |
| Quy trình hiện tại (3–7 bước) | Lấy các cặp/hồ sơ chứa các loại giấy tờ liên quan. Cho máy scan toàn bộ tài liệu để lưu bản mềm. Cần người trích xuất dữ liệu từ các giấy tờ đã scan |
| Bottleneck (bước nào, mất bao nhiêu phút) | Cần người trích xuất dữ liệu từ các giấy tờ đã scan (4-5 ngày mỗi 3 tháng) |
| Impact (nếu không giải thì sao) | Sai sót dữ liệu, thiếu thu chi |
| Success metric (baseline → target) | từ 4-5 ngày xuống còn 1-2 ngày |
| Phương án không dùng AI | Yêu cầu đối tác, kế toán, nhân viên thống nhất số hóa các loại giấy tờ |
| Giả thuyết về AI (nếu có) | OCR, lọc thông tin từ bản mềm |
| Cảm nhận nhanh | Workflow | 

Quy trình nháp hiện tại:

```text
- AI sẽ OCR => Nhóm và phân các loại giấy tờ: phiếu thu, phiếu chi, hóa đơn...
```

### Problem Card #3

| Trường | Nội dung |
|---|---|
| Job Story | Quy trình trình ký và duyệt chi bị nghẽn do hóa đơn/chứng từ bản cứng chờ sếp duyệt trực tiếp, dẫn đến thanh toán chậm cho nhà cung cấp. |
| Actor |  Kế toán, Trưởng phòng, Ban Giám Đốc  |
| Thời điểm / bối cảnh | Diễn ra liên tục hàng tuần |
| Quy trình hiện tại (3–7 bước) | Kế toán xuất hóa đơn. In bản cứng. Chờ sếp có mặt tại văn phòng ký duyệt |
| Bottleneck (bước nào, mất bao nhiêu phút) |  Chờ sếp có mặt tại văn phòng ký duyệt. Tối thiểu nửa ngày làm việc |
| Impact (nếu không giải thì sao) | làm trễ hạn thanh toán và ảnh hưởng đến uy tín với đối tác |
| Success metric (baseline → target) | Ký duyệt chi ngay khi có hóa đơn |
| Phương án không dùng AI | Đợi sếp |
| Giả thuyết về AI (nếu có) | Không dùng AI |
| Cảm nhận nhanh | NO AI |

Quy trình nháp hiện tại:

```text
Chuyển sang chữ ký số, hóa đơn điện tử
```

### Card muốn pitch nhất

- Card số: 1
- Vì sao: mục đích, đầu ra dữ liệu rõ ràng
- Câu hỏi muốn nhóm phản biện: Vì công ty không tuyển dụng thường xuyên, có nên đầu tư để áp dụng AI?

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| | | |

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card | | |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt: | |
| Nhận phản biện | Câu hỏi tôi nhận được: | Tôi đã sửa gì: |
| Gom cluster / cây OST | | |
| Chọn candidate problem | | |
| Kiểm chứng / research | | |
| Quy trình nhóm | | |
| Problem Statement | | |
| Mức can thiệp AI | | |
| Quyết định | | |

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | | | | |
| CP2 Problem Card | | | | |
| CP4 Research | | | | |
| CP5 Quy trình | | | | |
| CP5–6 Problem Statement | | | | |
| CP6 Mức can thiệp / quyết định | | | | |

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**

**6.5. Điều khó nhất khi viết Problem Statement là gì?**

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**

**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.

---

## 7. Tài liệu tham khảo

-
