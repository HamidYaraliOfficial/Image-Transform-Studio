# Image Transform Studio

---

## English

### Overview
**Image Transform Studio** is a powerful, interactive desktop application built with **Python**, **PyQt6**, and **OpenCV (cv2)**. It enables users to apply real-time **geometric image transformations** such as translation, rotation, scaling, similarity, affine, and perspective transforms — all through an intuitive GUI.

Designed for developers, students, and digital artists, this tool visualizes matrix-based transformations instantly with full control over parameters, interpolation methods, and border handling.

---

### Features
- **6 Transformation Modes**:
  - Translation
  - Rotation (with custom or auto center)
  - Scaling (with aspect ratio lock)
  - Similarity (rotation + uniform scale + translation)
  - Affine (3-point control)
  - Perspective (4-point homography)
- **Real-time Preview** with side-by-side original/result view
- **Threaded Processing** – No UI freeze during heavy operations
- **Advanced Interpolation**:
  - Nearest, Linear, Cubic, Lanczos
- **Border Handling**:
  - Constant, Replicate, Reflect, Wrap
  - Custom border value
- **Multilingual Support**: English & Persian (RTL layout)
- **Theme Switching**: Light & Dark modes
- **Sliders + SpinBoxes** for precise control
- **Progress Feedback** during processing

---

### Requirements
- Python 3.9+
- PyQt6
- OpenCV (`cv2`)
- NumPy

---

### Installation
1. Install dependencies:
   ```bash
   pip install PyQt6 opencv-python numpy
   ```
2. Save the script as `image_transform_studio.py`
3. Run:
   ```bash
   python image_transform_studio.py
   ```

---

### Usage
1. **Load** an image using the "Load Image" button.
2. Select a transformation tab.
3. Adjust parameters using sliders or input fields.
4. Click **"Apply"** to see the result instantly.
5. Use **"Save Result"** to export the transformed image.
6. Switch between **English/Persian** and **Light/Dark** themes anytime.

> Tip: Enable "Auto Center" in Rotation for natural pivot behavior.

---

### Project Structure
- `image_transform_studio.py` – Complete standalone application
- No external assets or config files required

---

### Contributing
Contributions are highly encouraged!  
Feel free to:
- Add new transformation types
- Support more languages
- Improve UI/UX
- Optimize performance

Submit a pull request with clear descriptions.

---

### License
Released under the **MIT License**. Free to use, modify, and distribute.

---

## فارسی

### نمای کلی
**استودیو تبدیل تصویر** یک برنامه دسکتاپ قدرتمند و تعاملی است که با استفاده از **پایتون**، **PyQt6** و **OpenCV** ساخته شده است. این ابزار به کاربران امکان می‌دهد تا **تبدیل‌های هندسی تصویر** مانند انتقال، چرخش، مقیاس‌دهی، تبدیل مشابه، آفین و پرسپکتیو را به‌صورت زنده و با کنترل کامل اعمال کنند.

مناسب برای برنامه‌نویسان، دانشجویان و هنرمندان دیجیتال، این ابزار تبدیل‌های ماتریسی را به‌صورت بصری و فوری نمایش می‌دهد.

---

### ویژگی‌ها
- **۶ حالت تبدیل**:
  - انتقال
  - چرخش (با مرکز دلخواه یا خودکار)
  - مقیاس‌دهی (با حفظ نسبت تصویر)
  - تبدیل مشابه (چرخش + مقیاس یکنواخت + انتقال)
  - تبدیل آفین (کنترل با ۳ نقطه)
  - تبدیل پرسپکتیو (هموگرافی ۴ نقطه‌ای)
- **پیش‌نمایش لحظه‌ای** با نمایش کنار هم تصویر اصلی و نتیجه
- **پردازش در ترد جدا** – بدون قفل شدن رابط کاربری
- **درون‌یابی پیشرفته**:
  - نزدیک‌ترین، خطی، مکعبی، لانکزوس
- **مدیریت حاشیه**:
  - ثابت، تکرار، بازتاب، پیچش
  - مقدار حاشیه قابل تنظیم
- **پشتیبانی چندزبانه**: فارسی و انگلیسی (چیدمان راست‌به‌چپ)
- **تغییر تم**: روشن و تاریک
- **اسلایدر + فیلد عددی** برای کنترل دقیق
- **نوار پیشرفت** در حین پردازش

---

