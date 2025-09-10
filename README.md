# 📱 BkHelper

BkHelper là một **mobile app** được phát triển bằng **React Native + Expo** nhằm hỗ trợ sinh viên Bách Khoa tìm kiếm nhanh chóng thông tin **khóa học, giờ học, phòng học, và giảng viên** trong trường.

## 🚀 Tech Stack

- **Framework**: [React Native](https://reactnative.dev/) + [Expo](https://expo.dev/)
- **Navigation**: [Expo Router](https://expo.github.io/router) + [React Navigation](https://reactnavigation.org/)
- **State & Form**: [Formik](https://formik.org/)
- **Networking**: [Axios](https://axios-http.com/)
- **UI/UX**:
  - `@expo/vector-icons` – Icon pack
  - `expo-linear-gradient`, `expo-blur` – UI effects
  - `react-native-root-toast` – Toast notification
- **Animation**: `react-native-reanimated`, `react-native-gesture-handler`
- **Storage**: `@react-native-async-storage/async-storage`
- **Web Support**: `react-native-web`, `react-native-webview`

## 📂 Cấu trúc thư mục

```
src/
├── app/            # Màn hình + layout (sử dụng expo-router)
├── assets/         # Hình ảnh, fonts, icons
├── components/     # Các UI component tái sử dụng
├── constants/      # Màu sắc, config, enums
├── context/        # React Context (Auth, Theme...)
├── hooks/          # Custom hooks (useAuth, useTheme...)
├── scripts/        # Script hỗ trợ (reset project...)
├── services/       # Gọi API, Axios instance, service layer
├── types/          # TypeScript types & interfaces
└── utils/          # Hàm tiện ích, format date, logger...
```

## 🛠️ Cài đặt & Chạy ứng dụng

### 1️⃣ Yêu cầu môi trường
- [Node.js >= 18](https://nodejs.org)
- [Expo CLI](https://docs.expo.dev/get-started/installation/)

### 2️⃣ Clone project
```bash
git clone https://github.com/thinhnguyen07022004/BkHelper.git
cd BkHelper
```

### 3️⃣ Cài đặt dependencies
```bash
npm install
# hoặc yarn install
```

### 4️⃣ Chạy ứng dụng
```bash
npm run start
# Mở app Expo Go trên điện thoại và quét QR code
```

Chạy trên nền tảng cụ thể:
```bash
npm run android   # Android Emulator hoặc thiết bị thật
npm run ios       # iOS Simulator (macOS)
npm run web       # Chạy trên web
```

### 5️⃣ Reset project (nếu cần)
```bash
npm run reset-project
```

## 📚 Scripts

| Lệnh                | Mô tả                          |
|--------------------|--------------------------------|
| `npm start`        | Khởi động project (Expo)       |
| `npm run android`  | Chạy trên Android              |
| `npm run ios`      | Chạy trên iOS                  |
| `npm run web`      | Chạy trên trình duyệt Web      |
| `npm run reset-project` | Dọn dẹp cache & node_modules |

## 📦 Các thư viện chính

| Nhóm              | Thư viện |
|------------------|---------|
| **UI/UX**        | `@expo/vector-icons`, `expo-linear-gradient`, `expo-blur`, `expo-font`, `expo-haptics`, `expo-image`, `react-native-root-toast` |
| **Navigation**   | `expo-router`, `@react-navigation/native`, `@react-navigation/bottom-tabs`, `@react-navigation/native-stack`, `@react-navigation/elements` |
| **Networking**   | `axios` |
| **State & Form** | `formik`, `@react-native-async-storage/async-storage` |
| **Animation**    | `react-native-reanimated`, `react-native-gesture-handler` |
| **System**       | `expo-constants`, `expo-splash-screen`, `expo-status-bar`, `expo-linking`, `expo-system-ui`, `expo-web-browser` |
| **Web Support**  | `react-native-web`, `react-native-webview` |

## 🤝 Đóng góp

Mọi đóng góp đều được chào đón!  
- Fork repo  
- Tạo nhánh (`git checkout -b feature/my-feature`)  
- Commit thay đổi (`git commit -m 'Add feature'`)  
- Push nhánh (`git push origin feature/my-feature`)  
- Tạo Pull Request

## 📜 Giấy phép

Dự án này được phát hành dưới [MIT License](LICENSE).

---

👨‍💻 **Tác giả**: [Thinh Nguyen](https://github.com/thinhnguyen07022004)
