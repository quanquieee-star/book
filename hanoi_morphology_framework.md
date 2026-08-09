# Khung phân tích hình thái đô thị Hà Nội giai đoạn 1874–1954
## Analytical Framework for Morphological Transformation of Hanoi's Urban Structure (1874–1954)

> [!NOTE]
> Framework này được xây dựng mới hoàn toàn, tổng hợp từ các nền tảng lý thuyết quốc tế về Urban Morphology. Không copy từ bất kỳ framework nào sẵn có. Mỗi thành phần đều có tham chiếu học thuật cụ thể.

---

## Sơ đồ cấu trúc Framework

```mermaid
graph TD
    subgraph THEORETICAL_FOUNDATION["THEORETICAL FOUNDATION"]
        direction LR
        TF1["<b>FORM</b><br/>Physical elements of<br/>urban landscape"]
        TF2["<b>RESOLUTION</b><br/>Hierarchical levels<br/>of analysis"]
        TF3["<b>TIME</b><br/>Morphological periods<br/>& morphogenesis"]
    end

    subgraph CONTEXTUAL_DETERMINANTS["CONTEXTUAL DETERMINANTS OF HANOI"]
        direction LR
        CD1["<b>Hydro-topographical<br/>Setting</b><br/>Red River, lakes,<br/>canals, terrain"]
        CD2["<b>Colonial Planning<br/>Policy</b><br/>French administrative<br/>& urban agendas"]
        CD3["<b>Indigenous Urban<br/>Tradition</b><br/>Kẻ Chợ structure,<br/>phường nghề system"]
    end

    subgraph SCALE["SCALE OF ANALYSIS"]
        SC["City-District Scale<br/><i>Focusing on the historical urban core</i>"]
    end

    subgraph MORPHOLOGICAL_VARIABLES["MORPHOLOGICAL VARIABLES"]
        direction LR
        MV1["<b>A. Street Network</b>"]
        MV2["<b>B. Block & Plot<br/>Structure</b>"]
        MV3["<b>C. Open Space &<br/>Landscape System</b>"]
        MV4["<b>D. Hydro-topographical<br/>Framework</b>"]
    end

    subgraph COMPONENTS_A["Components of A"]
        A1["- Street typology<br/>- Route hierarchy<br/>- Network pattern<br/>&nbsp;&nbsp;organic vs. grid"]
    end

    subgraph COMPONENTS_B["Components of B"]
        B1["- Block formation<br/>&nbsp;&nbsp;& configuration<br/>- Plot ratio &<br/>&nbsp;&nbsp;subdivision pattern<br/>- Building-to-plot<br/>&nbsp;&nbsp;relationship"]
    end

    subgraph COMPONENTS_C["Components of C"]
        C1["- Civic squares &<br/>&nbsp;&nbsp;public gardens<br/>- Tree-lined<br/>&nbsp;&nbsp;boulevards<br/>- Green corridors<br/>&nbsp;&nbsp;& promenades"]
    end

    subgraph COMPONENTS_D["Components of D"]
        D1["- Lake system as<br/>&nbsp;&nbsp;spatial organizer<br/>- River & canal<br/>&nbsp;&nbsp;network<br/>- Terrain-adapted<br/>&nbsp;&nbsp;road alignment"]
    end

    subgraph TEMPORAL_ANALYSIS["MORPHOLOGICAL PERIODS"]
        direction LR
        T1["<b>Phase I</b><br/>1874–1888<br/><i>Formation of<br/>modern<br/>urban frame</i>"]
        T2["<b>Phase II</b><br/>1888–1897<br/><i>Systematic<br/>urban<br/>restructuring</i>"]
        T3["<b>Phase III</b><br/>1897–1920<br/><i>Capital city<br/>expansion</i>"]
        T4["<b>Phase IV</b><br/>1920–1943<br/><i>Hébrard plan<br/>& integrated<br/>urbanism</i>"]
        T5["<b>Phase V</b><br/>1943–1954<br/><i>Wartime<br/>consolidation</i>"]
    end

    subgraph ANALYTICAL_REPRESENTATION["ANALYTICAL REPRESENTATION"]
        direction LR
        AR1["<b>Morphological<br/>Region Mapping</b><br/><i>Conzen, 1960</i>"]
        AR2["<b>Urban Layering<br/>Diagram</b><br/><i>Accumulation of<br/>spatial layers</i>"]
    end

    subgraph RESEARCH_OUTCOMES["RESEARCH OUTCOMES"]
        O1["1. Identify morphological layers accumulated<br/>through five colonial planning phases and<br/>their persistence in contemporary urban fabric"]
        O2["2. Analyze the coexistence and structural<br/>transition between traditional organic tissue<br/>and modern planned urban form"]
        O3["3. Evaluate how hydro-topographical conditions<br/>shaped a distinctive multi-layered urban<br/>morphology differentiating Hanoi from other<br/>Southeast Asian colonial cities"]
    end

    subgraph FINAL_OUTCOME[""]
        FO["<b>Multi-layered Urban Morphology of Hanoi<br/>under Colonial Planning Interventions (1874–1954)</b>"]
    end

    THEORETICAL_FOUNDATION --> CONTEXTUAL_DETERMINANTS
    CONTEXTUAL_DETERMINANTS --> SCALE
    SCALE --> MORPHOLOGICAL_VARIABLES

    MV1 --> COMPONENTS_A
    MV2 --> COMPONENTS_B
    MV3 --> COMPONENTS_C
    MV4 --> COMPONENTS_D

    COMPONENTS_A --> TEMPORAL_ANALYSIS
    COMPONENTS_B --> TEMPORAL_ANALYSIS
    COMPONENTS_C --> TEMPORAL_ANALYSIS
    COMPONENTS_D --> TEMPORAL_ANALYSIS

    TEMPORAL_ANALYSIS --> ANALYTICAL_REPRESENTATION
    ANALYTICAL_REPRESENTATION --> RESEARCH_OUTCOMES
    RESEARCH_OUTCOMES --> FINAL_OUTCOME

    style THEORETICAL_FOUNDATION fill:#1a3a5c,stroke:#2d6da8,color:#fff
    style CONTEXTUAL_DETERMINANTS fill:#2d4a3e,stroke:#4a8a6e,color:#fff
    style MORPHOLOGICAL_VARIABLES fill:#4a3a1a,stroke:#8a7a3a,color:#fff
    style TEMPORAL_ANALYSIS fill:#3a1a4a,stroke:#7a3a8a,color:#fff
    style RESEARCH_OUTCOMES fill:#1a1a1a,stroke:#555,color:#fff
    style FINAL_OUTCOME fill:#c45a00,stroke:#e67300,color:#fff
```

