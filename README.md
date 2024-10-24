# NFTevent - NFT Event Platform on Polkadot

NFTevent là một nền tảng được xây dựng trên Polkadot cho phép tạo và quản lý các sự kiện bằng NFT. Dự án này tận dụng tính năng cross-chain của Polkadot để cung cấp trải nghiệm mượt mà cho người dùng trong việc tạo, mua bán và quản lý vé sự kiện dưới dạng NFT.

## 📋 Tính năng chính

- Tạo và quản lý sự kiện
- Phát hành vé sự kiện dưới dạng NFT
- Marketplace để mua bán vé
- Tích hợp ví Polkadot
- Smart contract bảo mật
- Cross-chain interoperability
- Hệ thống check-in tại sự kiện

## 🚀 Cài đặt

1. Clone repository:
```bash
git clone https://github.com/tuantuho40/Polkadot-VN-Hackathon-2024/NFTevent.git
cd NFTevent
```

2. Cài đặt dependencies:
```bash
yarn install
```

3. Cấu hình môi trường:
```bash
cp .env.example .env
```
Chỉnh sửa file `.env` với các thông số phù hợp.

4. Khởi chạy development server:
```bash
yarn dev
```

## 🛠 Tech Stack

- Substrate/Polkadot
- Rust
- Node.js
- React
- Web3.js
- IPFS

## 🏗 Cấu trúc dự án

```
NFTevent/
├── contracts/           # Smart contracts 
├── chain/              # Substrate chain code
├── frontend/           # React frontend
├── scripts/            # Development scripts
└── tests/              # Test files
```

## 📝 API Documentation

API documentation có thể được truy cập tại `http://localhost:3000/api-docs` sau khi khởi chạy development server.

## 🧪 Testing

Chạy unit tests:
```bash
yarn test
```

Chạy end-to-end tests:
```bash
yarn test:e2e
```

## 🔐 Smart Contracts

Smart contracts được viết bằng ink! và được triển khai trên parachain. Các contract chính bao gồm:

- EventFactory.rs: Tạo và quản lý sự kiện
- EventNFT.rs: NFT token standard cho vé sự kiện
- Marketplace.rs: Quản lý việc mua bán vé

## 🤝 Đóng góp

1. Fork dự án
2. Tạo branch mới (`git checkout -b feature/AmazingFeature`)
3. Commit changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to branch (`git push origin feature/AmazingFeature`)
5. Tạo Pull Request

## 📄 License

Dự án này được phân phối dưới giấy phép MIT. Xem file `LICENSE` để biết thêm chi tiết.

## ⚠️ Lưu ý

- Dự án đang trong giai đoạn phát triển (Alpha)
- Backup dữ liệu thường xuyên
- Kiểm tra kỹ các giao dịch trước khi ký
- Báo cáo lỗi qua GitHub Issues

## 🙏 Cảm ơn

Cảm ơn các thư viện và framework đã được sử dụng trong dự án:

- Polkadot
- Substrate
- ink!
- OpenZeppelin
- React
- Web3.js
