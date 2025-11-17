# MẠNG DI ĐỘNG 5G
## Bài thực hành Lab02 - Công nghệ Mạng Viễn Thông

---

## OUTLINE PRESENTATION (30 SLIDES)

### PHẦN 1: GIỚI THIỆU (2 slides)
### PHẦN 2: ĐẶC TÍNH CƠ BẢN 5G (5 slides - 15%)
### PHẦN 3: CÔNG NGHỆ MỚI TRONG 5G (9 slides - 30%)
### PHẦN 4: DỊCH VỤ TRÊN MẠNG 5G (6 slides - 20%)
### PHẦN 5: TRIỂN KHAI TẠI VIỆT NAM (5 slides - 15%)
### PHẦN 6: KẾT LUẬN (3 slides)

---

# SLIDE 1: TRANG BÌA
## MẠNG DI ĐỘNG 5G

**Nội dung:**
- Tìm hiểu công nghệ mạng 5G
- Ứng dụng và triển khai tại Việt Nam

**Nhóm:** [Tên nhóm]
**GVHD:** [Tên giảng viên]

**Gợi ý hình ảnh:**
- Logo 5G với hiệu ứng công nghệ hiện đại
- Hình nền mạng lưới kết nối toàn cầu
- Màu sắc: Xanh dương, trắng (công nghệ hiện đại)

---

# SLIDE 2: MỤC LỤC

**Nội dung:**

1. **Đặc tính cơ bản của mạng 5G**
   - Specifications & yêu cầu kỹ thuật
   - So sánh với 3G, 4G

2. **Công nghệ mới trong 5G**
   - Công nghệ phần RF (Radio Frequency)
   - Công nghệ phần Core Network

3. **Dịch vụ trên mạng 5G**
   - 5+ dịch vụ tiêu biểu

4. **Triển khai tại Việt Nam**
   - Tình trạng triển khai
   - Băng tần & tốc độ thực tế

**Gợi ý hình ảnh:**
- Icon cho từng phần
- Timeline hoặc roadmap

---

# PHẦN 2: ĐẶC TÍNH CƠ BẢN CỦA MẠNG 5G (15%)

---

# SLIDE 3: TỔNG QUAN VỀ 5G

**5G - Thế hệ thứ 5 của mạng di động**

**Định nghĩa:**
- 5G không chỉ là bản nâng cấp từ 4G
- Là hệ thống hoàn toàn mới, được thiết kế dựa trên nhu cầu ứng dụng cụ thể
- Mạng lưới kết nối phổ biến (Ubiquitous connectivity)

**Đặc điểm nổi bật:**
- ✅ Tốc độ cực cao (Enhanced Mobile Broadband - eMBB)
- ✅ Độ trễ cực thấp (Ultra-Reliable Low-Latency - URLLC)
- ✅ Kết nối hàng loạt thiết bị (Massive Machine-Type Communications - mMTC)

**Gợi ý hình ảnh:**
- Infographic 3 đặc điểm chính của 5G
- Biểu đồ tam giác 5G use cases (eMBB, URLLC, mMTC)
- Logo các tổ chức chuẩn hóa: 3GPP, ITU

---

# SLIDE 4: THÔNG SỐ KỸ THUẬT 5G - IMT-2020

**Tiêu chuẩn 5G theo ITU IMT-2020:**

| Thông số | Chỉ tiêu 5G | So sánh 4G LTE |
|----------|-------------|----------------|
| **Peak Data Rate** | Downlink: 20 Gbps<br>Uplink: 10 Gbps | Tăng 20 lần |
| **User Data Rate** | Downlink: 100 Mbps<br>Uplink: 50 Mbps | Tăng 3-10 lần |
| **Latency** | 4ms (lý tưởng)<br>1ms (URLLC) | 4G: 20ms |
| **Connection Density** | 1 triệu thiết bị/km² | Tăng 10 lần |
| **Mobility** | 0-500 km/h | Hỗ trợ tàu cao tốc |
| **Spectral Efficiency** | DL: 30 bits/Hz<br>UL: 15 bits/Hz | Tăng 3 lần |
| **Energy Efficiency** | Tiết kiệm năng lượng khi không sử dụng | Smart power mode |

**Gợi ý hình ảnh:**
- Bảng so sánh với màu sắc nổi bật
- Icon minh họa cho từng thông số
- Biểu đồ cột so sánh 4G vs 5G

---

# SLIDE 5: SO SÁNH CÁC THẾ HỆ MẠNG DI ĐỘNG

**Tiến hóa từ 1G đến 5G:**

| Thế hệ | Thời kỳ | Công nghệ | Tốc độ | Ứng dụng chính |
|--------|---------|-----------|--------|----------------|
| **1G** | 1980s | Analog (AMPS) | 2.4 Kbps | Thoại analog |
| **2G** | 1990s | GSM, CDMA | 64 Kbps | Thoại số, SMS |
| **2.5G** | 2000s | GPRS, EDGE | 384 Kbps | Email, WAP |
| **3G** | 2000s | UMTS, HSPA | 2-14 Mbps | Video call, Mobile Internet |
| **4G** | 2010s | LTE, LTE-A | 100 Mbps - 1 Gbps | HD Video, Gaming |
| **5G** | 2020s | 5G NR | 1-20 Gbps | IoT, AR/VR, Autonomous |