---

## Chi tiết từng tầng của Framework

### Tầng 1: NỀN TẢNG LÝ THUYẾT (Theoretical Foundation)

Dựa trên 3 nguyên lý cốt lõi của nghiên cứu hình thái đô thị theo **Moudon (1997)**:

| Nguyên lý | Nội dung | Tham chiếu |
|---|---|---|
| **FORM** (Hình thái) | Các yếu tố vật chất cơ bản cấu thành cảnh quan đô thị: đường phố, ô phố, lô đất, công trình, không gian mở | Conzen (1960); Oliveira (2016) |
| **RESOLUTION** (Cấp độ phân giải) | Phân tích ở nhiều cấp: lô đất → ô phố → khu vực → thành phố. Mỗi cấp cho thấy logic tổ chức không gian khác nhau | Kropf (2009); Oliveira (2016) |
| **TIME** (Thời gian) | Đô thị là sản phẩm tích lũy qua nhiều giai đoạn hình thái (morphological periods). Mỗi giai đoạn để lại "dấu vết" vật chất có thể nhận diện | Conzen (1960); Whitehand (2001) |

**Tham chiếu đầy đủ:**
- Moudon, A.V. (1997). Urban morphology as an emerging interdisciplinary field. *Urban Morphology*, 1, 3–10.
- Conzen, M.R.G. (1960). *Alnwick, Northumberland: A Study in Town-Plan Analysis*. Institute of British Geographers, Publication No. 27.
- Oliveira, V. (2016). *Urban Morphology: An Introduction to the Study of the Physical Form of Cities*. Springer.
- Kropf, K. (2009). Aspects of urban form. *Urban Morphology*, 13(2), 105–120.
- Whitehand, J.W.R. (2001). British urban morphology: the Conzenian tradition. *Urban Morphology*, 5(2), 103–109.

---

### Tầng 2: BỐI CẢNH QUYẾT ĐỊNH (Contextual Determinants)

> [!IMPORTANT]
> Đây là điểm khác biệt quan trọng nhất so với các framework hình thái đô thị áp dụng cho đô thị châu Âu hoặc đô thị Malay. Hà Nội có **3 yếu tố bối cảnh đặc thù** chi phối toàn bộ quá trình biến đổi hình thái:

