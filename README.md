# 🛒 Marketplace

> Multi-vendor e-commerce marketplace — built with Next.js, NestJS, PostgreSQL.

## 📖 Giới thiệu

Dự án xây dựng một sàn thương mại điện tử đa nhà cung cấp (multi-vendor marketplace), cho phép nhiều người bán (vendor) đăng bán sản phẩm và người mua (customer) mua hàng trên cùng một nền tảng.

## 🏗️ Kiến trúc

```
marketplace/
├── apps/
│   ├── api/            # Backend (NestJS + Prisma + PostgreSQL)
│   ├── web/            # Customer-facing web app (Next.js)
│   └── admin/          # Vendor & Admin dashboard (Next.js)
├── packages/
│   ├── database/       # Prisma schema & client
│   ├── shared-types/   # TypeScript types dùng chung
│   └── ui/             # Shared React components
└── ...
```

## 🛠️ Tech Stack

| Layer    | Công nghệ                        |
|----------|----------------------------------|
| Frontend | Next.js 14, TypeScript, Tailwind |
| Backend  | NestJS, Prisma, PostgreSQL       |
| Cache    | Redis                            |
| Search   | Elasticsearch                    |
| Queue    | BullMQ                           |
| DevOps   | Docker, GitHub Actions           |

## 🚀 Getting Started

> Hướng dẫn chạy dự án sẽ được cập nhật khi hoàn thiện setup.

## 📝 Roadmap

- [x] Khởi tạo dự án & cấu trúc monorepo
- [ ] Setup database schema
- [ ] Auth module (JWT + OAuth)
- [ ] Product catalog
- [ ] Cart & Checkout
- [ ] Order management
- [ ] Vendor dashboard
- [ ] Admin dashboard

## 📄 License

MIT