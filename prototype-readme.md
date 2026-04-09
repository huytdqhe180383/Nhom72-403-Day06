# Prototype Readme – Vietnam Airlines NEO

**Level:** Working

NEO là prototype web chat cho Vietnam Airlines, tập trung vào 4 luồng chính: tìm vé đa điều kiện, tư vấn nhóm/phức tạp, check-in online bằng PNR/PDF và chăm sóc chủ động cho hội viên Lotusmiles. Prototype hiện chạy theo mô hình VNA-only, dùng dữ liệu cục bộ và backend FastAPI để demo an toàn các luồng đặt vé, check-in và phản hồi dịch vụ

**Link prototype:** 

## Tools và API đã dùng

- Frontend: HTML, CSS, Vanilla JavaScript
- Backend: FastAPI, uvicorn
- Dữ liệu cục bộ: `mock_data/*.csv`, `logs/chat_history.jsonl`, `logs/service_feedback.db`
- API chính: `/api/chat`, `/api/chat/stream`, `/api/flights/search`, `/api/flights/from-text`, `/api/session/bind-user`, `/api/history/{session_id}`, `/api/checkin/pnr`, `/api/checkin/seatmap`, `/api/checkin/select-seat`, `/api/checkin/upload`, `/api/feedback`
- UI/State: `localStorage`, shared chat widget, tickets page, check-in page, feedback card, clear-history button

## Phân công (draft)

| Hạng mục | Người phụ trách |
|---|---|
| Tổng hợp yêu cầu & viết spec | [Tôi] |
| Frontend chat / tickets / check-in | [Tôi / thêm tên sau] |
| Backend API & dữ liệu cục bộ | [Tôi / thêm tên sau] |
| Test & chỉnh sửa nội dung | [Tôi / thêm tên sau] |