**Điểm khác biệt của 5G:**
- 🔹 **Tốc độ:** Nhanh hơn 4G 10-100 lần
- 🔹 **Độ trễ:** Giảm từ 20ms xuống 1-4ms
- 🔹 **Dung lượng:** Kết nối 1 triệu thiết bị/km²
- 🔹 **Hiệu suất năng lượng:** Tiết kiệm pin hơn

**Gợi ý hình ảnh:**
- Timeline evolution 1G → 5G
- Biểu đồ so sánh tốc độ (bar chart)
- Hình minh họa use cases từng thế hệ

---

# SLIDE 6: KIẾN TRÚC MẠNG 5G

**Hai thành phần chính:**

### 1. **5G New Radio (5G NR) - Radio Access Network**
- Giao diện vô tuyến mới hoàn toàn
- Linh hoạt, có khả năng mở rộng
- Hỗ trợ nhiều băng tần (sub-6GHz và mmWave)

### 2. **5G NextGen Core Network (5G NG Core)**
- Core network thế hệ mới
- Dựa trên Software Defined Networking (SDN)
- Network Functions Virtualization (NFV)
- Network Slicing

**Mối quan hệ:**
```
[User Equipment (UE)] ←→ [5G NR / gNB] ←→ [5G Core Network] ←→ [Services/Internet]
```

**Gợi ý hình ảnh:**
- Sơ đồ kiến trúc 5G end-to-end
- Hình minh họa 5G NR và Core Network
- So sánh kiến trúc 4G vs 5G

---

# SLIDE 7: TIMELINE PHÁT TRIỂN & CHUẨN HÓA 5G

**Lộ trình phát triển 5G:**

| Năm | Sự kiện |
|-----|---------|
| **2015** | ITU-R công bố vision IMT-2020 |
| **2016** | 3GPP bắt đầu nghiên cứu 5G NR |
| **2017** | 3GPP Release 15 NSA (Non-Standalone) |
| **2018** | 3GPP Release 15 SA (Standalone) hoàn thành |
| **2019** | Triển khai thương mại đầu tiên (Hàn Quốc, Mỹ) |
| **2020** | 3GPP Release 16 (5G Phase 2) |
| **2021-2024** | Mở rộng triển khai toàn cầu |
| **2025+** | 3GPP Release 17, 18 - Nâng cấp 5G Advanced |

**Các tổ chức chuẩn hóa:**
- **ITU-R (ITU-T, ITU-R):** Chuẩn quốc tế
- **3GPP:** Phát triển tiêu chuẩn kỹ thuật
- **ETSI, IEEE, FCC:** Chuẩn khu vực
- **ARIB, ATIS, CCSA, TSDSI, TTA, TTC:** Thành viên 3GPP

**Gợi ý hình ảnh:**
- Timeline visualization
- Logo các tổ chức chuẩn hóa
- Bản đồ triển khai 5G toàn cầu

---

# PHẦN 3: CÔNG NGHỆ MỚI TRONG 5G (30%)

---

# SLIDE 8: CÔNG NGHỆ PHẦN RF - TỔNG QUAN

**Radio Frequency Technologies trong 5G:**

### **1. Millimeter Wave (mmWave)**
- Tần số: 24-100 GHz (hiện tại: 24-40 GHz)
- Băng thông: Rất rộng (1-2 GHz)
- Tốc độ: Cực cao (multi-Gbps)

### **2. Sub-6 GHz**
- Tần số: 3.3-4.2 GHz, 2.5-2.6 GHz
- Phủ sóng: Tốt hơn mmWave
- Cân bằng tốc độ và coverage

### **3. Massive MIMO**
- Nhiều anten (hàng chục đến hàng trăm)
- Beamforming & Beamsteering
- Tăng dung lượng và hiệu suất

**Gợi ý hình ảnh:**
- Biểu đồ phổ tần 5G
- So sánh coverage mmWave vs Sub-6GHz
- Hình minh họa Massive MIMO antenna

---

# SLIDE 9: MILLIMETER WAVE (mmWave)

**Công nghệ sóng milimet - Đột phá của 5G:**

### **Đặc điểm:**
- **Tần số:** 24 GHz - 100 GHz (5G: 24-40 GHz, 57-71 GHz)
- **Băng thông:** Cực rộng (400 MHz - 2 GHz)
- **Tốc độ:** Lên đến 20 Gbps

### **Ưu điểm:**
- ✅ Băng thông khổng lồ → tốc độ cực cao
- ✅ Phổ tần sẵn có nhiều
- ✅ Tái sử dụng tần số tốt (coverage nhỏ)