| Yếu tố | Vai trò đối với hình thái Hà Nội | Tham chiếu |
|---|---|---|
| **Hydro-topographical Setting** (Bối cảnh thủy văn – địa hình) | Hệ thống sông Hồng, sông Tô Lịch, hồ Hoàn Kiếm, hồ Tây, hồ Trúc Bạch và mạng lưới kênh mương chi phối trực tiếp tuyến đường, hình dạng ô phố, và vị trí các khu chức năng. Đây là yếu tố mà Conzen gọi là "fixation line" — ranh giới tự nhiên định hình sự phát triển đô thị. | Logan (2000); Papin (2001); Cerise (2009) |
| **Colonial Planning Policy** (Chính sách quy hoạch thuộc địa) | Các đồ án quy hoạch của Pháp (từ bản đồ phân khu 1880s đến Đồ án Hébrard 1924 và đồ án Pineau 1943) tạo ra tầng cấu trúc hiện đại xếp chồng lên cấu trúc bản địa. | Masson (1929); Wright (1991); Lancret (2002) |
| **Indigenous Urban Tradition** (Truyền thống đô thị bản địa) | Cấu trúc Kẻ Chợ với hệ thống phường nghề, mạng đường phố hữu cơ, ô phố nhỏ mật độ cao tạo nên "lớp nền" (base layer) mà mọi can thiệp quy hoạch hiện đại đều phải thích ứng hoặc chồng lên. | Papin (2001); Nguyễn Quốc Thông (2004) |

**Tham chiếu đầy đủ:**
- Logan, W.S. (2000). *Hanoi: Biography of a City*. University of New South Wales Press.
- Papin, P. (2001). *Histoire de Hanoi*. Fayard, Paris.
- Cerise, E. (2009). *Fabrication de la ville de Hanoi entre planification et pratiques habitantes*. Thèse de doctorat, Université Paris 8.
- Masson, A. (1929). *Hanoï pendant la période héroïque (1873–1888)*. Geuthner, Paris.
- Wright, G. (1991). *The Politics of Design in French Colonial Urbanism*. University of Chicago Press.
- Lancret, N. (2002). "De l'usage de termes: ville de l'Asie du Sud-Est, la ville vietnamienne." In *Vocabulaire architectural*. EFEO/IRD.

---

### Tầng 3: BIẾN SỐ PHÂN TÍCH HÌNH THÁI (Morphological Variables)

Dựa trên mô hình phân chia ba thành phần (tripartite division) của Conzen (1960) — **Town Plan = Street System + Plot Pattern + Building Fabric** — và được mở rộng theo Oliveira (2016) bổ sung thêm **Natural Context** và **System of Public Spaces**, framework này xác định **4 biến phân tích** phù hợp với đặc thù Hà Nội:

#### A. Street Network (Mạng lưới đường phố)
| Thành phần | Mô tả | Cơ sở lý thuyết |
|---|---|---|
| Street typology | Phân loại đường theo mặt cắt, chức năng, thời kỳ hình thành (đường phố truyền thống vs. đại lộ thuộc địa) | Conzen (1960): Street system |
| Route hierarchy | Phân cấp từ ngõ nhỏ (ruelles) → phố thương mại → đại lộ hành chính (boulevards) | Kropf (2009): Levels of resolution |
| Network pattern | Mô hình mạng: hữu cơ (organic) tại Kẻ Chợ vs. ô bàn cờ (grid) tại khu Pháp vs. hướng tâm (radial) từ sau 1924 | Oliveira (2016): Street network analysis |

#### B. Block & Plot Structure (Cấu trúc ô phố & phân lô)
| Thành phần | Mô tả | Cơ sở lý thuyết |
|---|---|---|
| Block formation & configuration | Hình dạng, kích thước, tỷ lệ dài/rộng của ô phố qua các giai đoạn | Conzen (1960): Plot pattern & street blocks |
| Plot subdivision pattern | Cách phân lô bên trong ô phố: lô hẹp sâu (nhà ống) vs. lô rộng (biệt thự) vs. lô lớn (công trình công) | Conzen (1960): Burgage cycle |
| Building-to-plot relationship | Tỷ lệ xây dựng/lô đất, khoảng lùi, hình thức bố trí công trình trên lô | Kropf (2009): Plot-building relationship |

