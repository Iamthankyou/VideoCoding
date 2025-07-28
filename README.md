# VideoCoding

This repository contains two reference software implementations for the Versatile Video Coding (VVC) standard (H.266/VVC - ISO/IEC 23090-3):

## Projects

### VVCSoftware_VTM

VTM (VVC Test Model) is the official reference software for the H.266/VVC video coding standard. It includes both encoder and decoder functionality and serves as a reference implementation to establish and test conformance and interoperability.

Key features:
- Complete implementation of the H.266/VVC standard
- Reference encoder and decoder
- Provides a basis for VVC-related research and development
- Developed jointly by ITU-T VCEG and ISO/IEC MPEG

[Read more about VVCSoftware_VTM](./VVCSoftware_VTM/README.md)

### vvenc

VVenC (Fraunhofer Versatile Video Encoder) is a fast and efficient H.266/VVC encoder implementation with a focus on practical usability and performance.

Key features:
- Easy to use with five predefined quality/speed presets
- Perceptual optimization for improved subjective video quality
- Extensive parallelization with good scaling
- Frame-level single-pass and two-pass rate control

[Read more about vvenc](./vvenc/README.md)

## Getting Started

Each project has its own build instructions and documentation. Please refer to the respective README files linked above for detailed information on how to build and use these software packages.

## About H.266/VVC

The Versatile Video Coding (VVC) standard is the successor to H.265/HEVC, offering approximately 50% better compression efficiency at the same perceived video quality. It was finalized in July 2020 and is particularly optimized for 4K and 8K video content, HDR, and 360° video.

## License

Each project has its own licensing terms. Please refer to the respective README files and license documents in each project directory for details.

---

# VideoCoding (Tiếng Việt)

Repository này chứa hai phần mềm triển khai cho chuẩn nén video Versatile Video Coding (VVC) (H.266/VVC - ISO/IEC 23090-3):

## Các Dự Án

### VVCSoftware_VTM

VTM (VVC Test Model) là phần mềm tham chiếu chính thức cho chuẩn nén video H.266/VVC. Phần mềm này bao gồm cả chức năng mã hóa và giải mã, đóng vai trò là triển khai tham chiếu để thiết lập và kiểm tra sự phù hợp và khả năng tương tác.

Các tính năng chính:
- Triển khai đầy đủ chuẩn H.266/VVC
- Bộ mã hóa và giải mã tham chiếu
- Cung cấp nền tảng cho nghiên cứu và phát triển liên quan đến VVC
- Được phát triển bởi ITU-T VCEG và ISO/IEC MPEG

[Đọc thêm về VVCSoftware_VTM](./VVCSoftware_VTM/README.md)

### vvenc

VVenC (Fraunhofer Versatile Video Encoder) là một triển khai bộ mã hóa H.266/VVC nhanh và hiệu quả với trọng tâm vào tính khả dụng và hiệu suất thực tế.

Các tính năng chính:
- Dễ sử dụng với năm cấu hình chất lượng/tốc độ được định nghĩa sẵn
- Tối ưu hóa cảm nhận để cải thiện chất lượng video chủ quan
- Hỗ trợ song song hóa rộng rãi với khả năng mở rộng tốt
- Kiểm soát tốc độ bit một lần và hai lần ở cấp độ khung hình

[Đọc thêm về vvenc](./vvenc/README.md)

## Bắt Đầu

Mỗi dự án có hướng dẫn xây dựng và tài liệu riêng. Vui lòng tham khảo các tệp README tương ứng được liên kết ở trên để biết thông tin chi tiết về cách xây dựng và sử dụng các gói phần mềm này.

## Về H.266/VVC

Chuẩn Versatile Video Coding (VVC) là phiên bản kế nhiệm của H.265/HEVC, mang lại hiệu quả nén tốt hơn khoảng 50% với cùng chất lượng video cảm nhận được. Nó được hoàn thiện vào tháng 7 năm 2020 và được tối ưu hóa đặc biệt cho nội dung video 4K và 8K, HDR, và video 360°.

## Giấy Phép

Mỗi dự án có điều khoản cấp phép riêng. Vui lòng tham khảo các tệp README tương ứng và tài liệu giấy phép trong thư mục của từng dự án để biết chi tiết.
