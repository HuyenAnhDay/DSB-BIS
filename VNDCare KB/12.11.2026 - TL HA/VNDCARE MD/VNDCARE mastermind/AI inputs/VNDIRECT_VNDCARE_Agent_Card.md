---
eyebrow: "VNDIRECT · NHÀ VNDS · CU · CU_VNDCARE · Phiếu agent"
sub: "VNDCARE Agent — agent cho CA/BA: đọc bốn kim Dgo · Dinvest · Dcare · Dvalues của từng khách, chuẩn bị cho người đồng hành; đứng cặp với VNDGO Agent của khách"
ver: "Bản 0.1 · 03/11/2026 · bản nháp bước 1 · 2 · 3 · 6 của bảy bước · Chủ sở hữu chốt 03/11: VNDGO Agent là cho khách, VNDCARE Agent là cho CA/BA; VNDCARE Agent chạy trước · chờ Head CU_VNDCARE, CU_VNDGO sửa vai, Pháp chế và CGC đọc lan can"
foot: "VNDIRECT · CU_VNDCARE · VNDIRECT_VNDCARE_Agent_Card · Lưu hành nội bộ"
---

# VNDIRECT_VNDCARE_Agent_Card — PHIẾU VNDCARE AGENT

## ĐỌC TRƯỚC

> WHY — La bàn bốn kim chỉ có nghĩa khi có người dùng nó trong việc thật. Một CA giữ hàng trăm khách không tự đọc được bốn kim của từng người mỗi ngày. Agent đọc thay, để mỗi lần CA ngồi với khách là một lần đọc lại kế hoạch của chính khách, không phải một buổi chào bán.

> HOW — Agent đứng sau CA/BA: máy chuẩn bị, người đồng hành nói chuyện với khách. Cặp với nó là VNDGO Agent ở CU_VNDGO — agent cho chính khách, chạy trên app; VNDGO Agent chỉ mở khi VNDCARE Agent chạy song song đủ một quý. Hai agent đọc cùng bốn kim của một khách, nên một khách chỉ có một la bàn.

> WHAT — Mười ô · vai · dữ liệu · lan can · từng bước · việc phải xong trước · ô treo.

## MƯỜI Ô

| Ô | Điền |
|---|---|
| Tên agent | VNDCARE Agent |
| Mastermind gốc | VNDCARE_MASTERMIND (12 tờ ở CU\CU_VNDCARE) đọc cùng VNDGO_MASTERMIND (17 tờ ở CU\CU_VNDGO); cả hai chưa đóng thành bốn quyển và gói (xem mục Việc phải xong trước) |
| Việc giao máy | ① la bàn sáng cho CA · ② chuẩn bị buổi đồng hành · ③ nháp kế hoạch Dinvest theo tháp HWG · ④ đọc Dvalues cuối kỳ, cả hai tầng · ⑤ sổ chăm và lời nhắc hẹn lại |
| Vai | xem bảng Vai |
| Dữ liệu | xem bảng Dữ liệu |
| Ruột tính | VNDIRECT_VNDCARE_AppCompass (app nghề CA/BA hai chiều, tám màn, lan can) · VNDIRECT_VNDCARE_CraftBank · VNDIRECT_VNDCARE_FCLiving · VNDIRECT_VNDGOCompass_BonKim (bốn kim, sáu bước dựng la bàn cho một khách, mười lan can) · VNDIRECT_VNDGO_ClientIndicators phụ lục C (luật L1 … L10, cách tính mười điều C1 … C10) |
| Nhịp | ① mỗi sáng trước giờ làm · ② trước mỗi lịch hẹn · ③ khi CA gọi · ④ cuối kỳ · ⑤ sau mỗi buổi gặp |
| Lan can | xem bảng Lan can |
| Phép thử | chạy máy trên năm bộ câu trả lời mẫu (ClientIndicators phụ lục B3); trạng thái mười điều và việc tiếp theo phải khớp năm màn hình mẫu ở mục 4 của tờ ấy |
| Người giữ agent · người kiểm · người nhận báo cáo | team map người |

## VAI

| Việc | Máy tự làm (bản cho CA đọc) | Máy đề xuất | Máy không làm |
|---|---|---|---|
| ① La bàn sáng | với mỗi khách gói DCA của CA: kim đang sáng, tín hiệu đầu và hàng chờ theo VNDIRECT_VNDGO_CompassSignals; khách DA về đội chăm trên nền số (OB-2), khách DMA về partner | khách nên gặp tuần này | xếp hạng khách, chấm điểm |
| ② Chuẩn bị buổi đồng hành | tờ đọc lại kế hoạch: đích khách tự đặt (nguyên văn «»), tiến độ góp, kim đang lệch, ba câu hỏi mở | — | kịch bản chào bán sản phẩm |
| ③ Nháp kế hoạch Dinvest | — | đường đi từng lớp của tháp HWG, đi từ lớp H lên, theo track khách đủ điều kiện | gợi ý mã cổ phiếu, dự phóng lãi; trình cho khách — CA có chứng chỉ hành nghề trình, khách tự đặt |
| ④ Dvalues cuối kỳ | đọc cả hai tầng; danh sách khách «tài khoản chạy mà người đứng yên ba kỳ» | khách nên mời đọc lại đích | đưa điểm CMI cho khách |
| ⑤ Sổ chăm | từ ghi chú sau buổi của CA: ghi dấu vết chăm, nhắc ngày hẹn lại, báo khách quá hạn chưa gặp cho đội trưởng | — | đánh giá CA, chấm doanh số |