### **Thách thức:**
- ❌ Khoảng cách truyền ngắn (200-300m)
- ❌ Bị cản trở bởi tường, mưa
- ❌ Cần beamforming để tập trung năng lượng
- ❌ Chi phí triển khai cao

### **Ứng dụng:**
- Dense urban areas (đô thị đông đúc)
- Indoor hotspots (sân bay, stadium)
- Fixed Wireless Access

**Gợi ý hình ảnh:**
- Biểu đồ propagation mmWave
- So sánh coverage area: sub-6GHz vs mmWave
- Hình ảnh small cell deployment
- Đồ thị ảnh hưởng của mưa lên signal

---

# SLIDE 10: MASSIVE MIMO & BEAMFORMING

**Massive MIMO (Multiple Input Multiple Output):**

### **Công nghệ:**
- **Số lượng anten:** 64, 128, hoặc 256 anten
- **MU-MIMO:** Multi-User MIMO - phục vụ nhiều user đồng thời
- **Spatial Multiplexing:** Tách biệt users theo không gian

### **Beamforming & Beamsteering:**
- **Beamforming:** Tập trung sóng vào hướng cụ thể
- **Beamsteering:** Điều khiển hướng beam động
- **Lợi ích:**
  - Tăng cường độ tín hiệu đến user
  - Giảm nhiễu cho users khác
  - Tăng dung lượng hệ thống

### **Quy trình MU-MIMO:**
1. gNB gửi CSI-RS (Channel State Information)
2. UE phản hồi channel information
3. gNB tính toán pre-coding matrix
4. Truyền tín hiệu với phase offset tối ưu

**Gợi ý hình ảnh:**
- Sơ đồ Massive MIMO array
- Visualization beamforming (các chùm sóng)
- So sánh: No beamforming vs With beamforming
- Hình ảnh gNB base station với massive MIMO

---

# SLIDE 11: 5G WAVEFORM - CP-OFDM & DFT-S-OFDM

**Dạng sóng 5G New Radio:**

### **1. CP-OFDM (Cyclic Prefix OFDM)**
- **Downlink:** CP-OFDM
- **Uplink:** CP-OFDM và DFT-S-OFDM

### **Đặc điểm:**
- Kế thừa từ 4G LTE nhưng được tối ưu hóa
- Subcarrier spacing linh hoạt: 15 kHz × 2^μ
  - μ = 0: 15 kHz (giống LTE)
  - μ = 1: 30 kHz
  - μ = 2: 60 kHz
  - μ = 3: 120 kHz
  - μ = 4: 240 kHz (mmWave)

### **Ưu điểm:**
- ✅ Hiệu suất phổ tần cao
- ✅ Chống fading tốt
- ✅ Linh hoạt với nhiều băng tần
- ✅ Hỗ trợ channel bandwidth lớn (đến 400 MHz)

### **Scalable Numerology:**
- Subcarrier spacing rộng hơn → chống phase noise tốt hơn ở mmWave
- FFT size scale theo bandwidth → không tăng complexity

**Gợi ý hình ảnh:**
- Biểu đồ OFDM subcarriers
- Bảng so sánh subcarrier spacing
- So sánh CP-OFDM vs DFT-S-OFDM
- Cyclic Prefix illustration

---

# SLIDE 12: 5G MODULATION SCHEMES

**Các kỹ thuật điều chế trong 5G:**

### **Modulation Schemes:**
| Scheme | Bits/symbol | Use case |
|--------|-------------|----------|
| **QPSK** | 2 | Low SNR, coverage |
| **16-QAM** | 4 | Medium SNR |
| **64-QAM** | 6 | High SNR, high speed |
| **256-QAM** | 8 | Very high SNR, peak rate |

### **Adaptive Modulation:**
- Hệ thống tự động chuyển đổi scheme phù hợp
- Dựa trên:
  - Signal-to-Noise Ratio (SNR)
  - Channel conditions
  - Distance from base station

### **Peak-to-Average Power Ratio (PAPR):**
- PAPR thấp → hiệu suất pin tốt hơn
- 5G optimization: cân bằng PAPR và spectral efficiency

**Gợi ý hình ảnh:**
- Constellation diagram: QPSK, 16-QAM, 64-QAM, 256-QAM
- Biểu đồ adaptive modulation
- Graph: SNR vs Modulation scheme

---

# SLIDE 13: 5G MULTIPLE ACCESS - OFDMA

**Công nghệ đa truy nhập 5G:**

### **OFDMA (Orthogonal Frequency Division Multiple Access)**
- Kế thừa từ 4G LTE
- Chia subcarriers cho nhiều users

### **Các phương án khác được nghiên cứu:**
- **SCMA:** Sparse Code Multiple Access
- **NOMA:** Non-Orthogonal Multiple Access
- **PDMA, MUSA, IDMA**

### **Resource Block Allocation:**
- Flexible Resource Grid
- Dynamic scheduling
- Low latency scheduling

