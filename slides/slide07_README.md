# SLIDE 7: TIMELINE PHÁT TRIỂN & CHUẨN HÓA 5G

## 📋 Mục đích Slide
Trình bày lộ trình phát triển và các mốc quan trọng trong quá trình chuẩn hóa 5G, cũng như các tổ chức chịu trách nhiệm.

## 🎯 Nội dung Chính

### Lộ trình Phát triển 5G

| Năm | Sự kiện quan trọng |
|-----|-------------------|
| **2015** | ITU-R công bố vision IMT-2020 |
| **2016** | 3GPP bắt đầu nghiên cứu 5G NR |
| **2017** | 3GPP Release 15 NSA (Non-Standalone) |
| **2018** | 3GPP Release 15 SA (Standalone) hoàn thành |
| **2019** | Triển khai thương mại đầu tiên (Hàn Quốc, Mỹ) |
| **2020** | 3GPP Release 16 (5G Phase 2) |
| **2021-2024** | Mở rộng triển khai toàn cầu |
| **2025+** | 3GPP Release 17, 18 - 5G Advanced |

### Các Tổ chức Chuẩn hóa

#### Tổ chức Quốc tế
1. **ITU-R (International Telecommunication Union - Radio)**
   - Định nghĩa vision và requirements
   - IMT-2020 specifications

2. **3GPP (3rd Generation Partnership Project)**
   - Phát triển tiêu chuẩn kỹ thuật chi tiết
   - Release 15, 16, 17, 18...

#### Các Tổ chức Khu vực
- **ETSI:** European Telecommunications Standards Institute
- **FCC:** Federal Communications Commission (US)
- **IEEE:** Institute of Electrical and Electronics Engineers

#### Thành viên 3GPP
- **ARIB:** Association of Radio Industries and Businesses (Japan)
- **ATIS:** Alliance for Telecommunications Industry Solutions (US)
- **CCSA:** China Communications Standards Association
- **TSDSI:** Telecommunications Standards Development Society India
- **TTA:** Telecommunications Technology Association (Korea)
- **TTC:** Telecommunication Technology Committee (Japan)

## 🎨 Thiết kế Đề xuất

### Timeline Visualization
```
┌─────────────────────────────────────────────────┐
│    TIMELINE PHÁT TRIỂN & CHUẨN HÓA 5G           │
│                                                 │
│  2015 ──► 2017 ──► 2018 ──► 2019 ──► 2020+     │
│   │        │        │        │        │         │
│  ITU    Release  Release  First   Release      │
│  Vision   15 NSA  15 SA   Deploy    16         │
│                                                 │
│  [Logo ITU] [Logo 3GPP] [Map deployment]       │
└─────────────────────────────────────────────────┘
```

### Organization Structure
```
        ┌───────────┐
        │   ITU-R   │  ← Vision & Requirements
        └─────┬─────┘
              │
        ┌─────▼─────┐
        │   3GPP    │  ← Technical Specifications
        └─────┬─────┘
              │
    ┌─────────┼─────────┐
    ▼         ▼         ▼
  ARIB      ATIS      CCSA  ← Regional Partners
   TTA       TTC     TSDSI
```

## 💡 Gợi ý Trình bày

### Thời gian
- **Khuyến nghị:** 2 phút

### Kịch bản mẫu
> "Hãy cùng nhìn lại lộ trình phát triển 5G qua các mốc quan trọng.
>
> **Năm 2015**, ITU-R công bố vision cho IMT-2020 - tên gọi chính thức của 5G, định nghĩa các requirements cơ bản.
>
> **2016**, 3GPP bắt đầu nghiên cứu và phát triển 5G New Radio.
>
> **Cuối 2017**, 3GPP hoàn thành Release 15 ở chế độ NSA - Non-Standalone, cho phép 5G hoạt động kết hợp với 4G.
>
> **Giữa 2018**, Release 15 Standalone được hoàn thành, cho phép 5G hoạt động độc lập hoàn toàn.
>
> **2019** là năm quan trọng với các triển khai thương mại đầu tiên tại Hàn Quốc và Mỹ.
>
> **2020**, Release 16 ra mắt với nhiều tính năng mới, và từ đó đến nay 5G đã được triển khai rộng rãi toàn cầu.
>
> Về phía chuẩn hóa, ITU-R đóng vai trò định nghĩa vision, còn 3GPP phát triển các tiêu chuẩn kỹ thuật chi tiết thông qua các thành viên khu vực như ARIB ở Nhật, ATIS ở Mỹ, CCSA ở Trung Quốc."