## DỮ LIỆU

| Luồng | Đọc gì | Ghi gì |
|---|---|---|
| CMS | hồ sơ VNDGO bảy lớp, câu trả lời của khách, trường đồng ý | — |
| AMS | giá trị khách đang giữ | — |
| TMS | dấu vết góp, giữ nguyên tắc, buổi gặp | dấu vết chăm (việc ⑤) |
| OMS | kế hoạch đang chạy tới đâu | — |
| PMS | danh mục SPDV khách đủ điều kiện | — |
| iMS | CA nào đi cùng khách (mã CA) | — |

Không đọc FMS. Không đọc kết quả soi sáng và dữ liệu hành vi của khách chưa đồng ý riêng; câu trả lời nhịp hai chỉ đọc khi khách đã đồng ý B2.

Che khách: trong KMS khách chỉ là mã; tên khách chỉ hiện trên công cụ của CA trong hệ thống của nhà. Tệp không có tên, số giấy tờ, số điện thoại.

Kiểm trước khi chạy: đủ luồng · giá trị tài sản khớp sổ lưu ký trong 0,5% · trường quá hạn hiệu lực (12 tháng, ba lớp nền 90 ngày) hiện «Cần xem lại», không coi là trống.

## LAN CAN

1. Không liên lạc khách: không gửi tin, không gọi, không đặt lịch thay khách. CA và người đồng hành VNDCARE nói chuyện với khách.
2. Không chấm điểm, không xếp hạng một khách; CMI ở trong nhà, khách không thấy điểm.
3. Không gợi ý mã, không dự phóng lãi, không chào bán; kế hoạch Dinvest là nháp cho CA, khách tự đặt.
4. Chỉ đọc trường khách đã đồng ý; không đưa dữ liệu khách ra khỏi hệ thống của nhà.
5. Không dùng la bàn và sổ chăm để chấm doanh số CA.
6. Lời khách giữ nguyên văn; số không khớp sổ thì dừng; mọi bản ra là bản máy, CA đọc và quyết.

## TỪNG BƯỚC CỦA NĂM VIỆC

| Việc | Đọc gì → chạy gì → đối chiếu gì → ghi ra đâu |
|---|---|
| ① | CMS + mã sự kiện của CU_BIS + chặng → máy tính mười điều và tín hiệu (CompassSignals) → chọn một kim sáng → danh sách sáng, chia theo người nhận |
| ② | CMS + AMS + OMS của một khách → sáu bước dựng la bàn (BonKim mục 12) → so đích khách tự đặt với tiến độ → tờ đọc lại kế hoạch |
| ③ | CMS lớp nền tài chính + PMS → tháp HWG, đi từ lớp H → so điều kiện track → nháp kế hoạch cho CA |
| ④ | AMS + TMS cuối kỳ → đọc tầng tài khoản và tầng người → tìm người đứng yên ba kỳ → danh sách cho CA |
| ⑤ | ghi chú sau buổi → TMS → lịch hẹn lại → lời nhắc cho CA, danh sách quá hạn cho đội trưởng |

Máy tính trạng thái mười điều (bước ①) dùng chung với VNDGO Agent — viết một lần, hai agent cùng gọi.

## VIỆC PHẢI XONG TRƯỚC

| Việc | Ai | Vì sao |
|---|---|---|
| Đóng VNDCARE_MASTERMIND và VNDGO_MASTERMIND: bốn quyển chữ · luật · bài học · gói mỗi bộ | phiên Mastermind, Chủ sở hữu duyệt chữ và luật | agent cần gói mang ruột tính, không chỉ trỏ về tờ |
| Đóng ô VN-DGO-3 (nhịp đọc bốn kim) và APP-2 (tờ bốn kim đọc lại theo chốt 23/10) | Chủ sở hữu | máy đọc bốn kim theo một nhịp; hai tờ đang nói hai nghĩa của cùng bốn kim |
| Luồng giữ dấu vết chăm | CU_BIS · CU_VNDCARE | BonKim mục 11 ghi chỗ hở: dấu vết chăm chưa có luồng giữ — việc ⑤ cần chỗ ghi |
| Pháp chế đọc việc ③ | Pháp chế · CGC | nháp kế hoạch đầu tư cho một khách chạm ranh tư vấn đầu tư; xác nhận ai được trình, trình thế nào |

## Ô TREO

| Hỏi gì | Mấy đường đi | Chọn sai thì hỏng ở đâu |
|---|---|---|
| Dữ liệu khách đi đường nào để agent chạy? Ví dụ: một CA giữ 300 khách, mỗi sáng cần trạng thái bốn kim của cả 300. | a · agent chạy trong hệ thống của nhà (Dplatform, app nghề của CA), KMS chỉ giữ tờ và gói · b · đội BIS xuất tệp mã hoá hằng ngày vào KMS như RISKMARGIN | a: cần đội IT nối agent vào hệ thống, chậm hơn một quý · b: dữ liệu khách nhiều lớp đi qua thư mục dùng chung, rủi ro lộ cao hơn hẳn ký quỹ; lộ ra khi có một tệp bị chép nhầm chỗ |

VNDIRECT · CU_VNDCARE · Lưu hành nội bộ