### **Mini-slot transmission:**
- Truyền dữ liệu trong thời gian ngắn hơn
- Giảm latency
- Hỗ trợ URLLC applications

**Gợi ý hình ảnh:**
- Sơ đồ OFDMA resource allocation
- Time-Frequency grid
- So sánh scheduling: 4G vs 5G
- Mini-slot vs regular slot

---

# SLIDE 14: CÔNG NGHỆ CORE NETWORK - 5G NG CORE

**5G NextGen Core Network:**

### **Kiến trúc mới:**

**1. Software Defined Networking (SDN)**
- Tách control plane và data plane
- Quản lý mạng bằng software
- Linh hoạt, dễ nâng cấp

**2. Network Functions Virtualization (NFV)**
- Các chức năng mạng chạy trên phần mềm
- Triển khai trên hardware thông dụng
- Giảm chi phí, tăng tính linh hoạt

**3. Network Slicing**
- Tạo nhiều mạng ảo trên cùng hạ tầng vật lý
- Mỗi slice phục vụ một use case cụ thể:
  - **eMBB slice:** High bandwidth
  - **URLLC slice:** Ultra-low latency
  - **mMTC slice:** Massive IoT

**Gợi ý hình ảnh:**
- Sơ đồ 5G Core architecture
- SDN/NFV illustration
- Network slicing diagram (3 slices song song)
- So sánh 4G EPC vs 5G Core

---

# SLIDE 15: NETWORK SLICING CHI TIẾT

**Network Slicing - Công nghệ then chốt:**

### **Khái niệm:**
- Chia mạng vật lý thành nhiều mạng logic độc lập
- Mỗi slice có cấu hình riêng
- Cùng hạ tầng phục vụ nhiều use cases khác nhau

### **Các loại slices:**

| Slice Type | Latency | Bandwidth | Reliability | Use Case |
|------------|---------|-----------|-------------|----------|
| **eMBB** | Medium | Very High | Medium | Video streaming, VR/AR |
| **URLLC** | Ultra-Low (1ms) | Low-Medium | 99.999% | Autonomous cars, Remote surgery |
| **mMTC** | High | Very Low | Low-Medium | IoT sensors, Smart city |

### **Lợi ích:**
- ✅ Tối ưu hóa tài nguyên
- ✅ Cô lập giữa các services
- ✅ Flexibility & Scalability
- ✅ Monetization opportunities

**Gợi ý hình ảnh:**
- Diagram: Physical network → Multiple slices
- 3 use cases với 3 slices khác nhau
- Resource allocation visualization
- Real-world example (factory, hospital, entertainment)

---

# SLIDE 16: CÁC CÔNG NGHỆ BỔ TRỢ KHÁC

**Các kỹ thuật nâng cao khác trong 5G:**

### **1. Small Cells & Dense Networks**
- Triển khai nhiều cells nhỏ
- Tăng capacity, coverage
- Frequency reuse tốt hơn

### **2. Carrier Aggregation**
- Kết hợp nhiều carrier thành bandwidth lớn
- Tăng tốc độ peak data rate
- Hỗ trợ inter-band và intra-band

### **3. Dual Connectivity**
- Kết nối đồng thời 4G và 5G (NSA mode)
- Smooth migration path
- Tận dụng coverage 4G + speed 5G

### **4. Edge Computing (MEC)**
- Xử lý dữ liệu tại edge of network
- Giảm latency
- Hỗ trợ real-time applications

### **5. Spectrum Sharing**
- Dynamic Spectrum Sharing (DSS)
- 4G và 5G dùng chung băng tần
- Tối ưu hóa sử dụng phổ tần

**Gợi ý hình ảnh:**
- Small cell deployment scenario
- Carrier aggregation illustration
- NSA vs SA architecture
- MEC architecture diagram

---

# PHẦN 4: DỊCH VỤ TRÊN MẠNG 5G (20%)

---

# SLIDE 17: 5G USE CASES - TỔNG QUAN

**Ba nhóm ứng dụng chính:**

### **1. Enhanced Mobile Broadband (eMBB)**
- Băng thông cực rộng
- Video 4K/8K, VR/AR, Cloud gaming

### **2. Ultra-Reliable Low-Latency Communications (URLLC)**
- Độ trễ < 1ms
- Độ tin cậy 99.999%
- Autonomous vehicles, Industrial automation

### **3. Massive Machine-Type Communications (mMTC)**
- Kết nối hàng loạt thiết bị IoT
- 1 triệu devices/km²
- Smart city, Agriculture, Asset tracking

**Gợi ý hình ảnh:**
- Triangle diagram: eMBB, URLLC, mMTC
- Icons cho các use cases
- Real-world photos cho mỗi nhóm

---

# SLIDE 18: DỊCH VỤ 1 - AUTONOMOUS VEHICLES

**Xe tự lái & V2X Communications:**