### Kỹ thuật trình bày
- **Point to timeline** khi nói đến từng mốc
- **Explain NSA vs SA** briefly
- **Show logos** of standardization organizations
- **Global deployment map** nếu có

## 📊 Technical Details

### 3GPP Releases Breakdown

#### Release 15 (2017-2018)
- **Phase 1 của 5G**
- **NSA (Non-Standalone):**
  - 5G NR + 4G EPC Core
  - Quick deployment
- **SA (Standalone):**
  - 5G NR + 5G Core
  - Full 5G capabilities
- **Focus:** eMBB (broadband)

#### Release 16 (2020)
- **Phase 2 của 5G**
- **New features:**
  - URLLC enhancements
  - Industrial IoT
  - V2X (Vehicle-to-Everything)
  - Positioning services
  - Unlicensed spectrum (NR-U)

#### Release 17 (2022)
- **5G Advanced begins**
- **Features:**
  - NR sidelink enhancements
  - NTN (Non-Terrestrial Networks) - Satellite
  - Multi-SIM devices
  - Extended reality (XR)

#### Release 18 (2024+)
- **AI/ML for air interface**
- **Ambient IoT**
- **Enhanced positioning**

### NSA vs SA Architecture

**NSA (Non-Standalone):**
```
UE ←→ gNB ←→ eNB ←→ 4G EPC Core
```
- Pros: Faster deployment, leverage existing 4G
- Cons: Limited 5G features, still dependent on 4G

**SA (Standalone):**
```
UE ←→ gNB ←→ 5G Core
```
- Pros: Full 5G capabilities, network slicing
- Cons: Requires new core network infrastructure

## 📚 Thuật ngữ Giải thích

### ITU-R
- **International Telecommunication Union - Radiocommunication**
- Cơ quan chuyên môn của Liên Hợp Quốc
- Quản lý phổ tần vô tuyến toàn cầu
- Định nghĩa các thế hệ di động (IMT-2000 cho 3G, IMT-Advanced cho 4G, IMT-2020 cho 5G)

### 3GPP
- **3rd Generation Partnership Project**
- Không phải một tổ chức riêng lẻ mà là partnership của nhiều tổ chức
- Tạo ra technical specifications thông qua consensus
- Phát hành "Releases" định kỳ

### IMT-2020
- **International Mobile Telecommunications-2020**
- Tên chính thức của 5G theo ITU
- Định nghĩa 8 KPIs chính (peak rate, latency, etc.)

## 🌍 Global Deployment Timeline

### First Countries (2019)
- **Hàn Quốc:** April 2019 (SK Telecom, KT, LG U+)
- **Mỹ:** April 2019 (Verizon)
- **Thụy Sĩ:** May 2019 (Swisscom)

### Major Markets (2020-2021)
- **Trung Quốc:** Nov 2019 (China Mobile, China Unicom, China Telecom)
- **Nhật Bản:** March 2020
- **EU:** Throughout 2020
- **Việt Nam:** Trial 2020, Commercial 2024

## ✅ Checklist Hoàn thành

- [ ] Timeline rõ ràng từ 2015-2025
- [ ] Các mốc quan trọng được highlight
- [ ] Giải thích Release 15, 16, 17, 18
- [ ] Logos của ITU-R và 3GPP
- [ ] Liệt kê các tổ chức chuẩn hóa
- [ ] Bản đồ triển khai toàn cầu (optional)
- [ ] Phân biệt NSA vs SA

## 📌 Ghi chú Quan trọng

> **Standardization is ongoing:** 5G không "xong" mà vẫn đang được phát triển thông qua các Release mới. Release 18, 19 sẽ tiếp tục mang đến các tính năng mới.

> **Vietnam context:** Việt Nam bắt đầu thử nghiệm 5G từ 2020, nhưng chính thức thương mại hóa từ 10/2024 với Viettel. Có thể highlight điều này.

## 🎯 Key Takeaways

Đảm bảo audience hiểu:
1. **5G development took ~5 years** from vision (2015) to deployment (2019)
2. **3GPP releases continue:** 5G is not static, new features added regularly
3. **NSA was transition:** Most networks now moving to SA for full capabilities

## 🔄 Liên kết

- **Slide trước:** [Slide 06 - Kiến trúc mạng 5G](slide06_README.md)
- **Slide tiếp:** [Slide 08 - Công nghệ RF - Tổng quan](slide08_README.md)
- **Phần:** Đặc tính cơ bản 5G (5/5 slides)

---

**Cập nhật:** 2025-11-17
**Phần:** Đặc tính cơ bản 5G (15%)
**Thời lượng:** 2 phút
**Mức độ kỹ thuật:** ⭐⭐☆☆☆
