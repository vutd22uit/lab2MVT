# SLIDE 6: KIẾN TRÚC MẠNG 5G

## 📋 Mục đích Slide
Giới thiệu kiến trúc tổng thể của mạng 5G với hai thành phần chính: 5G NR và 5G Core Network.

## 🎯 Nội dung Chính

### Hai Thành phần Chính

#### 1. 5G New Radio (5G NR) - Radio Access Network
**Đặc điểm:**
- Giao diện vô tuyến mới hoàn toàn
- Linh hoạt, có khả năng mở rộng
- Hỗ trợ nhiều băng tần (sub-6GHz và mmWave)

**Chức năng:**
- Kết nối thiết bị người dùng (UE)
- Base station: gNB (gNodeB)
- Quản lý tài nguyên vô tuyến

#### 2. 5G NextGen Core Network (5G NG Core)
**Công nghệ nền tảng:**
- Software Defined Networking (SDN)
- Network Functions Virtualization (NFV)
- Network Slicing
- Service-Based Architecture (SBA)

**Chức năng:**
- Định tuyến data
- Quản lý session
- Policy control
- Kết nối với Internet/Services

### Kiến trúc End-to-End

```
[User Equipment] ←→ [5G NR / gNB] ←→ [5G Core Network] ←→ [Services/Internet]
      (UE)           (Base Station)      (NG Core)              (DN)
```

### So sánh với 4G LTE

| Component | 4G LTE | 5G |
|-----------|--------|-----|
| **Access Network** | eNodeB (eNB) | gNodeB (gNB) |
| **Core Network** | EPC (Evolved Packet Core) | 5GC (5G Core) |
| **Architecture** | Hardware-based | Cloud-native, Virtualized |
| **Flexibility** | Limited | High (Network Slicing) |

## 🎨 Thiết kế Đề xuất

### Architecture Diagram
```
┌─────────────────────────────────────────────────┐
│        KIẾN TRÚC MẠNG 5G                        │
│                                                 │
│  ┌──────┐       ┌──────┐      ┌──────────┐    │
│  │  UE  │◄─────►│ gNB  │◄────►│ 5G Core  │    │
│  │ 📱   │       │ 📡   │      │ ☁️       │    │
│  └──────┘       └──────┘      └──────────┘    │
│                                      │          │
│   User          5G NR         5G NG Core       │
│  Equipment    (Access Net)    (SDN/NFV)        │
│                                      ▼          │
│                              [Internet/Services]│
└─────────────────────────────────────────────────┘
```

### Two-Part Visualization
```
┌──────────────────┬──────────────────┐
│    5G NR         │   5G Core        │
│                  │                  │
│ • Multiple bands │ • SDN/NFV        │
│ • Flexible       │ • Slicing        │
│ • Scalable       │ • Cloud-native   │
│                  │                  │
│ [Antenna icon]   │ [Cloud icon]     │
└──────────────────┴──────────────────┘
```

## 💡 Gợi ý Trình bày

### Thời gian
- **Khuyến nghị:** 2-2.5 phút

### Kịch bản mẫu
> "Bây giờ chúng ta tìm hiểu về kiến trúc tổng thể của mạng 5G. Mạng 5G bao gồm hai thành phần chính:
>
> **Thứ nhất** là 5G New Radio, hay còn gọi là 5G NR, đây là phần Radio Access Network - mạng truy cập vô tuyến. 5G NR là giao diện vô tuyến hoàn toàn mới, linh hoạt và có khả năng mở rộng. Nó hỗ trợ nhiều băng tần khác nhau, từ sub-6 GHz cho coverage rộng, đến mmWave cho tốc độ cực cao. Base station trong 5G được gọi là gNB - g là viết tắt của generation.
>
> **Thứ hai** là 5G NextGen Core Network - mạng lõi thế hệ mới. Đây là điểm đổi mới lớn của 5G. Thay vì dựa trên hardware như 4G, 5G Core được xây dựng dựa trên Software Defined Networking và Network Functions Virtualization. Điều này cho phép triển khai Network Slicing - tạo nhiều mạng ảo trên cùng một hạ tầng vật lý, mỗi slice phục vụ một use case cụ thể.
>
> Luồng data đi từ User Equipment, qua 5G NR/gNB, vào 5G Core Network, và cuối cùng ra Internet hoặc các dịch vụ khác."

### Kỹ thuật trình bày
- **Draw attention** to the flow: UE → gNB → Core → Internet
- **Emphasize NEW aspects:** Cloud-native, virtualization
- **Compare briefly** with 4G architecture if audience is familiar
- **Use hand gestures** to show the flow of data