### **Vehicle-to-Everything (V2X):**
- **V2V:** Vehicle to Vehicle
- **V2I:** Vehicle to Infrastructure
- **V2P:** Vehicle to Pedestrian
- **V2N:** Vehicle to Network

### **Yêu cầu:**
- Latency < 1ms (URLLC)
- Reliability 99.999%
- Real-time decision making

### **Lợi ích:**
- 🚗 Giảm tai nạn giao thông
- 🚗 Tối ưu lưu lượng, giảm tắc nghẽn
- 🚗 Tiết kiệm năng lượng, giảm phát thải
- 🚗 Tăng năng suất vận tải

### **Công nghệ 5G hỗ trợ:**
- Ultra-low latency communication
- High bandwidth cho sensor data
- Edge computing for real-time processing
- Network slicing (URLLC slice)

**Gợi ý hình ảnh:**
- Hình ảnh xe tự lái
- Diagram V2X communication
- Infographic: Safety statistics
- Smart traffic scenario

---

# SLIDE 19: DỊCH VỤ 2 - SMART CITIES

**Thành phố thông minh:**

### **Các thành phần:**

**1. Smart Traffic Management**
- Camera giám sát HD real-time
- Tín hiệu đèn giao thông thông minh
- Parking guidance system

**2. Smart Utilities**
- Smart grid - lưới điện thông minh
- Water management
- Waste management (rác thải)

**3. Public Safety**
- Video surveillance (giám sát an ninh)
- Emergency response system
- Environmental monitoring (không khí, tiếng ồn)

**4. Smart Lighting**
- Đèn đường tự động điều chỉnh
- Tiết kiệm năng lượng

### **Yêu cầu 5G:**
- Massive IoT connectivity (mMTC)
- High bandwidth for video
- Low power consumption

### **Lợi ích:**
- Tiết kiệm năng lượng 30-40%
- Giảm phát thải CO2
- Cải thiện chất lượng sống
- Tối ưu hóa tài nguyên

**Gợi ý hình ảnh:**
- Smart city panorama
- Icons của các services
- Before/After comparison
- Real deployment (Barcelona, Singapore...)

---

# SLIDE 20: DỊCH VỤ 3 - INDUSTRIAL IoT & INDUSTRY 4.0

**Nhà máy thông minh & Tự động hóa:**

### **Ứng dụng:**

**1. Smart Manufacturing**
- Robotic automation
- Predictive maintenance (bảo trì dự đoán)
- Quality control tự động
- Digital twin

**2. Remote Control**
- Remote equipment operation
- Haptic feedback control
- Collaborative robots (Cobots)

**3. Asset Tracking**
- Real-time location tracking
- Inventory management
- Supply chain optimization

### **Yêu cầu:**
- Ultra-low latency (URLLC) cho control
- High reliability 99.999%
- Massive sensor connectivity
- Private 5G networks

### **Lợi ích:**
- ⚙️ Tăng năng suất 25-40%
- ⚙️ Giảm downtime
- ⚙️ Tiết kiệm chi phí vận hành
- ⚙️ Flexibility & agility

**Gợi ý hình ảnh:**
- Smart factory floor
- Robotic arms với 5G connectivity
- Predictive maintenance dashboard
- Industry 4.0 infographic

---

# SLIDE 21: DỊCH VỤ 4 - ENHANCED MOBILE ENTERTAINMENT

**Giải trí di động nâng cao:**

### **1. AR/VR/XR Applications**
- **Virtual Reality:** Gaming, Training, Education
- **Augmented Reality:** Shopping, Navigation, Social media
- **Extended Reality:** Mixed experiences

**Yêu cầu:**
- Bandwidth: 50-200 Mbps/user
- Latency: < 10ms
- Tỷ lệ khung hình cao (90-120 fps)

### **2. Cloud Gaming**
- Gaming on-demand không cần console
- Stream 4K/8K gaming
- Multi-player real-time

**Yêu cầu:**
- Tốc độ: 25-50 Mbps
- Latency: < 20ms
- Stable connection

### **3. Ultra-HD Video Streaming**
- 4K/8K video streaming
- 360-degree video
- Live event streaming

**Yêu cầu:**
- 4K: 25 Mbps
- 8K: 100 Mbps

### **4. Immersive Sports & Concerts**
- Multi-angle views
- VR stadium experience
- Interactive content

**Gợi ý hình ảnh:**
- VR headset user
- Cloud gaming on smartphone
- 8K video streaming
- Stadium with 5G coverage

---

# SLIDE 22: DỊCH VỤ 5 - HEALTHCARE & TELEMEDICINE

**Y tế thông minh:**

### **1. Remote Surgery (Phẫu thuật từ xa)**
- Bác sĩ điều khiển robot phẫu thuật từ xa
- Haptic feedback real-time
- **Yêu cầu:** Latency < 1ms, Reliability 99.9999%

### **2. Remote Patient Monitoring**
- Wearable health devices
- Continuous vital signs monitoring
- Alert system tự động
- **Yêu cầu:** Massive IoT, Low power