#### C. Open Space & Landscape System (Hệ thống không gian mở & cảnh quan)
| Thành phần | Mô tả | Cơ sở lý thuyết |
|---|---|---|
| Civic squares & public gardens | Quảng trường, vườn hoa công cộng (Jardin botanique, Place Paul Bert / quảng trường Đông Kinh Nghĩa Thục) | Oliveira (2016): System of public spaces |
| Tree-lined boulevards | Đại lộ có hành lang cây xanh (như Rue Paul Bert, Avenue Puginier) — vừa là giao thông vừa là cảnh quan | Whitehand (2001): Fringe belt concept |
| Green corridors & promenades | Không gian đi dạo ven hồ, dải cây xanh liên kết các công viên | Oliveira (2016) |

#### D. Hydro-topographical Framework (Khung thủy văn – địa hình)
> [!TIP]
> Đây là biến phân tích **độc đáo** của framework này, không có trong các framework Conzenian truyền thống vốn được xây dựng cho đô thị châu Âu ít chịu chi phối bởi thủy văn. Biến này được bổ sung dựa trên nhận định của Oliveira (2016) về "Natural Context" và nghiên cứu thực nghiệm về Hà Nội của Cerise (2009), Logan (2000).

| Thành phần | Mô tả | Cơ sở lý thuyết |
|---|---|---|
| Lake system as spatial organizer | Hồ Hoàn Kiếm, Hồ Tây, Hồ Trúc Bạch, Bảy Mẫu... đóng vai trò "fixation line" tự nhiên, định hướng tuyến đường và ranh giới các khu chức năng | Conzen (1960): Fixation line concept — áp dụng mở rộng cho ranh giới tự nhiên |
| River & canal network | Sông Hồng, sông Tô Lịch, kênh mương — hệ thống giao thông thủy truyền thống bị thu hẹp/lấp dần, chuyển thành trục đường bộ | Logan (2000); Papin (2001) |
| Terrain-adapted road alignment | Tuyến đường uốn theo địa hình tự nhiên (đê sông, gò đất, bờ hồ) thay vì theo lưới bàn cờ cứng nhắc | Cerise (2009) |

---

### Tầng 4: CÁC GIAI ĐOẠN HÌNH THÁI (Morphological Periods)

Khái niệm **morphological period** (giai đoạn hình thái) là công cụ phân tích cốt lõi của trường phái Conzen (1960), cho phép nhận diện các thời kỳ mà hình thái đô thị mang những đặc trưng thống nhất. Framework này xác định **5 giai đoạn** tương ứng với các mốc quy hoạch lớn:

| Giai đoạn | Thời kỳ | Đặc trưng hình thái chính | Sự kiện quy hoạch chủ đạo |
|---|---|---|---|
| **I** | 1874–1888 | Xuất hiện lớp cấu trúc đô thị hiện đại đầu tiên (khu nhượng địa Đồn Thủy), tồn tại song song với cấu trúc truyền thống Kẻ Chợ | Hình thành nhượng địa, thành lập Thành phố Hà Nội (1888) |
| **II** | 1888–1897 | Tái cấu trúc có hệ thống: phá Hoàng thành, lấp kênh mương, xây dựng mạng đường ô bàn cờ khu phố Tây phía Nam hồ Hoàn Kiếm | Hà Nội trở thành thành phố trực thuộc Pháp |
| **III** | 1897–1920 | Mở rộng theo mô hình thành phố thuộc địa: xây dựng hạ tầng lớn (cầu Long Biên 1903), hình thành khu phố Tây hoàn chỉnh | Hà Nội là thủ đô Liên bang Đông Dương |
| **IV** | 1920–1943 | Chuyển sang quy hoạch tích hợp: phân vùng chức năng (zoning), kết hợp cảnh quan tự nhiên (hồ, cây xanh), mạng giao thông hướng tâm | Đồ án Hébrard (1924), phong cách Đông Dương |
| **V** | 1943–1954 | Củng cố và hoàn thiện cấu trúc trong điều kiện chiến tranh, hạn chế mở rộng, tập trung chỉnh trang nội đô | Đồ án Pineau (1943), kết thúc thời kỳ thuộc địa |

**Tham chiếu:** Masson (1929); Wright (1991); Logan (2000); Papin (2001); Cerise (2009).

---

### Tầng 5: BIỂU DIỄN PHÂN TÍCH (Analytical Representation)

| Công cụ biểu diễn | Mô tả | Cơ sở lý thuyết |
|---|---|---|
| **Morphological Region Mapping** | Lập bản đồ vùng hình thái: xác định các vùng đô thị có đặc trưng đồng nhất về mạng đường, ô phố, và kiểu công trình | Conzen (1960): Morphological region |
| **Urban Layering Diagram** | Sơ đồ chồng lớp: thể hiện sự tích lũy nhiều lớp không gian (layers) qua các giai đoạn, trong đó mỗi lớp mới được tích hợp (chứ không thay thế hoàn toàn) lớp cũ | Khái niệm từ bài viết của tác giả, phù hợp với Conzen (1960) về "time depth" |