## 📊 Technical Details

### 5G NR Specifications
- **Frequency bands:**
  - FR1 (Frequency Range 1): sub-6 GHz (450 MHz - 6 GHz)
  - FR2 (Frequency Range 2): mmWave (24-52 GHz)
- **Channel bandwidth:**
  - FR1: up to 100 MHz
  - FR2: up to 400 MHz
- **Duplex modes:** FDD, TDD, SUL (Supplementary Uplink)

### 5G Core Network Functions
Key network functions (NFs):
- **AMF:** Access and Mobility Management Function
- **SMF:** Session Management Function
- **UPF:** User Plane Function
- **PCF:** Policy Control Function
- **UDM:** Unified Data Management
- **AUSF:** Authentication Server Function

### Service-Based Architecture (SBA)
- Network functions communicate via service-based interfaces
- RESTful APIs (HTTP/2)
- Microservices architecture
- Cloud-native principles

## 📚 Thuật ngữ Giải thích

### gNB vs eNB
- **eNB:** evolved NodeB (4G LTE base station)
- **gNB:** next generation NodeB (5G base station)
- **Khác biệt:** gNB hỗ trợ 5G NR, bandwidth rộng hơn, MIMO lớn hơn

### SDN (Software Defined Networking)
- **Định nghĩa:** Tách control plane và data plane
- **Lợi ích:** Linh hoạt, dễ quản lý, programmable
- **Ví dụ:** Có thể thay đổi routing policy bằng software

### NFV (Network Functions Virtualization)
- **Định nghĩa:** Chạy network functions trên virtual machines
- **Lợi ích:** Giảm chi phí hardware, dễ scale, nhanh deploy
- **Ví dụ:** Firewall, load balancer chạy trên VM thay vì hardware chuyên dụng

### Network Slicing
- **Định nghĩa:** Tạo nhiều logical networks trên cùng physical infrastructure
- **Use cases:** eMBB slice, URLLC slice, mMTC slice
- **Analogy:** Như nhiều làn đường (lanes) trên cùng một đường cao tốc

## 🎨 Visual Elements Suggestions

### Icons to use
- **UE:** 📱 Smartphone icon
- **gNB:** 📡 Cell tower / Antenna
- **5G Core:** ☁️ Cloud icon
- **Internet:** 🌐 Globe
- **SDN:** ⚙️ Gears / Settings
- **NFV:** 📦 Container / Virtual box
- **Slicing:** 🍕 Pizza slices (fun) or 🔪 Knife cutting

### Color scheme
- **5G NR:** Blue (#0099FF)
- **5G Core:** Green (#00CC66)
- **Connections:** Gray arrows
- **Highlight:** Orange for key concepts

## ✅ Checklist Hoàn thành

- [ ] Hai thành phần chính rõ ràng (5G NR + 5G Core)
- [ ] Sơ đồ end-to-end architecture
- [ ] Giải thích SDN, NFV, Network Slicing
- [ ] So sánh với 4G (eNB vs gNB, EPC vs 5GC)
- [ ] Icons phù hợp cho các components
- [ ] Flow arrows rõ ràng
- [ ] Technical terms có giải thích

## 📌 Ghi chú Quan trọng

> **Simplify for non-technical audience:** Nếu audience không technical, có thể skip các acronyms như AMF, SMF. Chỉ cần nhấn mạnh "cloud-based" và "flexible".

> **Focus on benefits:** Thay vì liệt kê quá nhiều technical terms, focus vào benefits: faster deployment, lower cost, support multiple use cases.

## 🎯 Key Takeaways

Đảm bảo audience hiểu:
1. **5G has two main parts:** Radio access (5G NR) and Core network (5G Core)
2. **5G Core is cloud-native:** Unlike 4G, it's software-based and virtualized
3. **Network Slicing enables:** Multiple virtual networks for different use cases

## 🔄 Liên kết

- **Slide trước:** [Slide 05 - So sánh các thế hệ mạng](slide05_README.md)
- **Slide tiếp:** [Slide 07 - Timeline phát triển 5G](slide07_README.md)
- **Phần:** Đặc tính cơ bản 5G (4/5 slides)

---

**Cập nhật:** 2025-11-17
**Phần:** Đặc tính cơ bản 5G (15%)
**Thời lượng:** 2-2.5 phút
**Mức độ kỹ thuật:** ⭐⭐⭐☆☆