### **3. Telemedicine & Consultation**
- Video consultation HD
- Real-time diagnosis
- AI-assisted diagnosis
- **Yêu cầu:** High bandwidth, Stable connection

### **4. Ambulance Connectivity**
- Live video từ xe cứu thương
- Real-time patient data transmission
- Pre-hospital treatment guidance
- **Yêu cầu:** Mobility, Low latency

### **5. Medical Training**
- VR/AR surgical training
- Remote education
- Simulation platforms

**Lợi ích:**
- 🏥 Tiếp cận y tế ở vùng xa
- 🏥 Giảm chi phí
- 🏥 Chăm sóc 24/7
- 🏥 Chất lượng điều trị tốt hơn

**Gợi ý hình ảnh:**
- Remote surgery setup
- Wearable health devices
- Telemedicine consultation
- Connected ambulance

---

# SLIDE 23: CÁC DỊCH VỤ KHÁC

**Thêm các ứng dụng 5G:**

### **6. Smart Agriculture (Nông nghiệp thông minh)**
- IoT sensors (độ ẩm, nhiệt độ, pH)
- Drone monitoring
- Automated irrigation
- Precision farming

### **7. Retail & Shopping**
- AR virtual try-on
- Smart checkout
- Inventory management
- Personalized advertising

### **8. Education**
- Virtual classrooms
- Remote labs
- AR/VR learning experiences
- Interactive content

### **9. Energy & Utilities**
- Smart grid management
- Renewable energy optimization
- Real-time monitoring
- Demand response

### **10. Public Safety & Emergency**
- First responder communications
- Disaster management
- Drone surveillance
- Real-time coordination

**Gợi ý hình ảnh:**
- Grid layout với icons
- Photos cho mỗi use case
- Statistics/numbers

---

# PHẦN 5: TRIỂN KHAI 5G TẠI VIỆT NAM (15%)

---

# SLIDE 24: TÌNH TRẠNG TRIỂN KHAI 5G VIỆT NAM

**Tổng quan triển khai:**

### **Lộ trình:**
- **3/2024:** Đấu giá băng tần 5G
- **10/2024:** Viettel ra mắt 5G thương mại (đầu tiên)
- **12/2024:** VNPT thương mại hóa 5G
- **3/2025:** MobiFone chính thức ra mắt 5G

### **Hiện trạng (tính đến 3/2025):**

**Việt Nam đã chính thức bước vào kỷ nguyên 5G!**

| Nhà mạng | Trạng thái | Thời điểm launch |
|----------|-----------|------------------|
| **Viettel** | ✅ Đã triển khai | 15/10/2024 |
| **VNPT** | ✅ Đã triển khai | 12/2024 |
| **MobiFone** | ✅ Đã triển khai | 3/2025 |

### **Phủ sóng:**
- **Viettel:** 6,500+ trạm phát sóng, 63/63 tỉnh thành
- **VNPT:** 63 tỉnh thành, 705 quận/huyện
- **MobiFone:** Đang mở rộng nhanh chóng

**Mục tiêu quốc gia:**
- **2025:** Tốc độ trung bình 100 Mbps
- **2030:** Phủ sóng 99% dân số

**Gợi ý hình ảnh:**
- Timeline triển khai
- Logo 3 nhà mạng
- Bản đồ Việt Nam với coverage
- Photos lễ ra mắt 5G

---

# SLIDE 25: BĂNG TẦN 5G TẠI VIỆT NAM

**Phân bổ băng tần 5G:**

### **Đấu giá băng tần (tháng 3/2024):**

| Nhà mạng | Băng tần | Giá trúng đấu |
|----------|----------|---------------|
| **Viettel** | 2.5 - 2.6 GHz (B1)<br>+ 700 MHz (5/2025) | 7,533 tỷ VNĐ<br>+ ~2,000 tỷ |
| **VNPT (VinaPhone)** | 3.7 - 3.8 GHz (C2) | 2,581 tỷ VNĐ |
| **MobiFone** | 3.8 - 3.9 GHz (C3) | ~2,500 tỷ VNĐ |

### **Đặc điểm băng tần:**

**1. Băng 700 MHz (Viettel - "Băng tần vàng")**
- ✅ Coverage rộng, xuyên tường tốt
- ✅ Phù hợp vùng nông thôn, miền núi
- ❌ Băng thông hạn chế

**2. Băng 2.5-2.6 GHz**
- ⚖️ Cân bằng coverage và capacity
- ⚖️ Phù hợp đô thị và ngoại thành

**3. Băng 3.7-3.9 GHz (Mid-band)**
- ✅ Băng thông rộng
- ✅ Tốc độ cao
- ❌ Coverage ngắn hơn 700MHz

### **Kế hoạch tương lai:**
- Nghiên cứu mmWave (24-40 GHz) cho hotspots
- Mở rộng băng tần mid-band

**Gợi ý hình ảnh:**
- Biểu đồ phổ tần số
- So sánh coverage các băng tần
- Bảng đấu giá với số tiền
- Infographic đặc điểm từng băng tần

