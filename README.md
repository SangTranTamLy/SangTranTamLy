  <h1 align="center">POS System</h1>

  <p align="center">
    Hệ thống quản lý bán hàng, kho hàng, ca làm việc và hóa đơn.
  </p>

  <p align="center">
    <img src="https://img.shields.io/badge/Frontend-React%20%2B%20TypeScript-2563EB?style=for-the-badge&logo=react&logoColor=white" alt="Frontend React TypeScript" />
    <img src="https://img.shields.io/badge/Backend-Node.js%20%2B%20Express-16A34A?style=for-the-badge&logo=node.js&logoColor=white" alt="Backend Node Express" />
    <img src="https://img.shields.io/badge/Database-MySQL-F59E0B?style=for-the-badge&logo=mysql&logoColor=white" alt="Database MySQL" />
    <img src="https://img.shields.io/badge/Auth-JWT-111827?style=for-the-badge&logo=jsonwebtokens&logoColor=white" alt="JWT Authentication" />
  </p>

  ---

  ## Giới Thiệu Dự Án

  **POS System** là hệ thống quản lý bán hàng được xây dựng nhằm hỗ trợ các nghiệp vụ vận hành tại cửa hàng như quản lý sản phẩm, danh mục, bán hàng tại quầy, hóa đơn, kho hàng, kiểm kê, ca làm việc và báo cáo doanh thu.

  Dự án phù hợp cho các mô hình:

  - Cửa hàng bán lẻ
  - Quán cà phê, trà sữa, đồ uống
  - Siêu thị mini
  - Mô hình kinh doanh nhỏ cần quản lý bán hàng và tồn kho rõ ràng

  Mục tiêu của hệ thống là giúp quy trình bán hàng nhanh hơn, dữ liệu tập trung hơn và hỗ trợ người quản lý theo dõi hoạt động kinh doanh một cách trực quan.

  ---

  ## Tính Năng Chính

  | Nhóm chức năng | Mô tả |
  | --- | --- |
  | Quản lý sản phẩm | Thêm, sửa, cập nhật trạng thái, quản lý giá bán, tồn kho và thông tin sản phẩm. |
  | Quản lý danh mục | Phân loại sản phẩm theo nhóm để dễ tìm kiếm và quản lý. |
  | Bán hàng tại quầy | Tạo đơn hàng nhanh, chọn sản phẩm, tính tổng tiền và thanh toán. |
  | Quản lý hóa đơn | Theo dõi danh sách hóa đơn, chi tiết đơn hàng và trạng thái thanh toán. |
  | Quản lý nhập kho | Ghi nhận số lượng nhập kho, cập nhật tồn kho và lịch sử giao dịch kho. |
  | Quản lý kiểm kê | Kiểm tra tồn kho thực tế, đối chiếu và điều chỉnh số lượng khi cần. |
  | Quản lý ca làm việc | Theo dõi ca làm của nhân viên, hỗ trợ quy trình vận hành tại quầy. |
  | Quản lý người dùng | Phân quyền người dùng theo vai trò như admin, nhân viên bán hàng, quản lý. |
  | Báo cáo doanh thu | Tổng hợp doanh thu, đơn hàng và dữ liệu kinh doanh phục vụ quản lý. |
  | Giao diện responsive | Tối ưu trải nghiệm sử dụng trên nhiều kích thước màn hình. |

  ---

  ## Công Nghệ Sử Dụng

  ### Frontend

  | Công nghệ | Vai trò |
  | --- | --- |
  | React | Xây dựng giao diện người dùng |
  | TypeScript | Tăng tính an toàn kiểu dữ liệu khi phát triển |
  | Tailwind CSS | Thiết kế giao diện nhanh, hiện đại và responsive |
  | React Router | Điều hướng giữa các trang trong hệ thống |
  | Axios | Gửi request từ frontend đến backend API |

  ### Backend

  | Công nghệ | Vai trò |
  | --- | --- |
  | Node.js | Môi trường chạy backend |
  | Express.js | Xây dựng REST API |
  | TypeScript | Tổ chức code backend rõ ràng, dễ bảo trì |
  | MySQL | Lưu trữ dữ liệu hệ thống |
  | JWT Authentication | Xác thực và phân quyền người dùng |

  ---

  ## Giao Diện Hệ Thống

  Khu vực này dùng để cập nhật ảnh giao diện sau khi hoàn thiện hoặc chụp màn hình các chức năng chính.

  > Có thể cập nhật ảnh giao diện tại thư mục `docs/images`.

  Ví dụ placeholder an toàn:

  ```md
  ![Dashboard Screenshot](./docs/images/dashboard.png)
  ![POS Screenshot](./docs/images/pos.png)
  ![Inventory Screenshot](./docs/images/inventory.png)
  ```

  Gợi ý ảnh nên thêm:

  - Dashboard tổng quan
  - Màn hình bán hàng POS
  - Trang quản lý sản phẩm
  - Trang quản lý kho và kiểm kê
  - Trang hóa đơn và báo cáo

  ---

  ## Cấu Trúc Thư Mục

  ```text
  pos-system/
  +-- frontend/
  |   +-- src/
  |   +-- package.json
  |   +-- vite.config.ts
  +-- backend/
  |   +-- src/
  |   +-- package.json
  |   +-- tsconfig.json
  +-- docs/
  |   +-- images/
  +-- README.md
  ```

  ---

  ## Hướng Dẫn Cài Đặt

  ### 1. Clone repository

  ```bash
  git clone https://github.com/SangTranTamLy/pos-system-online.git
  cd pos-system-online
  ```

  ### 2. Cài dependencies cho frontend

  ```bash
  cd frontend
  npm install
  ```

  ### 3. Cài dependencies cho backend

  ```bash
  cd ../backend
  npm install
  ```

  ### 4. Tạo file môi trường

  Tạo file `.env` trong thư mục `backend` và file `.env.development` trong thư mục `frontend` theo mẫu bên dưới.

  ### 5. Chạy backend

  ```bash
  cd backend
  npm run dev
  ```

  Backend mặc định chạy tại:

  ```text
  http://localhost:5000
  ```

  ### 6. Chạy frontend

  ```bash
  cd frontend
  npm run dev
  ```

  Frontend mặc định chạy tại:

  ```text
  http://localhost:5173
  ```

  ---

  ## Biến Môi Trường Mẫu

  ### Backend `.env.example`

  ```env
  PORT=5000

  DB_HOST=localhost
  DB_PORT=3306
  DB_USER=root
  DB_PASSWORD=your_database_password
  DB_NAME=pos_system

  JWT_SECRET=your_jwt_secret_key
  ```

  ### Frontend `.env.example`

  ```env
  VITE_API_URL=http://localhost:5000/api

  VITE_VIETQR_BANK_ID=
  VITE_VIETQR_ACCOUNT_NO=
  VITE_VIETQR_ACCOUNT_NAME=
  ```

  > Không đưa mật khẩu thật, token thật hoặc thông tin tài khoản ngân hàng thật lên GitHub.

  ---

  ## Tài Khoản Demo

  | Vai trò | Email / Tên đăng nhập | Mật khẩu | Ghi chú |
  | --- | --- | --- | --- |
  | Admin | `admin@example.com` | `123456` | Toàn quyền quản lý hệ thống |
  | Nhân viên bán hàng | `staff@example.com` | `123456` | Truy cập POS, hóa đơn, khách hàng |
  | Quản lý kho | `warehouse@example.com` | `123456` | Quản lý nhập kho, kiểm kê và tồn kho |

  > Có thể thay đổi tài khoản demo theo dữ liệu seed hoặc cấu hình thực tế của dự án.

  ---

  ## Điểm Nổi Bật

  - Giao diện hiện đại, rõ ràng và dễ thao tác.
  - Quy trình bán hàng tại quầy nhanh, phù hợp môi trường vận hành thực tế.
  - Quản lý kho rõ ràng, hỗ trợ nhập kho và kiểm kê.
  - Phân quyền người dùng theo vai trò.
  - Dễ mở rộng thêm module mới như máy in hóa đơn, mã vạch và báo cáo nâng cao.
  - Cấu trúc frontend/backend tách biệt, thuận tiện bảo trì và triển khai.

  ---

  ## Định Hướng Phát Triển

  - [ ] Tích hợp máy in hóa đơn.
  - [ ] Hỗ trợ quét mã vạch sản phẩm.
  - [ ] Xuất báo cáo Excel/PDF.
  - [ ] Bổ sung thống kê nâng cao theo ngày, tháng, sản phẩm và nhân viên.
  - [ ] Đồng bộ dữ liệu realtime.
  - [ ] Tối ưu trải nghiệm trên thiết bị cảm ứng tại quầy.

  ---

  ## Thông Tin Tác Giả

  | Thông tin | Nội dung |
  | --- | --- |
  | Tên | T.Sang Dev |
  | Vai trò | Fullstack Developer |
  | GitHub | [SangTranTamLy](https://github.com/SangTranTamLy) |
  | Email | [sangchaubr089@gmail.com](mailto:sangchaubr089@gmail.com) |

  ---

  ## License

  Dự án phục vụ mục đích học tập và phát triển cá nhân.

  Bạn có thể chuyển sang **MIT License** nếu muốn công khai mã nguồn theo giấy phép mã nguồn mở.
