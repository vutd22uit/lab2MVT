# SLIDE 4: THÔNG SỐ KỸ THUẬT 5G - IMT-2020

## 📋 Mục đích Slide
Trình bày chi tiết các thông số kỹ thuật chuẩn của 5G theo tiêu chuẩn ITU IMT-2020 và so sánh với 4G LTE.

## 🎯 Nội dung Chính

### Tiêu chuẩn 5G theo ITU IMT-2020

| Thông số | Chỉ tiêu 5G | So sánh 4G LTE |
|----------|-------------|----------------|
| **Peak Data Rate** | DL: 20 Gbps<br>UL: 10 Gbps | Tăng 20 lần |
| **User Data Rate** | DL: 100 Mbps<br>UL: 50 Mbps | Tăng 3-10 lần |
| **Latency** | 4ms (lý tưởng)<br>1ms (URLLC) | 4G: 20ms |
| **Connection Density** | 1 triệu thiết bị/km² | Tăng 10 lần |
| **Mobility** | 0-500 km/h | Hỗ trợ tàu cao tốc |
| **Spectral Efficiency** | DL: 30 bits/Hz<br>UL: 15 bits/Hz | Tăng 3 lần |
| **Energy Efficiency** | Smart power mode | Tiết kiệm năng lượng |

### Giải thích các thông số

#### 1. Peak Data Rate (Tốc độ đỉnh)
- **Downlink:** 20 Gbps (20,000 Mbps)
- **Uplink:** 10 Gbps
- **Ý nghĩa:** Tốc độ tối đa lý thuyết trong điều kiện lý tưởng
- **So sánh:** 4G LTE-A đạt ~1 Gbps

#### 2. User Experienced Data Rate (Tốc độ người dùng)
- **Downlink:** 100 Mbps (tối thiểu)
- **Uplink:** 50 Mbps
- **Ý nghĩa:** Tốc độ thực tế mà user trải nghiệm
- **Use case:** Stream 4K video mượt mà

#### 3. Latency (Độ trễ)
- **Thông thường:** 4ms
- **URLLC:** 1ms
- **4G LTE:** 20-30ms
- **Ý nghĩa:** Thời gian phản hồi của mạng
- **Quan trọng cho:** Gaming, xe tự lái, VR

#### 4. Connection Density (Mật độ kết nối)
- **5G:** 1,000,000 devices/km²
- **4G:** 100,000 devices/km²
- **Use case:** Smart city với hàng triệu sensors

#### 5. Mobility (Khả năng di động)
- **Phạm vi:** 0-500 km/h
- **Hỗ trợ:** Tàu cao tốc, máy bay hạ cánh
- **4G:** Giảm hiệu suất ở tốc độ cao

#### 6. Spectral Efficiency (Hiệu suất phổ tần)
- **Downlink:** 30 bits/Hz/cell
- **Uplink:** 15 bits/Hz/cell
- **Ý nghĩa:** Lượng data truyền được trên 1 Hz băng thông

#### 7. Energy Efficiency (Hiệu suất năng lượng)
- Smart sleep mode
- Tiết kiệm pin thiết bị khi không sử dụng
- Quan trọng cho IoT devices

## 🎨 Thiết kế Đề xuất

### Layout - Comparison Table
```
┌─────────────────────────────────────────┐
│   THÔNG SỐ KỸ THUẬT 5G - IMT-2020      │
│                                         │
│  ┌─────────────────────────────────┐   │
│  │ Thông số  │  5G    │  vs 4G     │   │
│  ├───────────┼────────┼────────────┤   │
│  │ Peak Rate │ 20Gbps │   ↑20x     │   │
│  │ Latency   │  1ms   │   ↓20x     │   │
│  │ Density   │  1M/km²│   ↑10x     │   │
│  │ ...       │ ...    │   ...      │   │
│  └─────────────────────────────────┘   │
└─────────────────────────────────────────┘
```

### Visual Elements
1. **Table:** Bảng so sánh rõ ràng với border
2. **Icons:** Mỗi thông số có icon tương ứng
   - Peak Rate: ⚡ Lightning bolt
   - Latency: ⏱️ Stopwatch
   - Density: 📡 Multiple devices
   - Mobility: 🚄 High-speed train
   - Efficiency: 📊 Bar chart
3. **Color coding:**
   - Cột 5G: Xanh dương
   - Cột so sánh: Xanh lá (tăng) / Cam (khác biệt)
4. **Arrows:** ↑ (tăng), ↓ (giảm), → (thay đổi)

### Alternative: Infographic Style
```
     ⚡ 20 Gbps          ⏱️ 1ms
     Peak Rate          Latency

     📡 1M/km²          🚄 500km/h
     Density            Mobility
```

## 💡 Gợi ý Trình bày

### Thời gian
- **Khuyến nghị:** 2.5-3 phút

