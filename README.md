```
graph TD
    A[1. Website BookStore] --> B[1.1 Khảo sát yêu cầu]
    A --> C[1.2 Phân tích thiết kế]
    A --> D[1.3 Phát triển]
    A --> E[1.4 Kiểm thử]
    A --> F[1.5 Triển khai]
    A --> G[1.6 Bàn giao]

    B --> B1[1.1.1 Chuẩn bị khảo sát]
    B --> B2[1.1.2 Thực hiện khảo sát]
    B --> B3[1.1.3 Tổng hợp kết quả]

    C --> C1[1.2.1 Phân tích yêu cầu]
    C --> C2[1.2.2 Thiết kế CSDL]
    C --> C3[1.2.3 Thiết kế giao diện]

    D --> D1[1.3.1 Phát triển Backend]
    D --> D2[1.3.2 Phát triển Frontend]
    D --> D3[1.3.3 Tích hợp hệ thống]

    E --> E1[1.4.1 Kiểm thử đơn vị]
    E --> E2[1.4.2 Kiểm thử tích hợp]
    E --> E3[1.4.3 Kiểm thử hệ thống]

    F --> F1[1.5.1 Cài đặt hệ thống]
    F --> F2[1.5.2 Cấu hình]
    F --> F3[1.5.3 Đào tạo]

    G --> G1[1.6.1 Nghiệm thu]
    G --> G2[1.6.2 Bàn giao tài liệu]
    G --> G3[1.6.3 Kết thúc dự án]

    style A fill:#f9f,stroke:#333,stroke-width:2px
    style B,C,D,E,F,G fill:#bbf,stroke:#333
```