---

### Tầng 6: KẾT QUẢ NGHIÊN CỨU (Research Outcomes)

> [!IMPORTANT]
> 3 kết quả này được viết **hoàn toàn mới**, gắn chặt với đặc thù nghiên cứu Hà Nội thay vì copy từ framework khác.

1. **Nhận diện các lớp hình thái** (morphological layers) được tích lũy qua 5 giai đoạn quy hoạch thuộc địa và sự tồn tại liên tục (persistence) của chúng trong cấu trúc đô thị đương đại.

2. **Phân tích sự đồng tồn tại và chuyển tiếp cấu trúc** giữa mô hình đô thị truyền thống hữu cơ (organic tissue) và hình thái đô thị hiện đại có quy hoạch (planned urban form), hình thành cấu trúc đô thị đa lớp (multi-layered urban structure).

3. **Đánh giá vai trò của điều kiện thủy văn – địa hình** trong việc hình thành hình thái đô thị đa lớp đặc trưng, tạo nên sự khác biệt của Hà Nội so với các đô thị thuộc địa khác tại Đông Nam Á (Sài Gòn, Batavia).

---

### KẾT LUẬN TỔNG THỂ (Final Outcome)

**"Multi-layered Urban Morphology of Hanoi under Colonial Planning Interventions (1874–1954)"**

*(Hình thái đô thị đa lớp của Hà Nội dưới tác động của các can thiệp quy hoạch thuộc địa, 1874–1954)*

---

## Danh mục tham chiếu đầy đủ

| # | Tham chiếu | Vai trò trong Framework |
|---|---|---|
| 1 | **Conzen, M.R.G.** (1960). *Alnwick, Northumberland: A Study in Town-Plan Analysis*. Institute of British Geographers, Publication No. 27. | Nền tảng: Tripartite division, morphological period, fixation line, burgage cycle, morphological region |
| 2 | **Moudon, A.V.** (1997). Urban morphology as an emerging interdisciplinary field. *Urban Morphology*, 1, 3–10. | Nền tảng: 3 nguyên lý Form – Resolution – Time |
| 3 | **Whitehand, J.W.R.** (2001). British urban morphology: the Conzenian tradition. *Urban Morphology*, 5(2), 103–109. | Nền tảng: Mở rộng Conzen, fringe belt |
| 4 | **Kropf, K.** (2009). Aspects of urban form. *Urban Morphology*, 13(2), 105–120. | Nền tảng: Hierarchical levels of resolution |
| 5 | **Oliveira, V.** (2016). *Urban Morphology: An Introduction to the Study of the Physical Form of Cities*. Springer. | Nền tảng: Natural context, system of public spaces |
| 6 | **Logan, W.S.** (2000). *Hanoi: Biography of a City*. University of New South Wales Press. | Bối cảnh Hà Nội: Tổng quan lịch sử quy hoạch |
| 7 | **Papin, P.** (2001). *Histoire de Hanoi*. Fayard, Paris. | Bối cảnh Hà Nội: Lịch sử đô thị và thủy văn |
| 8 | **Cerise, E.** (2009). *Fabrication de la ville de Hanoi entre planification et pratiques habitantes*. Thèse de doctorat, Université Paris 8. | Bối cảnh Hà Nội: Mối quan hệ quy hoạch – thực tiễn |
| 9 | **Masson, A.** (1929). *Hanoï pendant la période héroïque (1873–1888)*. Geuthner, Paris. | Dữ liệu giai đoạn I |
| 10 | **Wright, G.** (1991). *The Politics of Design in French Colonial Urbanism*. University of Chicago Press. | Chính sách quy hoạch thuộc địa |
| 11 | **Lancret, N.** (2002). De l'usage de termes. In *Vocabulaire architectural*. EFEO/IRD. | Khái niệm đô thị Việt Nam |

> [!TIP]
> **Ghi chú trích dẫn cho Figure:** Khi sử dụng sơ đồ này trong bài báo, bạn ghi dưới figure:
> *"Author's analytical framework, developed based on the Conzenian tripartite division of urban form (Conzen, 1960), Moudon's three principles of urban morphology (1997), and Oliveira's analytical framework (2016). The hydro-topographical variable is added to account for the specific natural determinants of Hanoi's urban development (Logan, 2000; Cerise, 2009)."*