---

# SLIDE 26: TỐC ĐỘ THỰC TẾ & THUÊ BAO

**Hiệu suất mạng 5G Việt Nam:**

### **Tốc độ thực tế (tính đến 2/2025):**

| Chỉ số | Trung bình VN | Viettel | VNPT | MobiFone |
|--------|---------------|---------|------|----------|
| **Download** | 187.58 Mbps | 226.27 Mbps | 157.17 Mbps | Đến 1.5 Gbps |
| **Upload** | 34.87 Mbps | 29.83 Mbps | 45.5 Mbps | - |
| **So với 4G** | 10-15 lần | 15-20 lần | 10-12 lần | 10-15 lần |

### **Số lượng thuê bao (2/2025):**
- **Viettel:** 5.5 triệu thuê bao 5G
- **VNPT:** ~3 triệu thuê bao 5G
- **Tổng cộng:** ~8.5 triệu+ thuê bao 5G

### **Tốc độ tăng trưởng:**
- Tăng trưởng nhanh từ 10/2024
- Dự kiến đạt 15-20 triệu thuê bao cuối 2025

### **Giá cước:**
- Các gói 5G từ 135,000 - 500,000 VNĐ/tháng
- Data unlimited hoặc dung lượng lớn
- Miễn phí nâng cấp từ 4G lên 5G (có điều kiện)

**Gợi ý hình ảnh:**
- Biểu đồ tốc độ (bar chart)
- Speed test screenshots
- Biểu đồ tăng trưởng thuê bao
- So sánh tốc độ 4G vs 5G

---

# SLIDE 27: ĐẦU TƯ & KẾ HOẠCH TRIỂN KHAI

**Đầu tư hạ tầng 5G:**

### **Viettel:**
- **Đầu tư:** Hàng chục nghìn tỷ đồng
- **Mục tiêu:** 20,000+ trạm BTS năm 2025
- **Hiện tại:** 6,500+ trạm (10/2024 - 2/2025)
- **Phủ sóng:** 100% tỉnh thành, 90% outdoor

### **VNPT:**
- **Phủ sóng:** 63 tỉnh/thành, 705 quận/huyện
- **Đầu tư:** Mở rộng hạ tầng liên tục
- **Mục tiêu:** Phủ sóng toàn diện 2025-2026

### **MobiFone:**
- **Trạng thái:** Đang đẩy nhanh triển khai
- **Mục tiêu:** Đuổi kịp 2 nhà mạng đầu

### **Hỗ trợ của Chính phủ:**
- **Nghị quyết 193/2025/QH15:**
  - Hỗ trợ đến 15% tổng vốn đầu tư
  - Điều kiện: Triển khai tối thiểu 20,000 trạm năm 2025
- Đơn giản hóa thủ tục cấp phép
- Hỗ trợ giải phóng mặt bằng

### **Thách thức:**
- Chi phí đầu tư lớn
- Phổ cập thiết bị 5G
- Phát triển use cases phù hợp VN

**Gợi ý hình ảnh:**
- Biểu đồ đầu tư (investment chart)
- Photos trạm BTS 5G
- Timeline deployment plan
- Infographic government support

---

# SLIDE 28: ỨNG DỤNG 5G TẠI VIỆT NAM

**Các ứng dụng 5G đang triển khai:**

### **1. Đang áp dụng:**

**Viettel:**
- 🏭 Smart factory tại các khu công nghiệp
- 🏥 Bệnh viện thông minh (telehealth pilot)
- 🎮 Cloud gaming platform
- 📺 Live streaming 4K/8K

**VNPT:**
- 🏙️ Smart city projects (Hà Nội, TP.HCM)
- 🚗 Smart traffic monitoring
- 🎓 Education platform
- 🏢 Enterprise solutions

**MobiFone:**
- 📱 Enhanced mobile broadband
- 🎬 Entertainment services

### **2. Kế hoạch triển khai:**
- Autonomous vehicles testing
- Smart agriculture ở Đồng bằng Sông Cửu Long
- Industrial IoT cho manufacturing
- Smart tourism

### **3. Thị trường mục tiêu:**
- Doanh nghiệp (B2B) - ưu tiên
- Consumer (B2C) - dần phổ cập
- Government & Smart city

**Gợi ý hình ảnh:**
- Screenshots các ứng dụng
- Photos triển khai thực tế VN
- Use case icons
- Partnership logos

---

# PHẦN 6: KẾT LUẬN

---

# SLIDE 29: TÓM TẮT & KẾT LUẬN

**Tóm tắt nội dung:**

### **Đặc điểm nổi bật của 5G:**
- 📊 Tốc độ: 10-100 lần nhanh hơn 4G
- ⚡ Độ trễ: Giảm xuống 1-4ms
- 🔗 Kết nối: 1 triệu thiết bị/km²
- 🎯 Đa dạng use cases: eMBB, URLLC, mMTC