### Kịch bản mẫu
> "Tiếp theo, chúng ta sẽ đi vào các thông số kỹ thuật cụ thể của 5G theo tiêu chuẩn IMT-2020 do ITU đưa ra.
>
> **Đầu tiên** là tốc độ đỉnh: 5G đạt 20 Gigabit/s cho downlink và 10 Gigabit/s cho uplink, nhanh hơn 4G tới 20 lần.
>
> **Thứ hai**, tốc độ thực tế người dùng trải nghiệm là tối thiểu 100 Mbps, đủ để stream video 4K mượt mà.
>
> **Đặc biệt quan trọng** là độ trễ: 5G giảm xuống chỉ còn 1 millisecond cho các ứng dụng URLLC, thấp hơn 4G tới 20 lần. Đây là yếu tố then chốt cho các ứng dụng như xe tự lái hay phẫu thuật từ xa.
>
> **Mật độ kết nối** cũng được cải thiện đáng kể: 1 triệu thiết bị trên mỗi kilomet vuông, tăng 10 lần so với 4G, đáp ứng nhu cầu IoT và smart city.
>
> **Về khả năng di động**, 5G hỗ trợ tốc độ lên tới 500 km/h, phù hợp với tàu cao tốc và cả máy bay đang hạ cánh.
>
> Cuối cùng, **hiệu suất phổ tần** và **hiệu suất năng lượng** cũng được cải thiện đáng kể."

### Kỹ thuật trình bày
- **Không đọc thuộc** tất cả số liệu
- **Chọn 3-4 thông số quan trọng nhất** để nhấn mạnh
- **So sánh cụ thể** với 4G để tạo contrast
- **Đưa ví dụ thực tế** cho mỗi thông số

## 📊 Data Visualization

### Recommended Charts

#### Option 1: Comparison Bar Chart
```
Peak Data Rate:
4G  |■■■■        | 1 Gbps
5G  |■■■■■■■■■■ | 20 Gbps

Latency:
4G  |■■■■■      | 20 ms
5G  |■          | 1 ms
```

#### Option 2: Speedometer/Gauge
- Hiển thị tốc độ 20 Gbps trên đồng hồ tốc độ
- Vùng đỏ cho 4G, vùng xanh cho 5G

#### Option 3: Icon Grid (Connection Density)
```
4G: [100 small dots] = 100K devices/km²
5G: [1000 small dots] = 1M devices/km²
```

## 📚 Thuật ngữ Kỹ thuật

### Peak vs Experienced Data Rate
- **Peak:** Tốc độ lý thuyết tối đa
- **Experienced:** Tốc độ thực tế trung bình
- **Tại sao khác nhau:** Điều kiện thực tế (khoảng cách, nhiễu, số users...)

### Latency Components
- **Radio latency:** Độ trễ vô tuyến
- **Core network latency:** Độ trễ mạng lõi
- **End-to-end latency:** Tổng độ trễ từ đầu đến cuối

### Connection Density
- **Nghĩa:** Số lượng thiết bị kết nối đồng thời
- **Per km²:** Trên diện tích 1 km vuông
- **Use case:** Dense urban areas, stadiums

## ✅ Checklist Hoàn thành

- [ ] Bảng so sánh đầy đủ 7 thông số
- [ ] Số liệu chính xác theo ITU IMT-2020
- [ ] So sánh rõ ràng với 4G
- [ ] Icons/visual elements cho mỗi metric
- [ ] Highlight các thông số quan trọng nhất
- [ ] Units rõ ràng (Gbps, ms, km/h...)
- [ ] Color coding hợp lý

## 📌 Ghi chú Quan trọng

> **Source Credibility:** Các con số này được lấy trực tiếp từ ITU-R Recommendation M.2083. Đảm bảo cite nguồn để tăng tính chuyên nghiệp.

> **Real-world vs Theoretical:** Lưu ý rằng đây là các chỉ tiêu kỹ thuật. Trong thực tế, tốc độ có thể thấp hơn tùy thuộc vào điều kiện triển khai.

## 🔗 Tài liệu Tham khảo

- ITU-R M.2083: "IMT Vision – Framework and overall objectives of the future development of IMT for 2020 and beyond"
- 3GPP TR 38.913: "Study on Scenarios and Requirements for Next Generation Access Technologies"

## 🔄 Liên kết

- **Slide trước:** [Slide 03 - Tổng quan về 5G](slide03_README.md)
- **Slide tiếp:** [Slide 05 - So sánh các thế hệ mạng](slide05_README.md)
- **Phần:** Đặc tính cơ bản 5G (2/5 slides)

---

**Cập nhật:** 2025-11-17
**Phần:** Đặc tính cơ bản 5G (15%)
**Thời lượng:** 2.5-3 phút
**Mức độ kỹ thuật:** ⭐⭐⭐☆☆