### پیش‌نیازها
- پایتون ۳.۹ یا بالاتر
- PyQt6
- OpenCV (`cv2`)
- NumPy

---

### نصب
1. نصب کتابخانه‌ها:
   ```bash
   pip install PyQt6 opencv-python numpy
   ```
2. فایل را با نام `image_transform_studio.py` ذخیره کنید
3. اجرا:
   ```bash
   python image_transform_studio.py
   ```

---

### نحوه استفاده
1. با دکمه **«بارگذاری تصویر»** یک تصویر انتخاب کنید.
2. یکی از تب‌های تبدیل را انتخاب کنید.
3. پارامترها را با اسلایدر یا فیلد عددی تنظیم کنید.
4. روی **«اعمال»** کلیک کنید تا نتیجه فوراً نمایش داده شود.
5. با **«ذخیره نتیجه»** تصویر تبدیل‌شده را ذخیره کنید.
6. در هر زمان بین **فارسی/انگلیسی** و **تم روشن/تیره** جابه‌جا شوید.

> نکته: در تب چرخش، گزینه **«مرکز خودکار»** را فعال کنید تا چرخش طبیعی‌تر باشد.

---

### ساختار پروژه
- `image_transform_studio.py` – برنامه کامل و مستقل
- بدون نیاز به فایل تنظیمات یا منابع خارجی

---

### مشارکت
مشارکت شما بسیار ارزشمند است!  
می‌توانید:
- نوع تبدیل جدیدی اضافه کنید
- زبان‌های بیشتری پشتیبانی کنید
- رابط کاربری را بهبود دهید
- عملکرد را بهینه کنید

درخواست کشش (Pull Request) با توضیحات واضح ارسال کنید.

---

### مجوز
تحت **مجوز MIT** منتشر شده است. آزاد برای استفاده، تغییر و توزیع.

---

## 中文

### 项目概览
**图像变换工作室（Image Transform Studio）** 是一款功能强大的交互式桌面应用程序，使用 **Python**、**PyQt6** 和 **OpenCV** 构建。它支持用户通过直观的图形界面实时应用 **几何图像变换**，包括平移、旋转、缩放、相似变换、仿射变换和透视变换。

适用于开发者、学生和数字艺术家，此工具可即时可视化矩阵变换，并提供对参数、插值方法和边界处理的完全控制。

---

### 功能亮点
- **6 种变换模式**：
  - 平移
  - 旋转（支持自定义或自动中心）
  - 缩放（支持保持宽高比）
  - 相似变换（旋转 + 统一缩放 + 平移）
  - 仿射变换（3 点控制）
  - 透视变换（4 点单应性）
- **实时预览**：原始图像与结果并排显示
- **线程处理**：复杂操作不卡顿界面
- **高级插值**：
  - 最近邻、双线性、双三次、Lanczos
- **边界处理**：
  - 常量、复制、反射、环绕
  - 可自定义边界值
- **多语言支持**：英语 & 波斯语（支持 RTL 布局）
- **主题切换**：亮色 & 深色模式
- **滑块 + 数值输入**：精确控制参数
- **进度条反馈**：处理过程中显示状态

---

### 系统要求
- Python 3.9+
- PyQt6
- OpenCV (`cv2`)
- NumPy

---

### 安装步骤
1. 安装依赖：
   ```bash
   pip install PyQt6 opencv-python numpy
   ```
2. 将代码保存为 `image_transform_studio.py`
3. 运行程序：
   ```bash
   python image_transform_studio.py
   ```

---

### 使用指南
1. 点击 **“加载图像”** 按钮选择图片。
2. 在左侧选择一种变换模式。
3. 使用滑块或输入框调整参数。
4. 点击 **“应用”** 立即查看效果。
5. 使用 **“保存结果”** 导出变换后的图像。
6. 随时切换 **英文/波斯语** 和 **亮/暗主题**。

> 小贴士：在“旋转”选项卡中启用 **“自动中心”** 可获得更自然的旋转效果。

---

### 项目结构
- `image_transform_studio.py` – 完整独立的可执行程序
- 无需外部资源或配置文件

---

### 贡献代码
我们非常欢迎贡献！您可以：
- 添加新的变换类型
- 支持更多语言
- 优化用户界面
- 提升性能

请提交带有清晰说明的 Pull Request。

---

### 许可证
基于 **MIT 许可证** 发布。自由使用、修改和分发。