### **Công nghệ cốt lõi:**
- Millimeter Wave & Sub-6 GHz
- Massive MIMO & Beamforming
- 5G NR với CP-OFDM
- SDN/NFV & Network Slicing

### **Dịch vụ chính:**
- Autonomous vehicles
- Smart cities
- Industrial IoT
- Enhanced entertainment
- Healthcare & more

### **Tại Việt Nam:**
- ✅ 3 nhà mạng đã triển khai thương mại
- ✅ 8.5 triệu+ thuê bao
- ✅ Tốc độ trung bình: 187 Mbps
- 🎯 Mục tiêu 2030: Phủ 99% dân số

**Gợi ý hình ảnh:**
- Infographic tổng hợp
- Key numbers
- Vietnam 5G logo

---

# SLIDE 30: TÀI LIỆU THAM KHẢO

**Nguồn tham khảo:**

### **Tài liệu kỹ thuật:**
1. 3GPP Specifications - Release 15, 16, 17
   - https://www.3gpp.org/
2. ITU-R IMT-2020 Requirements
   - https://www.itu.int/
3. Electronics Notes - 5G Technology Tutorial
   - https://www.electronics-notes.com/
4. IEEE Publications on 5G Technology

### **Triển khai tại Việt Nam:**
5. Báo VnExpress - "Băng tần 5G thứ ba tại Việt Nam có chủ"
   - https://vnexpress.net/
6. VnEconomy - "Vietnam's 5G Network Speed: Aiming for 99% Coverage"
   - https://en.vneconomy.vn/
7. Vietnam Plus - "Commercialisation of 5G"
   - https://en.vietnamplus.vn/
8. RCR Wireless - "Viettel gets 700MHz spectrum"
   - https://www.rcrwireless.com/

### **Use cases & Applications:**
9. IBM - "5G Examples, Applications & Use Cases"
   - https://www.ibm.com/
10. MDPI - "5G for Smart Cities: Digital Twin Integration"

### **Thông tin nhà mạng:**
- Viettel: https://vietteltelecom.vn/
- VNPT: https://vnpt.com.vn/
- MobiFone: https://mobifone.vn/

---

**CẢM ƠN QUÝ THẦY CÔ VÀ CÁC BẠN ĐÃ LẮNG NGHE!**

**Q&A Session**

---

# PHỤ LỤC: GỢI Ý THIẾT KẾ SLIDE

## Màu sắc gợi ý:
- **Màu chủ đạo:** Xanh dương (#0066CC, #0099FF)
- **Màu phụ:** Trắng, Xám nhạt (#F5F5F5)
- **Màu highlight:** Cam (#FF6600), Xanh lá (#00CC66)

## Font chữ:
- **Tiêu đề:** Arial Bold, Calibri Bold (28-36pt)
- **Nội dung:** Arial, Calibri (18-24pt)
- **Ghi chú:** 14-16pt

## Layout:
- Header: Logo trường + Tên bài lab
- Footer: Số slide + Tên nhóm
- Margin: Đủ khoảng trống, không quá dày nội dung

## Hình ảnh:
- Độ phân giải cao (min 1080p)
- Có credit/source
- Icon vector khi có thể
- Infographic > Text thuần

## Biểu đồ:
- Dùng chart thay vì text khi có số liệu
- Màu sắc nhất quán
- Label rõ ràng

## Animation (tùy chọn):
- Fade in cho bullet points
- Không lạm dụng animation phức tạp
- Professional & clean

---

# GHI CHÚ CHO NGƯỜI TRÌNH BÀY

## Phân công trình bày (gợi ý cho nhóm 4 người):

**Thành viên 1:** Slides 1-7 (Intro + Đặc tính 5G)
- Thời gian: ~5 phút

**Thành viên 2:** Slides 8-16 (Công nghệ RF & Core)
- Thời gian: ~6 phút

**Thành viên 3:** Slides 17-23 (Dịch vụ 5G)
- Thời gian: ~5 phút

**Thành viên 4:** Slides 24-30 (Triển khai VN + Kết luận)
- Thời gian: ~4 phút

**Tổng:** ~20 phút

## Tips trình bày:
1. ✅ Nói rõ ràng, không đọc slides
2. ✅ Giải thích thuật ngữ kỹ thuật
3. ✅ Tương tác với hình ảnh/biểu đồ
4. ✅ Chuẩn bị câu hỏi có thể bị hỏi
5. ✅ Backup slides cho phần Q&A
6. ✅ Practice nhiều lần trước

## Câu hỏi có thể gặp:
- So sánh 5G NSA vs SA?
- Tại sao VN chưa triển khai mmWave?
- Chi phí đầu tư 5G cao như thế nào?
- Bao giờ 5G phổ biến ở VN?
- Security concerns với 5G?

---

**HẾT**

**File tạo bởi:** Claude AI Assistant
**Ngày tạo:** 2025-11-17
**Mục đích:** Bài thực hành Lab02 - Mạng 5G
